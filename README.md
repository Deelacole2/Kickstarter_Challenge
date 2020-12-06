# Kickstarter_Challenge
Kickstarter trend analysis based on launch date

# Kickstarting with Excel

## Overview of Project

### Purpose
 The purpose of this project was to shed some light on the outcomes of successful, failed and canceled Kickstarter campaigns based on their funding goals and launch date. As you will see, the funding goal is a seemingly important factor in whether or not the campaign will be successful.

## Analysis and Challenges
 ** Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.
 #### Analysis:
 * Initial Analysis: I started with converting the launch and deadline dates from Unix to a timestamps. This allowed me to see the timestamps in a manageable format. Next the Category and Subcategory column was separated by delimiter to allow for more granular analysis.
 
 There were two main components to the analysis:
 1. Parent Category: Theater VS. Outcomes
 2. Outcomes VS. Funding Goal for Plays
 ---
 
 1. Parent Category: Theater VS. Outcomes
 
 ![Outcomes by Launch Date](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/LaunchDatebyOutcome.Pivot.png)
 
 * This pivot table was created to allow for analysis and visualization of the monthly trends of the outcomes. The timestamps were grouped by month to allow us the get a look at which months were most successful 
 *
 *
 
 2. Outcomes VS. Funding Goal for Plays

![Outcomes vs. Funding Goals](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/Outcomes.Goals.Table.png)

*
*
*

 #### Challenges
 
 * This project was relatively straight forward but the columns that contained the Unix (which I didn't know were a thing) values were the only small challenge. Intially I was unsure of how to deal with them. The initial attempt to just format the number to a timestamp was unsuccessful and the explanantion and subsequent formula helped me conver the Launch and Deadline columns.


### Analysis of Outcomes Based on Launch Date

Components: Pivot table (previously posted) & Line Chart

![Theater Outcomes Based on Launch Date](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

* As you can see from the pivot table above, the most successful months for kickstarters were May and June
*
*

### Analysis of Outcomes Based on Goals

Components: Manually created table and Line Chart

![Funding Goal Vs. Outcome for Plays](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/Outcomes_vs_Goals.png)

*
*
*

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
* Theater campaigns that are launched in the months of May or Jun have a higher success rate.
* December is worst month to launch a campaign

- What can you conclude about the Outcomes based on Goals?
* From our table and chart you can conclude a number a things, first, it's best to keep your goal under $5,000 for the best chance for success. And on the opposite end, campaigns with goals of 50,000 or more are much less likely to succeed.

- What are some limitations of this dataset?
*

- What are some other possible tables and/or graphs that we could create?
*
*
*
