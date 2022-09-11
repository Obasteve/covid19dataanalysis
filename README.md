                              STEP 1
                              Data Collection
I  performed a web scrap to obtain data from the NCDC website. I also obtain data from the John Hopkins repository, and imported the provided external data. After which all the obtained data was saved in a dataframe.
                              STEP 2
After saving the data sets in a dataframe, I use the head() and the infor() method to view the obtained data sets both from the repository and the scrapped data.
                             STEP  3 
         Data Cleaning and Preparation
I converted the data to the appropriate data type, renaming of column and extraction of daily data for Nigeria from the Global daily Cases, commas were also removed. 
                              STEP 4
 - Analysis
I generated a pandas barplot   that shows the Top 10 states in terms of Confirmed Covid cases by Laboratory test

I also generated a plot that shows the Top 10 states in terms of Discharged Covid cases by  Sorting the values
The Plot the top 10 Death cases was also drawn.
There was  a generation of line plot for the total daily confirmed, recovered and death cases in Nigeria
                            STEP 5

I determine the daily infection rate, Pandas diff method was to find the derivate of the total cases after which a line plot was generated.
                             STEP 6

I calculated the  maximum infection rate for a day and also find the date
I determine the relationship between the external dataset and the NCDC COVID-19 dataset. I  generated a line plot of top 10 confirmed cases and the overall community vulnerability index on the same axis. This was possible by using a merging function after which a new dataframe was created. The nlargest function was used to get the top 10 cases
                             STEP 7
I determine the relationship between the external dataset and the NCDC COVID-19 dataset. A regression plot was plotted using the  Confirmed Cases and Population Density. 

                             STEP 8

More analyses were conducted with by usimg the vulnerability index and the top 10 confirmed cases.
I determine the effect of the Pandemic on the economy. by compare the Real GDP value Pre-COVID-19 with Real GDP in 2020. Pandas melt was used to generate a new datframe to plot the barplot.
                             STEP 9
Using axhline, draw a horizontal line through the graph at the value of Q2 2020.
Write out your observation
Note: Do not limit your analysis to the provided TODOs. Perform more analyses e.g
Check for more external dataset
Ask more questions & find the right answers by exploring the data
