# Google-Data-Analytic-Certificate-Capstone-Project
This is my capstone project for my Google Data Analytic Certificate and also my first data analysis project 

## About the project

This project is an analysis of smart device fitness data to help unlock new growth opportunities for **Bellabeat**, a high-tech manufacturer of health-focused products for women. 

In this analysis, I will focus on one of the company's products and analyze smart device data toi gain insight into how consumers are using their smart devices. These insights will later be used to help guide marketing strategy for the company 

### About Bellabeat

Bellabeat is a high-tech company that manufactures health-focused smart products. Using collected data on activity, sleep, stress, and reproductive health has allowed Bellabeat to empower women with
knowledge about their own health and habits. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women.

By 2016, Bellabeat had opened offices around the world and launched multiple products. Bellabeat products became available through a growing number of online retailers in addition to their own e-commerce channel on their website. The company has invested in traditional advertising media, such as radio, out-of-home billboards, print, and television, but focuses on digital marketing extensively. Bellabeat invests year-round in Google Search, maintaining active Facebook and Instagram pages, and consistently engages consumers on Twitter. Additionally, Bellabeat runs video ads on Youtube and display ads on the Google Display Network to support campaigns around key marketing dates.

#### Bellabeat Product: 
- Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress,menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
- Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.
- Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.
- Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.
- Bellabeat membership: Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and
beauty, and mindfulness based on their lifestyle and goals.

## Goal of the Project 
### Key Stakeholders
- Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
- Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
- Bellabeat marketing analytics team: A team of data analysts responsible for collecting, analyzing, and reporting data that helps guide Bellabeat’s marketing strategy
### Business Task
**Business Task**: Analyze trends in smart device usage and identify their potential application for Bellabeat customers. Use these insights to influence Bellabeat's marketing strategy.

**Specific Objectives:**
- **Trend Analysis**: Gather and analyze data on current trends in smart device usage. This may involve collecting data on the types of devices people are using, how frequently they use them, and for what purposes.
- **Customer Application**: Determine how these trends can be applied to Bellabeat's customer base. Understand if Bellabeat's products align with these trends and whether there are opportunities to enhance existing products or develop new ones.
- **Marketing Strategy:** Based on the insights from trend analysis and customer application, provide recommendations for adapting Bellabeat's marketing strategy. This may include identifying target audiences, messaging, and channels to reach potential customers effectively.
- **Competitive Analysis:** Assess how competitors in the smart device industry are responding to these trends. Identify Bellabeat's unique selling points and areas where it can outperform competitors.

## About the Data

**FitBit Fitness Tracker Data** (CC0: Public Domain, dataset made available through Mobius): This Kaggle data set contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habits.
- **Data Organization**: This dataset contains 18 csv files with 15 in narrow format and 3 in wide format. Each document represents different quantitative data trackded by Fibit.
- **Accessibility and privacy of data:** The data is licenced under CC0: Public Domain, with the author relinquishing all of his or her rights to the work under copyright law worldwide, including all related and neighbouring rights, to the extent permissible by law. Without seeking permission, the work may be copied, modified, distributed, and performed for commercial reasons.
- **Credibility and Integrity of data**: The dataset still have some noticeable limitations such as the low sample size (30 users) and also the timeframe is short and not current, also this a third-party data therefore it's very hard to validate the data with its original sources.

## Process the Data
In this project, I will use BigQuery as a tool to process and analyze the data.

### **Choosing data**: 

**_Include_**: 

_dailyActivity_merged.csv_

_dailyCalories_merged.csv_

_dailyIntensities_merged.csv_

_dailySteps_merged.csv_

_heartrate_seconds_merged.csv_

_hourlyCalories_merged.csv_

_hourlyIntensities_merged.csv_

_hourlySteps_merged.csv_

_minuteCaloriesNarrow_merged.csv_

_minuteIntensitiesNarrow_merged.csv_

_minuteMETsNarrow_merged.csv_

_minuteSleep_merged.csv_

_minuteStepsNarrow_merged.csv_

_sleepDay_merged.csv_

_weightLogInfo_merged.csv_

**_Exclude_**: 

_minuteCaloriesWide_merged.csv_

_minuteIntensitiesWide_merged.csv_

_minuteStepsWide_merged.csv_

The reason I choose to exclude these 3 files is due to the fact that they are in wide format and they have the same data with their long format versions 

### **Upload data to BigQuerry**:

Fisrt in BigQuery, I create a new dataset called **fibit_tracker** in my personal project and start to upload 15 csv files that I have chosen before 

![image](https://github.com/dunghoyyy/Google-Data-Analytic-Certificate-Capstone-Project/assets/132896605/5e9a0406-9e96-42ed-837c-9c913caf14bd)



