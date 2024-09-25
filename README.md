# Phase 1 Project: Aircraft Risk Assessment 


## Project Overview

The company is expanding  to new industries to diversify its portfolio and is interested in purchasing and operating airplanes for commercial and private enterprise. As a new entrant, they don't know anything about potential risks of aircraft. This project aims to identify the lowest risk aircraft models for the company to start this new business venture, ensuring a safe and profitable entry into the market.

### Business Understanding
#### Problem Statement

Determine which aircraft are lowest risk for the company to start this new business endeavour.

#### Main Objective

The main objective of this analysis is to determine which aircraft models, engine types, and air carriers have the best safety records, as measured by the number of uninjured people hence enabling the company to make informed investment decisions and minimize the risk of accidents in its new commercial and private aviation venture. 

#### Specific Objectives

1.Gather relevant data related to aircraft model, aicraft make, injury severity, total uninjured people, and other pertinent factors.

2.Clean and preprocess the collected data, addressing missing values, duplicates, and formatting issues.

3.Conduct an in-depth exploratory data analysis (EDA) to identify patterns, relationships, and trends in the data.

4.Analyze the number of uninjured people based on aicraft carrier and other relevant metrics.

5.Provide actionable insights and recommendations based on the analysis results.

6.Perform sensitivity analysis to assess the impact of various factors on the identified insights and recommendations.

7.Prepare a comprehensive report with effective visualizations to communicate the findings.


### The Data
#### Data Understanding

In this analysis, we utilised one dataset(the `data` folder is a [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses)) from the National Transportation Safety Board that includes aviation accident data from 1962 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.

It has 90348 rows, and 31 columns. Some of the columns that make the most sense to our analysis are Aircraft make, Aircraft model, Engine Type, Air carrier, Total number of uninjured people, and Injury Severity, to mention just but a few.

#### Data Cleaning

We handled missing values, dropped duplicates, and dropped some rows and columns. Applied appropriate techniques, such as imputation or removal, to address missing values.

#### Exploratory Data Analysis

In this phase, we dived into the dataset to gain insights and understand the relationships and patterns within the data. This process involved a series of analytical techniques and visualizations to explore the aircraft data comprehensively. We will employ various statistical and visual methods to examine the distribution of variables, missing values, and explore correlations between aircraft characteristics and safety outcomes. This phase will help us to refine our research questions, identify potential issues with the data, and inform the development of our predictive model. 

#### Analysis Results

Based on the exploratory data analysis (EDA) conducted, the following key findings and insights were obtained:
1.Most Safe Airplane make: The analysis indicated that **BOEING** airplane make was the most safe as it had most number of uninjured people indicating that it has a better safety record as compared to other airplane makes.

2.Amateir built: Majority of aircraft are not amateur-built. However, a significant proportion of aircraft are amateur-built. This suggests that amateur-built aircraft are a notable segment of the market.

3.Most Safe Airplane model: The analysis indicated that **737** airplane model was the most safe as it had most number of uninjured people indicating that it has a better safety record as compared to other airplane models.

4.Most Safe Air carrier: The analysis indicated that **Delta Airlines** air cairrier was the most safe as it had most number of uninjured people indicating that it has a better safety record as compared to other airplane carriers.

5.Most Safe Engine Type: The analysis indicated that **Turbo Fan** engine type was the most safe as it had most number of uninjured people indicating that it has a better safety record as compared to other engine types.

6.Most likelihood of injury severity: **Substantial Aircraft** damage suggested a higher likelihood of severe injuries. 

### Interactive Dashboard

The interactive dashboard is a collection of views that allows the viewer to change the views to understand different features in the data. Here is a link to view the different interactive dashboards on tableau: https://public.tableau.com/app/profile/daisy.wagati/viz/InteractiveDashboardPhase1Project/Dashboard1?publish=yes


### Conclusions

Based on the comprehensive analysis and exploratory data analysis (EDA) conducted, the following conclusions can be drawn:

1.BOEING is the safest airplane make, with a better safety record compared to other makes, indicating that investing in BOEING aircraft may be a safer choice.

2.The 737 airplane model is the safest, with a higher number of uninjured people, suggesting that this model may be a good investment option.

3.Delta Airlines is the safest air carrier, with a better safety record compared to other carriers, indicating that partnering or acquiring Delta Airlines may be a safer choice.

4.The Turbo Fan engine type stands out as a safer option, suggesting that it may be a more reliable and trustworthy choice for aircraft operations. This finding is significant, as engine type is a critical factor in aircraft safety.

5.The analysis also suggests that Substantial Aircraft damage is associated with a higher likelihood of severe injuries, indicating that aircraft with less damage may be a safer investment option.

### Recommendations

1.The company should consider investing in BOEING aircraft, particularly the 737 model, due to their better safety records.

2.The company should prioritize investing in aircraft with Turbo Fan engines, as they have a better safety record compared to other engine types. This could involve acquiring or partnering with airlines that operate Turbo Fan-powered aircraft, or investing in the development and production of Turbo Fan engines.

3.The company should prioritize investing in aircraft with less damage, as substantial damage is associated with a higher likelihood of severe injuries.






