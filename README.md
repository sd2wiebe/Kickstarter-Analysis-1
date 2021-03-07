# Kickstarter Analysis

## Overview of Project 
The purpose of this analysis is to filter and visualize data that will help my client Louise launch a successful fundraising campaign for her play, “Fever”. To aid Louise, I have looked at data points from successful and unsuccessful Kickstarter campaigns similar to hers, in order to give insight on the specific factors that might contribute to success or failure. 

## Analysis and Challenges

### Analysis of Outcomes based on Launch Date
For this analysis I was able to use a large data set of Kickstarter campaigns with many variables, including: Goal amount, Launch Date, Outcome, Country, Category and Subcategory, and more. The first thing I did was created a pivot table to summarize the data points I was interested in. I wanted to see if there was any correlation between the month of ‘Launch Date’ and whether the campaign was successful or not. However, the data produced was still too vague, so I filtered the data in the pivot table to only show campaigns more similar to Louise’s. For this, I filtered to show only the data with subcategory “Theater” and based out of the United States. Thus, I was able to create this [pivot table.](https://github.com/sd2wiebe/Kickstarter-Analysis-1/blob/main/Pivot%20Table.png)
From the data in the pivot table, I created a line chart to visualize the relationship: 

<p align="center"

![alttext](https://github.com/sd2wiebe/Kickstarter-Analysis-1/blob/main/Theater_Outcomes_vs_Launch.png)

</p>
We can see that the biggest gap between successful campaigns and failed campaigns occurs in May and carries over into June. To further clarify this relationship, I made a new column that displays the percentage of successful campaigns for each month, along with the mean:

<p align="center"

![alttext](https://github.com/sd2wiebe/Kickstarter-Analysis-1/blob/main/Launch%20date%20percentages.png)

</p>





