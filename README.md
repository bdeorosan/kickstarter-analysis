# An Analysis of Kickstarter Campaigns

### UCBE Bootcamp: Week 1 - Excel - Louise needs help finding characteristics of successful Kickstarter campaigns

#### Overview of Project

Louise needs help mining Kickstarter campaign data to learn about the profiles of those campaigns that are the most successful in obtaining full funding.  In this Module, she’d like to know specifically how the different campaigns fared with respect to the time of year and the funding amount requested by the campaigner(s).  The campaigns in question have to do with theatrical performances.


#### Analysis and Challenges

Kickstarter campaign data from 2010 to 2017 was used for this analysis.  This data collection was used to isolate successful, failed, and canceled theatrical campaigns, along with their respective launch dates and funding goals.  Firstly, a pivot table was used to filter isolate the theatrical campaign data and to plot the total number of successful, failed, and canceled campaigns by month, in total for all years obtained.  A subsequent pivot chart was created to visualize any trends in the data (see Figure 1).

  
![Figure 1: Theater Outcomes Based on Launch Date](https://github.com/bdeorosan/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png?raw=true)
<p align="center">
Figure 1: Theater Outcomes Based on Launch Date
</p>


Next, Excel’s COUNTIFS function was used to gather the number of successful, failed, and cancelled theater campaigns vs. their funding goals, which were represented mostly by $5,000 increments through $50,000; campaigns requesting more than $50,000 were also considered.  Subsequently, the percentage of successful, failed, and canceled campaigns was calculated at each goal increment, and the resulting percentages were plotted vs. those increments (see Figure 2).  

![Figure 2: Outcomes Based on Goal](https://github.com/bdeorosan/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png?raw=true)
<p align="center">
Figure 2: Outcomes Based on Goal
</p>


One interesting future challenge could be trying to analyze what happens during the “down” times of the year, seemingly from September through March.  Because the data focused more so on the financing of campaigns, and lacks survey data from donors, one would have difficulty understanding why people’s interest in funding Kickstarter campaigns wains during those times of the year.  This would be helpful info for Louise so that she can look out for any of those tendencies in the future should that behavior start to appear in the summer time as well.


#### Results

To maximize her changes of a successful campaign, Louise should target the month of May for her launch, but if she cannot launch then, she would not wait any longer than the end of June.  She should avoid trying to launch her campaign in the last couple months of the year.  To maximize her chances of a successful campaign focusing on a play, Louise should target a funding goal of $5,000 or less.  Also, she definitely has the right idea in mind as far as choosing a theatrical performance, specifically a play: campaigns to fund plays did not get canceled at all between 2010 and 2017.

The main limitation of this data set is that it only goes up to 2017; the world has changed significantly since then, especially after 2020.  If Louise were to launch her efforts in 2021, it may be much more difficult to achieve a successful campaign with the economic stress that the pandemic has placed upon potential donors and hosting venues, irrespective of the launch date or the funding goal.  To truly dig down into the successful campaigns, that data could be isolated and subjected to a box/whisker plot.  It would also be interesting to analyze data for the funding of musicals and theatrical spaces, which would likely show hammer home that plays are the best route to take if attempting to fund something within the realm of theater.
