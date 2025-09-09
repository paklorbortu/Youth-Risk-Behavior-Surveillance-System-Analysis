# Youth-Risk-Behavior-Surveillance-System-Analysis

## Project Overview
This project analyzes the Youth Risk Behavior Surveillance System (YRBSS) dataset 
to uncover trends in health-risk behaviors among middle school students in the United States. 
The focus is on Physical Activity, Mental Health, Substance Use, and Violence.

The goal is to transform raw survey data into meaningful insights using SQL (BigQuery) 
for querying and Power BI for visualization. The project also explores demographic and temporal 
trends to support data-driven decision-making in public health and education.

## Objectives

- Identify key risk behavior trends over the past decade.

- Analyze behavioral differences by sex, race, and grade.
 
- Determine which risky behaviors have shown the greatest increase.

- Provide actionable recommendations for youth health programs.

## Dataset Overview

- Source: Centers for Disease Control and Prevention (CDC)

- Format: CSV

- Period covered: 1991–2017

- Size: 751K rows × 35 columns

- Key variables include:

- YEAR: Year of survey

- Sex, Race, Grade: Demographics

- Topic & Subtopic: Behavior categories (e.g., Physical Activity, Substance Use)

- Greater_Risk_Data_Value / Lesser_Risk_Data_Value: Risk indicators

- Sample_Size: Number of respondents

##  Methodology

- Data Loading: Imported dataset into Google BigQuery.

- SQL Analysis: Queried trends by topic, demographic groups, and time.

- Visualization: Designed Power BI dashboards to highlight insights.

- Reporting: Compiled findings into a structured report with conclusions and recommendations.

## Key Findings

- Physical Activity: Inactivity is highest among females in 7th and 8th grade.

- Mental Health: Risks are rising, especially among females; 2017 saw a peak.

- Substance Use: ~9% of students have tried or currently use cigarettes, e-cigarettes, or marijuana, with 8th graders reporting the highest use.

- Violence & Bullying: Over 42% experience in-school bullying, and ~20% experience cyberbullying.

- Demographic Insights: Males report more fights and weapon carrying; Native Hawaiian or Other Pacific Islander students are the most inactive.

- Trends: Mental health concerns, inactivity, and substance experimentation are increasing.

## Visualizations (Power BI Dashboard)

Screenshots of the Power BI dashboard created for this project:

<img width="1432" height="803" alt="yrbss_dash_1" src="https://github.com/user-attachments/assets/cb73d5ad-ff47-485b-a18a-42b10b26972f" />


The dashboard allows filtering by sex, race, grade, and year, providing interactive insights into trends across risk behaviors.

## Recommendations

- Expand daily physical activity programs, especially for females in 7th–8th grade.

- Improve mental health counseling services, focusing on female students.

- Launch anti-vaping campaigns for early teens (particularly 8th-grade males).

- Strengthen digital safety education to combat cyberbullying in high-risk groups.

## Tools & Technologies

- SQL (Google BigQuery) → Querying and aggregations

- Power BI → Dashboards and visualizations

- Python →  Graphing

## Report

The full project report (with detailed analysis and recommendations) is included here:
`Youth Risk Behavior Surveillance System (YRBSS) Report`


## Acknowledgements

- Centers for Disease Control and Prevention (CDC).

