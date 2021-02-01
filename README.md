# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends 
## Overview of Project 
### Purpose of the Analysis
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Created a pivot table based on the Kickstarter data and sorted by the parent category "theater" to count the number of successful, failed and canceled campaigns based on launch date for each month of the year. Created a line graph based on the pivot table, as displayed below. 
![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals 
Created a graph based on the percentage of successful, failed and canceled "plays" for each goal range. 
![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
## Results 

- What are two conclusions you can draw about the Outcomes based on Launch Date?
* May, June and July had the highest number of successful kickstarters. Conversely, November, December and Jan/Mar had the least number of successful kickstarters. From this we can conculde that late spring/summer is the best time for a launch date and late fall/winter is the worst time for a launch date.
* We can also conclude that in general, based on overall kickstarter outcomes over the full year, the theater campaigns were more likely to reach their goal than not.  

- What can you conclude about the Outcomes based on Goals?
* There was a 100% failure rate for campaigns with goals of 5,000-9,999 and 45,000-49,000. 
* The highest success rates were for campaigns with goals of less than 1,000; 1000-4999, and 35000 to 39999 and 40000 to 44999 consecutively. 
* There is not a clear linear correlation between goal amount and success rate, so there may be other factors at play here 
* The vast majority of campaigns (regardless of success) were in the <$15,000 goal range 

- What are some limitations of this dataset?
* Limitation of Outcomes based on Launch Date: The number successful/failed for each month does not account for the volume of campaigns month-to-month. It may be more informative to have a "percentage successful / percentage failed" based on total campaigns for each nonth. 
* CURRENCY DIFFERENCES COUNTRY-to-COUNTRY NOT ACCOUNTED FOR 
*CAMPAIGN LENGTH NOT ACCOUNTED FOR (and according to Kickstarter website: "We recommend setting your campaign at 30 days or less. Campaigns with shorter durations have higher success rates, and create a helpful sense of urgency around your project."
* no division based on theater play SUBCATEGORY for launch date, but there was for goals. Also, launch date compared raw numbers while goals compared percentages. 

- What are some other possible tables and/or graphs that we could create?
* PERCENTAGE of successful campaigns based on launch date 
