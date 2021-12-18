
# Kickstarting with Excel

## Overview of Project

### Purpose

    Analyze a fundraising campaign dataset above to determine what factors 
    were determining for its cancellation, failure and success.

    In this way, Louise can make the decision to make the adjustments relevant
    to her own campaign proposal and thus have a greater chance of 
    success (data driven).

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date


    From the data set, a pivot table of the set was created (image A-1), 
    which had as a filter the years and the parent_category and as values 
    the count of the results and finally the release dates as rows (image A-2). 
  
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/pivot_table.png) A-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/pivot_filters.png) A-2

    Filtering was done by theater only in parent category (image A-3), once done
    perform the insertion of the line graph by clicking on insert, then graphing 
    the lines and then verifying that the x and y axes are on the correct places, 
    then proceeded to edit the colors and finally We would have this analysis 
    completed (image A-4).
    
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/filter_category.png) A-3
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png) A-4

### Analysis of Outcomes Based on Goals

    First I made use of the function COUNTIFS() from the sheet kickstarter 
    taking column D which is where the goals are and in number successful, 
    failed, canceled based on the criteria of the first row was generating 
    the pertinent filters (image B-1), for this analysis I only take into 
    account the category plays, for which I do not generate any value in the 
    canceled column, then add the totals of each column with the SUM() function
    and generate the percentages for the relevant columns (image B-2).
    
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/B-2.png) B-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/B-3.png) B-2

    Once the table was completed, I was able to generate the line chart,
    clicking on insert and then verifying that the x and y axes
    and they are where they should be, this point of creation is concluded
    analysis (image B-3).
    
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/B-4.png) B-3

### Challenges and Difficulties Encountered

    In both cases, obtaining the type of graph that I required was quite easy,
    the complicated thing was in the case of the first to obtain the colors that were
    in the example and in the case of the second because it had not filtered by
    plays and did not take into account the starting point of the ranges, it generated me
    certain differences, but in the end with patience I managed to finish it.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. The best range of times to undertake a campaign of this style is between the months of April to July (image C-1).
    2. The worst time to start a campaign comes from September to January (image C-2).

![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/C-1.png) C-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/C-2.png) C-2
    
- What can you conclude about the Outcomes based on Goals?
    1. That those campaigns that exceed 10 thousand dollars will have very difficult to be successful (image D-1).
    2. To have a better chance of success it is good to have a bell that is in the range of 1000 to 5000 dollars (image D-2).

![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/D-1.png) D-1
![](https://github.com/maadpeal/kickstarter-analysis/blob/main/resources/D-2.png) D-2

- What are some limitations of this dataset?
    1. That could be very general if a person is interested in a specific country, perhaps with a dataset focused more on a specific country with specific places, more interesting and particular observations could be achieved.
    2. The year, they are data from at least 4 years ago, with a fresher dataset, more precise information could be given to the person who requires the analysis.

- What are some other possible tables and/or graphs that we could create?
    1. The time lapses of the successful and unsuccessful campaigns, a count by days of duration with a bar graph could give us another dimension.
