# Kickstarting with Excel
The file that was used for this analysis project: [Kickstarter Challenge](https://github.com/boggesstristyn/kickstarter-analysis/files/8598198/Kickstarter_Challenge.xlsx)

## Overview of Project
### Purpose
The purpose of this project is to take large Kickstarter data and uncover different trends that will be helpful to our client, Louise, as she prepares her own Kickstarter for her play *Fever*. Louise's play has already come close to reaching the fundraising goal in a relatively short amount of time, now we've been asked to visualize the relation between launch dates and fundraising goals, and how the campaign managed.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
With the data for theater outcomes based on launch date, we created a pivot table showing the number of successful, failed, and canceled campaigns by month and with this table, we were able to plot the information on a line graph to visualize the trends, if any, in order to provide more insight as to when the best time to launch a campaign.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103851131/164999180-7a111fbe-4748-46e3-a550-3e698e409138.png)

### Analysis of Outcomes Based on Goals
In order to analyze the outcomes based on goals, we took the "Play" subcategory and looked at how many successful, failed, and canceled campaigns there were. We then converted the number in each outcome to a percentage based on the total number of campaigns in a specific goal range to plot them on a line graph, visualizing the relation between campaign outcomes and goal ranges.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103851131/164999187-f57e0f17-3786-41db-ba8c-1cbca02dbeff.png)

### Challenges and Difficulties Encountered
I encountered some difficulties with the COUNTIFS statements; it took me a moment to understand the formatting and necessary criteria. In the end I was able to realize the order in which the information to be pulled my be inputted.

## Results
From looking at the "Outcomes Based on Launch Date" graph, we can see that May seems to have the most successful amount of campaigns, while December has the least. May had the most successful campaigns, but June and July also significantly performed better than other months.

Outcomes based on goals showed that when the goal is less $1,000, the rate of success is the highest and rate of failure is the lowest. On the flip of that, goals in the range of $15,000 to $34,990 and more than $45,000, the rate of failure is highethan the rate of success.

A limting factor in this dataset were the outliers; we don't have any additional data on what caused these outliers, leaving us unable to analyze further.

I think that a type of bar graph could've been another option for both the "Outcomes Based on Launch" and "Outcomes Based on Goals" graphs. Another helpful table for the client could be one that shows the number of backers and average donation for plays.
