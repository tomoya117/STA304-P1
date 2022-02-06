Title: "Investigation of whether older people result in a higher hospitalized rate when infected by COVID-19"

This investigation provides information to individuals who get infected by COVID-19 in the future when making a decision of whether they should consider going to the hospital for treatment or not. By understanding the risk of home treatment leading to a more severe condition and possibly prognostic symptoms, it enables individuals to make their decisions with more responsibility. However, it is also important to note that this study only shows the trends in the hospitalization rate for each age group, and that the result from this investigation does not prove any causation between the age and the level of symptoms. 

The project uses a statistical software language, R, and packages, tidyverse and knitr. Installation of these packages in R is the first step to begin this analysis. Then, download the data of COVID-19 Cases in Toronto from Open Data Toronto Portal using the read_csv function. To remove any unnecessary observations, use na.omit function. Since the descriptions of age groups are very long, rename them by creating a new variable using mutate and case_when functions. Then, create a table using kable function to show the first 10 observations of the data set. Since this data set is difficult to see, use group_by and summarize functions to group the observations by each age group and get a total count of hospitalized people and total infected people for each age group. Then create a table using these information to show that there is are trends. To further visualize the data, create a bar graph using ggplot function. Use the fill option to show the bars for both "Yes" and "No" for the variable, 'Ever Hospitalized'. 

The visualizations using the table and graph enable the audience to observe the relationship between the age group and hospitalization rate. 