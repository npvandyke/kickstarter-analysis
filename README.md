# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends 
## Overview of Project 
### Purpose of the Analysis
Per the request of my client, Louise, I've performed the following analyses to determine how various Kickstarter campaigns for theater projects fared in relation to their launch date and funding goals, and to uncover any potential trends to inform strategies for success for future theater-based Kickstarter campaigns that Louise may wish to launch. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In order to analyze the outcomes of theater-based Kickstarter campaigns based on their launch date, I created a pivot table of the Kickstarter dataset filtered by the parent category "theater." This provided a count of the number of successful, failed, and canceled theater campaigns organized by the month of their launch date. I've included a line graph generated from the pivot table below:

![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

It should be noted that this graph includes all theater campaigns from the Kickstarter dataset, which covers multiple theater subcategories, campaign countries, and years of launch. 

### Analysis of Outcomes Based on Goals 
In order to analyze the outcomes of play-based Kickstarter campaigns based on their fundraising goal, I created a graph of the percentage of successful, failed and canceled Kickstarter campaigns for projects under the subcategory "plays," organized by fundraising goal ranges. The graph was generated off of a chart created to organize the Kickstarter dataset by fundraising goal range, outcome and subcategory using the `Countifs` Excel function. The graph is displayed below: 

![Outcomes_vs_Goals](Resources/Outcomes_vs_Goals.png)

It should be noted that unlike the Theater_Outcomes_vs_Launch graph, this graph includes only the subcateory "plays" from the parent category "theater." Further, while this graph displays the campaign outcomes based on the _percentage_ of campaigns which were successful, failed or canceled, the Theater_Outcomes_vs_Launch graph displays the raw _number_ of successful, failed and canceled campaigns rather than displaying them as a percentage. 

### Challenges and Difficulties Encountered
Potential challenges that could be encountered in working with this dataset include structuring the "Theater_Outcomes_vs_Launch" pivot table to include only _months_ for the launch date (rather than months and years), and remembering to include all three relevant conditions (subcategory, fundraising goal range and outcome) when organizing the "Outcomes_vs_Goals" dataset using the `Countifs` Excel function. 

## Results 
#### Conclusions Drawn from Outcomes Based on Launch Date 
Based on the 'Theater_Outcomes_vs_Launch' graph provided above, its apparent that May, June and July had the highest number of successful theater-based Kickstarter campaigns. Conversely, November, December and January/March had the lowest number of successful theater-based Kickstarter campaigns. This may indicate that the best time to launch a successful Kickstarter campaign for a theater project would be in the late spring or summer, with the worst time to lauch a successful campaign being in the late fall or winter.

Regardless of the launch date, its apparent that on a month-by-month basis there were always a greater number of successful Kickstarter campaigns for theater projects than failed campaigns, so Louise can feel optimistic about her odds of launching a successful kickstarter campaign for her next theater project. 

#### Conclusions Drawn from Outcomes Based on Goals
Based on the Outcomes_vs_Goals graph provided above, its apparent that there was a 100% failure rate for play-based Kickstarter campaigns with fundraising goals between $5,000 - $9,999 and between $45,000 - $49,000. We can also see that the highest success rates for play-based Kickstarter campaigns were those with goals of less than $1,000; followed by those with goals between $1,000 - $4,999; $35,000 - $39,999; and $40,000 - $44,999. 

The graph does not uncover any linear correlation between the success rate of play-based Kickstarter campaigns and the value of their fundraising goals, indicating that there may be other more influencial factors affecting the campaign success rate. However, it is worth noting that the vast majority of play-based Kickstarter campaigns (868 out of 954, or over 90%) had fundraising goals of less than $15,000, suggesting it may be most realistic to set a fundraising goal under the $15,000 range. 

#### Limitations of the Dataset
##### Limitation of "Outcomes Based on Launch Date" Data: 
The graph indicating the number of successful, failed and canceled Kickstarter campaigns based on the month of their launch date may be misleading in that it displays a raw number of campaigns, rather than accounting for month-to-month variation in campaign volume by displaying a percentage of successful/failed/canceled campaigns. For example, the month with the greatest number of successful Kickstarter campaigns (May), was also the month with the greatest number of failed Kickstarter campaigns- in other words the high _volume_ of success does not necessarily indicate a high _rate_ of success. It may be more informative to display these campaign outcomes as a percentage based on total volume per month of launch date. 

##### Limitations of "Outcomes Based on Goals" Data: 
The data for Kickstarter campaign outcomes based on fundraising goals has been filtered by the subcateory "plays" under the parent category "theater." If Louise wishes to launch a campaign for a different category of theater, for example a musical, this data may be less informative for her. Further, because this data has been more specifically categorically filtered than the data regarding campaign outcomes based on launch date, it is less directly comparable than had it been left with the more general category filter of "theater." 

It should also be noted that multiple countries with multiple currencies have been included in this dataset. It would be more informative had the currencies been standardized to all reflect the same value. 

##### Other Limitations of the Dataset: 

The only two potential factors that have been accounted for in this analysis of Kickstarter campaign outcomes were the campaign launch date and fundraising goal range, evaluated independently. Obviously there are other potential factors that may affect the success of a campaign. For example, according to Kickstarter's website: 
>We recommend setting your campaign at 30 days or less. Campaigns with shorter durations have higher success rates, and create a >helpful sense of urgency around your project. 
Clearly campaign length is a potential factor effecting success rate which has not been accounted for in this analysis. Another potential factor might include whether or not the project was a staff pick. 

Further, as stated above, the affects of the launch date and the fundraising goal range on the campaign outcome were evaluated independently in this analysis. Especially given that there was no linear correlation between fundraising goal range and campaign outcome in the dataset, the fundraising goal ranges might prove more informative if evaluated within the subset of each launch date month. 


#### Further Potential Analyses  

* PERCENTAGE of successful campaigns based on launch date 
