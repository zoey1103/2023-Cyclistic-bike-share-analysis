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
**Key Stakeholders :**
  1. Lily Moreno: Director of Marketing.
  2. Cyclistic executive team.


### 3.Prepare

  1. The data I used is Cyclistic’s Historical Trip Data to analyze and identify trends.
  2. This year 9 months data from 2023 January 1 to 2023 September 30 is used for analysis.
  3. The data is stored in CSV files. Each file contains one month data. Thus a total of 9 .csv files.
  4. The data is structured data ie., Organised data.
  5. For the purposes of this case study, datasets are generated from a fictional company. The datasets are appropriate and it have been made available by Motivate International Inc. under this **license**(https://www.divvybikes.com/data-license-agreement).
  6. As this data is collected by a real bike sharing company in Chicago, there are **no issues with bias or credibility**. So its Reliable, Original, Current and Cited (as in ROCCC). I do **not** think its **Comprehensive** because this data lacks some information.
  7. Data Integrity: It's **Accurate**, **Consistent** and **Trustworthy**.

### 4. Process
  1. Combine 9 months data into a file
  2. Explore data null value and basic trends, ex.
  3. Create new columns for further anlysis :
      * Timestamp transfer: month/day_of_week/hour
      * Trip duration column add to investigate travel time
  4. Decide to eliminate empty start_station/end_station rows and rows that travel time is shorter then 1min or longer than a day
  5. Create new table for cleaned data
  6. Analysis trend from cleaned data
       -  Time Aspect
         -  Monthly number of rides bewteen memebr and casual
         -  Weekly number of rides bewteen memebr and casual
         -  Hourly number of rides between member and casual
          
       - Bike Type Aspect
         - Different usage preference between member and casual
     
       - Station Aspect
         - Largest usage station between member and casual
