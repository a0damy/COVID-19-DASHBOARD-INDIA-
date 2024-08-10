# COVID-19-DASHBOARD-INDIA-
The project enables the creation of a user-friendly dashboard that provides real-time visualizations and actionable insights into the COVID-19 pandemic's trajectory and consequences.

## Table of Content
- Problem Statement
- Objectives
- The Data
- Tools
- Data Cleaning and Preparation
- Exploratory Data Analysis
- Insights
- Dashboard
- Recommendation

## Problem Statement
The COVID-19 pandemic has been ravaging India, posing a significant threat to public health, economy, and social stability. The rapid spread of the virus has overwhelmed the country's healthcare infrastructure, and there is a pressing need for real-time insights into the pandemic's trajectory to inform effective mitigation strategies.

Specific Challenges include;
- Rapidly increasing case numbers and mortality rates
- Limited access to healthcare facilities, particularly in rural areas
- Inadequate data availability and dissemination for effective decision-making
- Difficulty in tracking the virus's spread across different demographics, regions, and age groups.

## Objectives
Develop a data-driven solution to track the COVID-19 pandemic's trajectory in India, providing real-time insights into case numbers, mortality rates, hospitalizations, and vaccination efforts. The solution should enable policymakers, healthcare professionals, and the public to make informed decisions and respond effectively to the crisis.

## The Data
The dataset for this project was provided by InternCareer. This include 3 datasets; Covid_19_india, Covid_vaccine_statewise and Statewise Testing Details. After thorough cleaning and modelling, the covid-19 daily cases dataset provides information on the daily reported covid-19 cases, including; 
  1. Number of confirmed cases
  2. Deaths
  3. Recoveries
  4. Vaccination
  5. Testing data

<img width="949" alt="Covid model" src="https://github.com/user-attachments/assets/f7a1d7c9-a8bc-4fef-b527-84fe41100fd4">

## Tools
- Power Query Editor - Data cleaning and preparation
- Power BI - Data Visualization

## Data Cleaning and Preparation
After successfully importing the data into Power BI, I moved on to the data cleaning and preparation phase. This involved implementing the following steps to ensure the data was suitable for analysis:
- Removing rows that have values which are missing
- Changing the data type of some values within the column
- Removing columns that are not relevant to the task
- Data modelling by connecting the three datasets together

## Exploratory Data Analysis
The project answers the following questions:
- What are the daily trends in confirmed cases, deaths, recoveries and testing?
- What is the severity of cases in different region or state?
- What is the progress of the vaccination?
- Which is the most affected state/region?

## Insights
  1. Confirmed cases, deaths, recoveries and testing:
     - 5.5 billion cases have been reported.
     - Tragically, 73.4 million lives have been lost to the virus. The dashboard shows a steady increase in total deaths over   
       time, with the highest spike in July 2021 and Maharashtra emerges as the most affected state.
     - 5.0 billion individuals have successfully recovered. The steepest rise in recoveries was from March to August 2021.
     - To date, a massive 88 billion samples have been analyzed, with a remarkable 13 billion testing negative for COVID-19. 
       Notably, a staggering 320 million cases have returned positive results, highlighting the significant scale of the 
       pandemic's impact.

       <img width="955" alt="Covid1" src="https://github.com/user-attachments/assets/613ca6cf-ee05-450c-bc44-1d8809066f98">

  2. The map chart with colour-coding bubbles illustrate the severity of cases in different states with Maharashtra having the 
     highest deaths at 23.7 million and Karnataka at 6.05 million.
  3. A total of 27 billion individuals have received at least one dose of the vaccine. CoviShield is the predominant vaccine, with 
     62 billion doses administered and age-group 18 - 44 years account for the highest vaccination rate at 15 billion.

     <img width="957" alt="Covid2" src="https://github.com/user-attachments/assets/925d56d6-b73e-4c65-a9a9-f79e5de5edfd">

  4. Maharashtra emerges as the most affected state with over 23 million deaths and over 1 billion recoveries.

     <img width="947" alt="Covid4" src="https://github.com/user-attachments/assets/d676e891-ad3b-4b92-a6a9-901a9156777a">


## Dashboard

   <img width="949" alt="Covid3" src="https://github.com/user-attachments/assets/35404f53-beaf-48c7-a7ac-9128e499230d">

## Recommendation
   To combat the ongoing pandemic, we urge an urgent escalation of vaccination campaigns, focusing on regions with lower coverage 
   rates. Additionally, targeted interventions should be implemented in areas most severely affected by the virus to contain its 
   spread. Furthermore, we must bolster our public health infrastructure to ensure efficient testing and treatment capacities, 
   thereby saving lives and mitigating the crisis.
