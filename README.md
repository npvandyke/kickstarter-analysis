# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends 
## Overview of Project 
### Purpose of the Analysis
Per the request of my client, Louise, I've performed the following analyses to determine how various Kickstarter campaigns for theater projects fared in relation to their launch date and funding goals, and to uncover any potential trends to inform strategies for success for future Kickstarter campaigns that Louise may wish to launch. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In order to analyze the outcomes of theater-based Kickstarter campaigns based on their launch date, I created a pivot table of the Kickstarter data filtered by the parent category "theater." This provided a count of the number of successful, failed, and canceled theater campaigns organized by the month of their launch date. I've provided a line graph generated off of the pivot table below:
![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)
It should be noted that this graph includes all theater campaigns in the Kickstarter data, which covers multiple theater subcategories, campaign countries, and years of launch. 
### Analysis of Outcomes Based on Goals 
In order to analyze the outcomes of play-based Kickstarter campaigns based on their goal amount, I created a graph of 
![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
## Results 
#### Conclusions Drawn from Outcomes Based on Launch Date 
* May, June and July had the highest number of successful kickstarters. Conversely, November, December and Jan/Mar had the least number of successful kickstarters. From this we can conculde that late spring/summer is the best time for a launch date and late fall/winter is the worst time for a launch date.
* We can also conclude that in general, based on overall kickstarter outcomes over the full year, the theater campaigns were more likely to reach their goal than not.  

#### Conclusions Drawn from Outcomes Based on Goals
* There was a 100% failure rate for campaigns with goals of 5,000-9,999 and 45,000-49,000. 
* The highest success rates were for campaigns with goals of less than 1,000; 1000-4999, and 35000 to 39999 and 40000 to 44999 consecutively. 
* There is not a clear linear correlation between goal amount and success rate, so there may be other factors at play here 
* The vast majority of campaigns (regardless of success) were in the <$15,000 goal range 

#### Limitations of the Dataset
* Limitation of Outcomes based on Launch Date: The number successful/failed for each month does not account for the volume of campaigns month-to-month. It may be more informative to have a "percentage successful / percentage failed" based on total campaigns for each nonth. 
* CURRENCY DIFFERENCES COUNTRY-to-COUNTRY NOT ACCOUNTED FOR 
*CAMPAIGN LENGTH NOT ACCOUNTED FOR (and according to Kickstarter website: "We recommend setting your campaign at 30 days or less. Campaigns with shorter durations have higher success rates, and create a helpful sense of urgency around your project."
* no division based on theater play SUBCATEGORY for launch date, but there was for goals. Also, launch date compared raw numbers while goals compared percentages. 

#### Further Potential Analyses  
* PERCENTAGE of successful campaigns based on launch date 
