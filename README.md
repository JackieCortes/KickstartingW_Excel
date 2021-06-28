# Kickstarting with Excel

## Overview of Project:
_This piece presents the answer to new Louise’s questions to perform the first challenge for Module I: Excel for the Data Analytics Boot Camp.
This project is the extension of a first analysis for the same person who wants to know recommendations to launch a campaign for a play called “Fever” in the USA, attempting crowdfunding a goal of 10,000 USD. 
On this second chance, Louise had more questions regarding the launch dates and the funding goals. It is important to say that her campaign is almost ended._

_Note:The analysis was in Excel. The database contains information from 2010 to 2017 for a different kind of crowdfunding projects around the Globe. The database included a goal and pledged amounts, backers number, country and start/end dates, project name, outcome, category/subcategory project._

### Purpose
This project shows analyses to support new Louise's questions. Now Louise almost reached the fundraising goal for her play "Fever." And, she wanted to know how different the campaign results were depending on their launch dates and funding goals. 

## Analysis and Challenges
The following data were created with a pivot table or filling a matrix using functions as COUNTIFS() and SUM() each one has its respective line chart.  The frequent challenge for this exercise was the frozen Excel. 

### Analysis of Outcomes Based on Launch Date
The following chart was from a pivot table. The information was filtered and composed by the parent category is equal to "Theater," filtered by month versus outcome: "successful," failed," canceled."
The line for the successful outcomes has a rise reaching the peak in May and starting the fall with June. So on these Months, the other campaigns had high probabilities of achieving the results. Fo the rest of the months, there are more chances of not reaching the goal. 
![Theater Ouctomes based on Launch Date](https://github.com/JackieCortes/KickstartingW_Excel/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The following chart is from a matrix. The matrix contains filtered data for only "plays." This matrix was categorized using different goal ranges and dividing the information by outcomes ("successful," failed," canceled."). From this matrix, we can observe:
1.	More than 65% of the plays had a goal of less or equal to 4,999 USD.
2.	Any project with a goal greater than 5000 USD increased its failure percentage.
3.	When you have a project in the range of 5,000 – 10,000 USD, you have almost the same chances of success or failure.
![Theater Ouctomes based on Goals](https://github.com/JackieCortes/KickstartingW_Excel/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
One of the difficulties I found was forgetting your initial question and observing other results that data offered. Also, it is essential to point out that when Excel increases in the number of charts, colors, and different look and feel features, the memory size increased, and the app was frozen or delayed in save the file. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  The Launch Date is essential for campaigns; we can observe that all campaigns can trace a trend that offers an advantage or disadvantage.
  * May and June are excellent months to launch the campaign. All the campaigns have better chances when they are started in these two months. Although, May will have better opportunities, and more attempts were attempted.
  * In October, you have a high probability of failing, and December is not a good month to launch the campaign. 
_Note: From the previous analysis was observed that the usual last of a campaign is a month._

- What can you conclude about the Outcomes based on Goals?
  Most of the play budgets are adjusted below 9999 USD. Going further, any campaign below 4999 USD had more chances to reach its objective, and between 5000 – 10000 USD have the same chances of success or failure.
  
- What are some limitations of this dataset?
  The only limitation that I observed from the data set was the UNIX data stamp information for dates. If you did not know about this kind of information, we would lose important data.  And we would not have followed the trend. However, also it is observed that we did not know any input about the failure or successful results. It would be essential to know the reason behind or the campaign characteristics. 
- What are some other possible tables and/or graphs that we could create?
  1.  A chart showing the correlation among the successful and failed plays campaigns organized by pledged range versus the backer number to know if the backer number is essential or not. 
  2. A chart or pivot table to show if the campaign's duration impacts the outcome.
  3. If the reasons for the failure or success were available, it would be possible to compare the campaign characteristics.

If you need to see further details, please review [Kickstarter_Challenge.zip](https://github.com/JackieCortes/KickstartingW_Excel/blob/main/Kickstarter_Challenge.zip)
