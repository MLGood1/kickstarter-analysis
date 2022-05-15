# Kickstarting with Excel
## Overview of Project
Louise is starting a crowdfunding campaign to fund her new play Fever.  She has a budget of about $10,000.  She wants to know what specific factors made other similar campaigns successful.
### Purpose
The purpose of this project is to perform analysis on Kickstarter crowdfunding data to look for trends.
## Analysis and Challenges
•	Color coded the outcomes column using conditional formatting to highlight whether a campaign was successful, failed, canceled, or live.          
•	Calculated the percentage of campaigns funded using the round function.
•	Calculated the average donation amount for each campaign.
•	Separated the Category/Subcategory columns into two new columns to different between the parent category and the subcategory to for better filtering options

![image](https://user-images.githubusercontent.com/104471775/168491419-d651d486-1bab-4a1a-b7ff-e7ca15a49117.png)

•	Created a pivot tables and charts to document the number of successful, canceled, or failed campaigns broken down by the parent category (ex. Theater) and subcategory (ex. Plays).
•	Converted the unix timestamp dates to day-month-year format 
•	Create a pivot line chart to explore the relationship between outcomes and launch date.
•	Calculated the measures of central tendency and spread for the successful and failed campaigns.
•	Tried to identify any outliers 
### Analysis of Outcomes Based on Launch Date
•	Created a years column based on the Dated Created Conversion column.
•	Created a pivot table filtered by the parent category, plays, based on launch date.
•	Created a line chart of the pivot table to visualize the relationship between launch date and outcome (ie. Successful, failed, or canceled).

 ![image](https://user-images.githubusercontent.com/104471775/168491447-1e13e1d1-ab77-425c-9c53-3ea21ef0acf3.png)
 
### Analysis of Outcomes Based on Goals
•	Using the Countifs function, calculated the percentage successful, failed, or canceled plays based on the funding goal amount.

 ![image](https://user-images.githubusercontent.com/104471775/168491482-78113fd8-1504-40eb-8a3a-b2f0cc607da9.png)
 
•	Created a line chart to chart the relationship between goal amounts and the outcome of the campaign.

![image](https://user-images.githubusercontent.com/104471775/168491494-36a6b2bd-b470-4fda-a446-303b30c39652.png)

### Challenges and Difficulties Encountered
## Results
- Conclusions about Outcomes based on Launch Date:
1.	Campaigns launched in the summer months (May, June, and July) are more successful.
2.	Campaigns are more likely to fail in October.
- What can you conclude about the Outcomes based on Goals?
1.	Campaigns with lower goal amounts (those with a goal less than $1,000 ranging to about $5,000) are more successful. 
- Limitations of the dataset:
•	Doesn’t look at the relationship between play type and success rate of being funded.
•	Location, does the location of Louise’s play affect the number of backers?
- What are some other possible tables and/or graphs that we could create?
•	A line graph of outcomes based on average donation.
•	A line graph of outcome based on play type.
