# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project was to apply Excel skills learned in module one to a real life situation. The project was an extension of the scenario developed throughout the module, and focused on both displaying taught skills as well as developing new ideas.

In terms of practicing skills introduced throughout the module, this project requires the use of

- applying filters
- creating Pivot Tables and Pivot Charts
- creating and naming new sheets

An example of a PivotChart is shown below.

![Outcomes vs Goals chart](/resources/outcomes_vs_goals.png)

Charts such as these help to visualize the data being presented to a client. In this case the chart plots the initial goal of the campaign on the x-axis vs the percentage of successful campaigns on the y-axis. It shows that in most cases a lower initial goal will generally lead to a more successful campaign.

Some new skills not explicitly taught were

- COUNTIFS functions
- SUM functions

An example of the code for a COUNTIFS function in Excel is highlighted below

`=COUNTIFS(Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays",Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<5000")`

 In the instructions it asks for "links to code." I'm not entirely sure what is meant by that. Above is an example of COUNTIFS code. I used the following site to learn how to use COUNTIFS between two numbers. [COUNTIFS instructions](https://www.extendoffice.com/documents/excel/2412-excel-count-cells-between-two-values.html)

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In researching succesful kickstarter theater campaings, one critical aspect to look at is comparing the outcome of kickstarter theater campaings versus their initial launch date. The chart shown below helps to visualize these results.

![Chart showing theater outcomes vs launch date](/resources/theater_outcomes_vs_launch.png)

As the chart indicates, the most successful theater campaigns appear to have been launched between April and August, with the most successful launches occuring in May. As a result it would be advised to launch a theater campaign as close to May as possible. Additionally, it is advised to avoid launching a campaign beginning in September and running through January.

### Analysis of Outcomes Based on Goals

In looking at an analysis of theater campaigns based on initial goal, it is onece again helpful to visualize the results. The chart below shows initial campaign goal on the x-axis compared to the percentage of successful campaigns on the y-axis.

![Outcomes vs Goals chart](/resources/outcomes_vs_goals.png)

Generally speaking, campaigns with lower initial goals are more successful. There do appear to be some outliers to this rule. For some reason campaigns in the mid-$30,000 range were unusually successful. Additional research and analysis would be needed to better explain this anomaly. One possible explanation is that there were very few campaigns launched with this goal and those few that were launched were successful. 

### Challenges and Difficulties Encountered

The following challanges/difficulities were encountered while performing this analysis.

* My first challange was involing Excel operating very slowly. When using a new MacBook Air running the latest OS and version of Excel, performing any calculations, insertion of PiviotTables or Charts was painstakingly slow. After switching to an older Mac running an earlier OS performance improved dramatically.
* The second challenge I encountered was with using the COUNTIFS function. I have used this funciton on multiple previous occassions, however I needed to use Google to research how to include criteria for obtaining counts between to constraints.
* The final challange I encourtered is with the purpose of the readme deliverable. It is not clear if this taks was to be performed as a pretend analysis for a pretend client, or if the purpose was to document my experience with the module as a student. For example, is this question on difficulities desiged to explore difficulties I had in completing the module or to describe difficulties in the analysis which may or may not effect the end results.

## Results

### The following conclusions can be drawn about outcomes based on launch date.

1. As inddicated above, based on the Outcomes vs. Launch Date comparrison it appears that the most successful time to start a Theater Kickstarter campaign is between the months of April and August, with May being the most successful month.
2. In addition to recommending the most successful time to start a campaign, we can also recomment when **NOT** to start a campaing. It is not recommended to begin a Theater Kickstarter beginning in September and running through January. As indicated by the results, campaings begun around the holidays are not nearly as successful as those begun in the second quarter of the calendar year.

### The following conclusions can be drawn about outcomes based on goals.

1. From an anlalysis of outcomes versus initial goal it appears that projects with a lower initial goal are more successful in being fully funded. Projects with an initial goal of less than $10,000 are fully funded 70% of the time. As the initial goal increases the success rate generally decreases. This negative correlation holds for all but two funding goal divisions.
2. Projects in the $35,000-$45,000 range are funded at a higher rate than was expected. This could potentially be due to there being fewer projects in these goal ranges. Additional analysis and research would be required to fully explore this correlation.

### The following limitations of this data set can be identified.

1. One limitation of the data is that it does not include a method for filtering by prior success of kickstarter campaigns by the same requestor. For example, is a campaign more likely to be successful if the person submitting the request has had a previous kickstarter campaign successfully funded?
2. A second limitation of the data is the inability to see individual donation amounts. While total number of backers, funds received, and thus average donation are available, without a list of pledge amounts it is difficult to remmove and account for individual outliers in the data.

### What are some other possible tables and/or graphs that we could create?

* I would be interested to create a chart showing "Staff Pick" vs outcome. Here is an example of such a chart. Interestingly this chart clearly shows that if a project is a staff pick it is much more likely to be funded.

![Staff Pick vs Outcome PivotChart](/additional-resources/staff-pick_vs_outcome.png)

* We could also choose to look at country of origin vs outcome. Is there a correlation between where a project originates from and it's chances for success?
