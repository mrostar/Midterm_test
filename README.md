# Suicide Analysis Project

## Tableau Public Link
https://public.tableau.com/views/CDCSuicideAnalysisProject/TheStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Introduction
This analysis is meant to help visualize trends in suicide death rates in the United States. It aims to showcase which specific subgroups in the population (broken down by gender, age, and race/ethnic group) have the highest rates. This information can be used to help determine who is at the highest risk and, from there, establish the appropriate preventative measures.  

## Data/operation abstraction design
The data used for this project was downloaded from the Centers for Disease Control and Prevention (CDC) website and contains information on estimated death rates for suicide in the United States, measured as deaths per 100,000 residents. It includes data from 1950 up to 2018 and is broken down by gender, age, and race/ethnic group. This original dataset contains both age-adjusted and crude estimates, with the majority being crude. Because of this, I filtered the original dataset in Python to include crude estimates only prior to uploading it to Tableau. In Tableau, I created multiple calculated fields, including those used to calculate the differences in average estimates among age ranges by year, as well as the number of non-null estimates taken for each specific race/ethnic group and year. Finally, I created a calculated field that shows the average estimate based on the race/ethnic group selected.

## Future work
In the future, I would like to gather more recent data that includes the years 2019 up to the present (2024). This could allow me to determine whether there have been any changes in the trends I previously identified. I also think it would be interesting and useful to compare the U.S. suicide death rates to the rates of other countries. This could help determine if trends are similar or different, and from there I could examine how other countries address and prevent suicide. 
