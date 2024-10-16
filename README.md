# Aircrash-history-dashboard

EXCEL PROJECT: Analysis on Air Crashes Full Data from 1908 – 2023

This Project aims to explore the Air Crashes Full Data to showcase analytical skills and data visualizations. I got the Air Crash Full Data 1908 – 2023 from Kaggle, the project execution is as follows.

RESEARCH QUESTIONS

I first studied the data so as to have an idea of possible research questions that could be worked on, since the data is a record of plane crashes from 1908 – 2023 presented in a table format, the best thing to do was to check each column to see what values I would be working with, for example date column, location, aircraft type, aircraft manufacturer, number of casualties etc. after this I was able to come up with eight research questions  which are as follows:

•	Total Air fatalities since inception.

•	Total Passengers aboard the flights.

•	Count of all the aircraft lost.
•	Ground fatalities.
•	Aircraft operators with most crashes recorded.
•	Aircraft models involved in most crashes.
•	Yearly trend of air crashes.

ANALYSIS STEPS

After outlining my research questions, I went ahead to import the dataset which is a csv file, I went ahead to clean the data using the data transformation option. The cleaning process is outlined below:
•	Combined the year, quarter, month and day columns into a single column as a date.
•	Removed duplicates for the entire table.
•	Filling N/A values in columns with true values which were wrongly entered in another column.
•	Manually corrected wrongly entered values in columns i.e. Lufthansa Deutsche which is meant to be Deutsche Lufthansa.
•	Finally loading the data.

 Once my data had been loaded, I set out to begin the analysis based on my research questions by making use of pivot tables and also performing calculations. To get my yearly trend of air crashes I inserted a pivot table into a new sheet then dragged the date into rows and aircraft into the values section which I used to plot a chart. For the monthly wise relationship between number of people aboard the flights and fatalities recorded, I inserted a pivot table into the same sheet I used for the first one then proceeded to drag months to the rows section then sum of people aboard and fatalities recorded to the values section and plotted a dual clustered column chart. These steps were repeated for the aircraft models involved in most crashes and aircraft operators with most crashes recorded including their respective visuals.      								As for the calculated fields they were values picked from the grand total row of the respective pivot tables they were found. After this I went ahead to design a dashboard to display the visualizations created.
![Screenshot 2024-10-16 125545](https://github.com/user-attachments/assets/fbf10390-dd86-4fe2-8478-fcb16cd8789e) 

FINDINGS

After visualizing the data, the following findings were made:
•	Air crashes peaked most between 1939 - 1945 this can be attributed to the second world war which also occurred within that period.
•	Starting from the 2000s there has been a steady decline in the occurrence of air crashes which could be due to improved safety measures and much better engineering of aircrafts.
•	Boeing 737 B is the aircraft model with the greatest number of crashes mainly due to its wide usage amongst commercial airlines due to it being very economical
•	Most air crashes tend occur towards the month of December due to high traffic of passengers travelling for the holidays.
•	Aeroflot which is a Russian airline has the greatest number of crashes in history as well as fatalities of about 8231 passengers which is five times more than any airline.
•	The United States has the highest number of military aircraft crashes ever recorded in history.
CONCLUSION/RECOMMENDATION
Air travel is the fastest way to travel from country to country and even continent to continent and it has become an integral mode of transport mainly due to speed of transportation, though it might have its flaws but there will always be room for improvement, with advanced research and technologies air travel is swiftly becoming safer and more efficient just as it can be seen on the yearly trend of air crashes chart on the dashboard.
