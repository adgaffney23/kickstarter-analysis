# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project was to apply Excel skills learned in module 1 to a real life situation. The project was an extension of the scenario developed throughout module 1 and focused on both displaying taught skills as well as developing new ideas.

In terms of practicing skills introduced throughout the module, this project requires the use of

- applying filters
- creating Pivot Tables and Pivot Charts
- creating and naming new sheets

An example of a PivotChart is shown below.

![Chart showing theater outcomes vs launch date](/resources/theater_outcomes_vs_launch.png)

Charts such as these help to visualize the data being presented to a client. In this case the chart plots the initial goal of the campaign on the x-axis vs the percentage of successful campaigns on the y-axis. In this case it shows that in most cases a lower initial goal will potentially lead to a more successful campaign.

Some new skills not explicitly taught are

- COUNTIFS functions
- SUM functions

An example of the code for a COUNTIFS function in Excel is highlighted below

`=COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<5000")`

 In the instructions it asks for "links to code." I'm not entirely sure what is meant by that. Above is an example of COUNTIFS code. I used the site following site to learn how to use COUNTIFS between two numbers. [COUNTIFS instructions](https://www.extendoffice.com/documents/excel/2412-excel-count-cells-between-two-values.html)

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In researching succesful kickstarter theater campaings, one critical aspect to look at was comparing the outcome of kickstarter theater campaings versus their initial launch date. The chart shown below helps to visualize thse results.

![Chart showing theater outcomes vs launch date](/resources/theater_outcomes_vs_launch.png)

As the chart indicates, the most successful theater campaings appear to have been launched between April and August, with the most successful launches occuring in May. As a result it would be advided to launch a theater campaing as clost to May as possible. Additionally, it is advised to avoid launching a campaing beginning in September and running through January.

### Analysis of Outcomes Based on Goals

In looking at an analysis of theater campaings based on initial goal, it is onece again helpful to visualize the results. The chart below shows initial campaign goal on the x-axis compared to the percentage of successful campaigns on the y-axis.

![Outcomes vs Goals chart](/resources/outcomes_vs_goals.png)

### Challenges and Difficulties Encountered

## Results

### The following conclusions can be drawn about outcomes based on launch date.

1. As inddicated above, based on the Outcomes vs. Launch Date comparrison it appears that the most successful time to start a Theater Kickstarter campaign is between the months of April and August, with May being the most successful month.
2. In addition to recommending the most successful time to start a campaign, we can also recomment when **NOT** to start a campaing. It is not recommended to begin a Theater Kickstarter beginning in September and running through January. As indicated by the results, campaings begun arounf the holidays are not nearly as successful as those begun in the second quarter of the calendar year.

### The following conclusions can be drawn about outcomes based on goals.

1. Conclusion #1
2. Conclusion #2

### The following limitations of this data set can be identified.

1. Limitation #1
2. Limitation #2

- What are some other possible tables and/or graphs that we could create?
