# Challenge 1: Kickstarting with Excel

## Overview of Project
Analyse a collection of data from crowdfunded kickstarter campaigns to identify meaningful patterns which would reveal optimal conditions for campaign launches.

### Purpose
To analyze the dataset to gain insight on how the fundraising goal and launch date influence the likelihood of success for crowdfunding campaigns within specific criteria (eg. parent category or subcategory).

## Analysis and Challenges
        
        
### Analysis of Outcomes Based on Launch Date
   This chart displays the total number of successful, failed and canceled 'theater' kickstarter campaigns by month from 2009 to 2017. 
   
    ![Theater_Outcomes_vs_Launch](https://github.com/Hala-INTJ/Kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
   This chart displays the percentages of successful, failed and canceled 'plays' kickstarter campaigns by fundraising goal ranges.
    
    ![Outcomes_vs_Goals](https://github.com/Hala-INTJ/Kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered
I didn't encounter any challenges or difficulties. 

A possible challenge would have been encountered if the COUNTIFS function was not avavilable. The solution would have required many repetitive steps. The user would need to filter on the Subcategory "plays", then apply filtering on the different amount ranges of "Goal", then filter on the different outcomes. Then, finally, the counts of the different outcomes "successful/failed/canceled" would be dispalyed at the bottom of the sheet.    

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   * May, June and July appear to be the best months to launch theater kickstarter campaigns. Although the number of failed campaigns remain the same, the number of successful campaigns is considerably higher.
   * December is a poor month to launch a theater kickstarter campaign with a 50% chance of success.  

- What can you conclude about the Outcomes based on Goals?
   * Campaigns for which the subcategory is "plays" and with a goal under $5,000 or between $35,000 and $45,000 are more successful than campaigns with other goal values.
    
- What are some limitations of this dataset?
    * The dataset contains a mix of currencies which would need to be normalized for some analyses.
    * The dataset does not contain the date on which the goal was achieved for campaigns that were successful.
    * Grouping the data for several years will not reveal recent trends. For example, in the theater outcomes analysis, the total for May may not be evenly distributed across all years. It turns out that the theater kickstarter campaigns in May were concentrated in the years 2014 to 2016.

- What are some other possible tables and/or graphs that we could create?
*  Analysis of which categories and/or subcategories are more successful for kickstarter campaigns.
*  Analysis by kickstart success in different countries.
*  Analysis of success/failure percentages based on number of backers.

