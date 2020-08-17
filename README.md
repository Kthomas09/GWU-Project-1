# George Washington University Data Analytics Boot camp 2020 Fall Cohort
Assignment: Project 1
Developers:  Khorolsuren "Suzie" Erdenebat,  Temitayo "David" Olanbiwonnu, Jennifer S, Kent L. Thomas, Cynthia Zhang   

Topic: United States Covid-19 Demographic Data in Relation to Geographic, and Mental Health

Questions: 
1) How is Covid-19 test results compare amongst states?
    Hypothesis: States with larger populations would have a higher percentage test positive. 
2) Which age groups experienced the most mortality in the United States?
    Hypothesis:
3) What impact does Covid-19 have with the United States mental health?
    Hypothesis: 
    
Kent Thomas: 

1) The Data Discription: 
This data set was choosen because it broke down the State, and positive/negitive test results of covid 19 tests within each state. This data set is a continuous record throughout the entire covid 19 pandemic, with running totals in each tally for each week of 2020. For the purposes of this project we are only utilizing the first 55 rows. These 55 rows represent each of the 50 states, plus all United States territories. This would satisfy the most recent covid 19 data.

2) Cleaning Data: 
The method used to clean the data was to first fill all NaN values to 0. Next we isolated the most recent data on the data set, as this data set gave a running total. Finally, we found the percentage of positive test results per state and placed the total tests and percentage positive columns into the dataframe.

3) Data Visualization:
In order to represent all the states for a most recent date (8/6/2020) we created a bar chart. In the bar chart our dependent variables are the 50 US States and US Territories. Our independent variables are the percentage of tests results that were positive for each state and territory.
Additional visualization to be considered would be to group states by region, to see an expanded regional look of the perecentage of positive covid-19 test results.

4) Analysis: 
As of 8/6/2020 the primary location for the highest percentages of tests positive are southern states. Arizona, Alabama, Mississippi, Florida, Georga, South Carolina, and Texas. This test does not support our hypothesis, however there were very vaulable insights to be gained. The states mentioned above were also some of the first to reopen after the initial state wide lockdown's.

Further questions to be considered are how reopening methodology impacts positive covid-19 tests per state. It is important to note that southern states were some of the first states to reopen their economies. Here is a link to an article by the New York Times to help us begin to further expand on these further questions. https://www.nytimes.com/interactive/2020/us/states-reopen-map-coronavirus.html

Jennifer S.:

1) Data Discription:
Covid_Data.csv contains data from dates 2020-02-29(February) - 2020-08-06(August). The intention is to create a program that separates out each state into its own dataframe, clean each new dataframe and analyze the data with the best graphs to show trends in the data.

2) Cleaning Data: 
Separating out the State column to have 55 distinct elements.Turn all 54 States into their own variables to hold a dataframe for covid over time by each state. Make List of States from original dataframe Positive and Negative Cases is Cumulative by State, Need to get the increase/difference by date Loop through States. Make loop for postivie total change by State. Make loop for negative total change by State.Creating a Daterange Series Appending Months to their corresponding formated month exp 20200830 = August Reformatting index so that Index becomes the X Value.

3) Data Visualization: 
This is the map code for NY, FL, and CA over time with an interval from the first case, = Day 1 of covid/March to August = Day 160 Protected Variables are State Names, ie CA do not change these variables


4) Analysis:
For this set of data the states chosen are to represent COVID cases from the supposed beginning of the outbreak to the closest date for this analysis. Based on the graph and the data, the middle of March is when the first cases of COVID appeared. New York was the first state to recieve appreciable cases of COVID. Their cases went from a little under 10,000 to close to 300,000 cases in one month(from April to May). The figure above represents the change in cases over time for the data beginning on March 4, 2020 to August 6, 2020. Other suggestions to consider and study is the relation of the data to the 'Shut down', when each individual state set new guidelines for the openning and closing of businesses. Further work suggested is a cumulative line for cases over the United States, and a graph that shows all the states increase over time.


Cynthia Zang: 

1) Data Discription: 
The United States Census defines senior citizens as people 65 and older, as referenced by https://www.census.gov/library/visualizations/time-series/demo/nia_county_maps.html. Our hypothesis is that senior citizens have a higher chance of dying from the COVID-19 virus due to weaker immune systems. To test this hypothesis, we used data from the CDC's Provisional COVID-19 Death Counts dataset at: https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-Sex-Age-and-S/9bhg-hcku/data.

2) Cleaning Data: 
First we found the unique values in of age groups. Next, we found the values from the COVID-19 Deaths and set it equal to the number of covid deaths. We isolated the data from the age groups and COVID-19 deaths to plot our bar graph. Finally, we found the percentage of Age groups that died from COVID-19

3) Data Visualization: 
We created a bar & pie chart for Age group vs COVID-19 Deaths using pandas Create a pie chart using Pandas.

4) Analysis: 
As of August 5, 2020, people who are 85 years and older have the highest percentage of dying from COVID-19, followed by people between the ages of 65 to 74 years. While these results lined up with our hypothesis that senior citizens are at a higher risk of dying from COVID-19, other factors to consider include income and access to medical services.

Khorolsuren "Suzie" Erdenebat,  Temitayo "David" Olanbiwonnu:

1) Data Discription: 
This subproject involves analysing the use of two data set. First, the mental health data which consists of frequency of symptoms during the pandemic. Second, the covid data which consits the general parameters regarding covid-19 in the United States The end goal is to be able to draw conclusion and prediction on the state of mental illness during the pandemic and analyze the dependent and independent variables pertained to it

2) Cleaning Data: 
We are first checking the unique values in the group and subgroup catagories. Next we picked out the national estimate and created a data frame to consolidate the frame to mental illness, week label and values. Whem merging two dataframes together, first we imported the data set Covid_data.csv, subset the data to the dates of July 16 to July 21, and renamed the state column. Finally, we merged the two data sets.

3) Analysis:  
(a).Line graph was used to show the trajectory of the indicators of mental illness with the exponential increase in covid cases nationally
(b). The corrrelation of mental health and surge in covid cases was strongly positive as assummed with a 0.767 coefficient
(c). Descriptive statistics was used to analyze the relationship between indicators of mental health and covid cases by states. All indicators showed weak positive correlation with few outliers


Sourcing: 
(David, Suzie) mental_health - https://www.cdc.gov/nchs/covid19/pulse/mental-health.htm, (Cythia, Jen) covid_underscore_death.csv- https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-Sex-Age-and-S/9bhg-hcku/data, (Jen, Kent) State_Covid_Data - https://covidtracking.com


 

