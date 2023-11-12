# 2023-Cyclistic-bike-share-analysis
## How do annual members and casual riders use Cyclistic bikes differently?

### 1. Introduction 

This case study is the **Capstone Project of Google Data Analytics Professional Certificate** . In this case study I am working as a junior data analyst in the marketing analyst team at Cyclistic, a fictional bike-share company in Chicago.

Cyclistic is a bike-share program that features more than 5,800 bicycles and 600 docking stations. Cyclistic sets itself apart by also offering reclining bikes, hand tricycles, and cargo bikes, making bike-share more inclusive to people with disabilities and riders who can’t use a standard two-wheeled bike. The majority of riders opt for traditional bikes; about 8% of riders use the assistive options. Cyclistic users are more likely to ride for leisure, but about 30% use them to commute to work each day.

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations across Chicago. The bikes can be unlocked from one station and returned to any other station in the system anytime.

The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, my team wants to understand **how casual riders and annual members use Cyclistic bikes differently**. From the insights, our team will design a new marketing strategy to **convert casual riders into annual members**. But first, Cyclistic executives must approve our recommendations, so they must be backed up with **compelling data insights** and **professional data visualizations**.

There are 3 pricing plans: single-ride passes, full-day passes, and annual memberships. **Customers who purchase single-ride or full-day passes are referred to as Casual riders**. **Customers who purchase annual memberships are Cyclistic members**.

In order to answer the key business questions, I followed the steps of the data analysis process: ask, prepare, process, analyze, share, and act.

### 2. Ask

**Business Task**: 
  1. Identify trends to provide insigths for excuetive teams aprroval
  2. Recommendations for marketing team how to convert casual riders to memebrship riders

**Key Stakeholders**:
  1. Lily Moreno: Director of Marketing.
  2. Cyclistic executive team.


### 3.Prepare

  1. The data I used is Cyclistic’s Historical Trip Data to analyze and identify trends.
  2. 9-months data from 2023 January 1 - 2023 September 30 are used for analysis.
  3. The data is stored in CSV files. Each file contains one month data. Thus a total of 9 .csv files.
  4. The data is structured data ie., Organised data.
  5. For the purposes of this case study, datasets are generated from a fictional company. The datasets are appropriate and it have been made available by Motivate International Inc. under this **license**(https://www.divvybikes.com/data-license-agreement).
  6. As this data is collected by a real bike sharing company in Chicago, there are **no issues with bias or credibility**. So it's Reliable, Original, Current and Cited (as in ROCCC). I do think it's  **Not Comprehensive** because this data lacks some information.
  7. Data Integrity: It's **Accurate**, **Consistent** and **Trustworthy**.

### 4. Process

  1. All the process are done by SQL
  2. Combine 9 months data into a file
  3. Explore data null value and basic trends, ex.
  4. Create new columns for further anlysis :
      * Timestamp transfer: month/day_of_week/hour
      * Trip duration column add to investigate travel time
  5. Decide to eliminate empty start_station/end_station rows and rows that travel time is shorter then 1min or longer than a day
  6. Create new table for cleaned data

  
### 5. Analysis trend from cleaned data
     
**1. Time Aspect**

  * Monthly number of rides bewteen memebr and casual
  * Weekly number of rides bewteen memebr and casual
  * Hourly number of rides between member and casual
  * Average travel time per ride between member and casual
          
**2. Bike Type Aspect**

  * Different usage preference between member and casual
  * Percentage use of each biketype
     
**3. Station Aspect**
  * Largest usage station per number of rides
  * Rank the largest usage station member and casual rider percentage

### 6. Share

  1. Table and visual graphs for each topics
  2. Create Dashboard by Tableau for the summary
  3. Conclusion:
     * Jun-Sep has the heaviest usage during a year, considering weather, summer time people enjoy a bike ride more often
     * By number of rides, member > casual, however by travel time casual user > member
     * Looking into hourly rides, 16-19 has the higest run rate, we can suspect mostly it's used by commute
     * By the bike type, member using classic bike takes nearly a half(40%) of all types
     * Docked bike is only used by casual riders
     * Top 3 heaviest used station are Streeter Dr & Grand Ave, DuSable Lake Shore Dr & Monroe St, Michigan Ave & Oak St
     * Trends also show that among 3 top stations, up to 61%-73% users are casual rider, which brings up a good target to market on these users

### 7. Act

  My Recommendations:
  1. Giving out membership discount on summer seasons to attract more casual riders
  2. Broadcast a trial membership experience when casual riders use it 3 times a week at commute hour
  3. Target casual riders at top 3 stations, hold a campagin around these stations, and to promote cyclistic membership.
        (ex. design a free city ride tour for membership, and casual rider can join tour for $50, meantime join the membership today has yeraly membership discount, and free city ride tour)
    
