# Kickstarter_Challenge
Kickstarter trend analysis based on launch date

## Overview of Project

### Purpose
 The purpose of this project was to shed some light on the outcomes of successful, failed and canceled Kickstarter campaigns based on their funding goals and launch date. As you will see, the funding goal and the launch date are important factors in whether the campaign will be successful. The analysis was performed at the request of a playwright that is contemplating starting her own kickstarter to fund her play and we wanted to know the trends of success and failure of previous campaigns.

## Analysis and Challenges

 #### Analysis:
 Initial Analysis: 
 * I started with converting the launch and deadline dates from Unix to a timestamp. This allowed me to see the timestamps in a manageable format. 
 * The Category and Subcategory column was separated by delimiter to allow for more granular analysis.
 * The year was extracted from the date for easier grouping anf filtering.
 
 There were two main components to the analysis:
 1. Outcomes Based on Launch Date- Parent Category: Theater VS. Outcomes
 2. Outcomes Based on Goals- Outcomes VS. Funding Goal for Plays
 ---

### Analysis of Outcomes Based on Launch Date

Components: Pivot table & Line Chart
 
 ![Outcomes by Launch Date](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/LaunchDatebyOutcome.Pivot.png)
 
 * This pivot table was created to allow for analysis and visualization of the monthly trends of the outcomes. The timestamps were grouped by month to allow us the get a look at which months were most successful based on a count of the outcomes. This pivot table was filtered by Parental Category to only include Theater related kickstarters.
 
 ![Theater Outcomes Based on Launch Date](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Components: Manually created table and Line Chart

![Outcomes vs. Funding Goals](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/Outcomes.Goals.Table.png)

* This table was manually created to demonstrate the relationship (if there is one) between the amount of the funding goal and the percentage of successful, failed and canceled campaigns. There are also counts of each outcome and the corresponding funding goal.

![Funding Goal Vs. Outcome for Plays](https://github.com/Deelacole2/Kickstarter_Challenge/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

 #### Challenges
 
 * This project was relatively straight forward but the columns that contained the Unix values (which I didn't know was a thing) were the only challenge. Initially I was unsure of how to deal with them. The initial attempt to just format the number to a timestamp was unsuccessful and the explanation and subsequent formula helped me convert the Launch and Deadline columns.

## Results
---
- What are two conclusions you can draw about the Outcomes based on Launch Date?

* Theater campaigns that are launched in the months of May or Jun have a higher success rate, although launching earlier in the year generally bodes better for the outcome.
* December is worst month to launch a campaign, the success to failure ratio is almost 1:1.
---
- What can you conclude about the Outcomes based on Goals?

* From our table and chart, you can conclude several things, first, it's best to keep your goal under $5,000 for the best chance for success. And on the opposite end, campaigns with goals of 50,000 or more, very seldom succeed. Additionally, the goals from 25,000 to 35,000 have a 70% or more failure rate.
---
- What are some limitations of this dataset?

* The limited amount of data in the set. There is enough data to observe trends, but I believe that additional records would allow for a clearer more concrete analysis.
---
- What are some other possible tables and/or graphs that we could create?

* Country of origin vs. goal Vs. outcome
* The length of the campaign vs. outcome
* Whether or not the kickstarter received the "spotlight" vs outcome or pledged.
* Analysis centered around the parent categories. Theater vs. film & video vs. music.

