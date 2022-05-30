# Kickstarting with Excel

## Overview of Project

Louise wishes to compare how her crowdfunding campaign for her play _Fever_ fared versus different campaigns in relation to their launch dates and fundraising goals. This project will use Microsoft Excel to analyze crowdfunding data to determine this relation. The project utilizes pivot tables and charts to analyze and visualize the data.

### Purpose

Louise came close to her goal in short order and wants a comparison of other campaigns based on goals and start dates. This will determine the effectiveness of the analysis performed prior to her campaign and the advice given.

## Analysis and Challenges

The analysis was performed by creating a pivot table and chart to determine the effect of launch date. The outcome relation to goals was determined by using the countifs function.

### Analysis of Outcomes Based on Launch Date

Campaign launch date's effect on outcome was analyzed by isolating the year each campaign was created. A pivot table was created to show the outcome based on month the campaign started. This data was filtered by parent category and year the campaign started in. Filtering by Theater productions and all years available, the following chart was created.

[Theater_Outcomes_vs_Launch.png](https://github.com/mcwatts88/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

The campaign's goal's effect on outcome was determined by using the countifs function. The outcome, subcategory and goal range were all tabulated by number and percentage of total. The percentage of successful, failed and canceled campaigns in the goal range were charted below.

[Outcomes_vs_Goals.png](https://github.com/mcwatts88/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

Determining the correct field to place in the row, column, filter and values areas of the pivot table proved to be a difficulty at first. This was overcome by placing the fields in each box and determing the effect on the table.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

May was the most successful month to start a campaign with a ratio of 111:52:3 (successful:failed:canceled). Campaigns started in december had an almost equal success to failure rate, the worst of all the months. This is possibly due to holiday budgeting constraints.

- What can you conclude about the Outcomes based on Goals?

A smaller goal (<$5000) led to more successful campaigns. There was a significant dropoff for goals $5000 and above. The success rate jumps overtakes the failure rate again at $35000, but there are so few data points in this range that no advice can be given as to whether this is a good campaign goal.

- What are some limitations of this dataset?

There is more data for lower valued campaigns, so meaningful predictions for high value campaigns cannot be reliably drawn. This dataset is also most helpful to US campaigns, as that comprises most of the data.

- What are some other possible tables and/or graphs that we could create?

There was no analysis done on whether the staff pick or spotlight had any effect on the outcome. Determining this via a pivot table could indicate whether campaign visibility had an effect on the outcome.
