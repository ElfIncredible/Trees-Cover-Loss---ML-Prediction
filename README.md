# Trees Cover Loss - ML Prediction

## Table Of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Collection and Pre-processing](#data-collection-and-pre-processing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning](#machine-learning)
  - [Separate Features and Targets](#separate-features-and-targets)

## Project Overview

## Dataset

## Data Collection and Pre-processing
- Perform initial data loading, cleaning, and exploration tasks on national and subnational tree cover loss data in Kenya. 
- Rename columns for clarity, remove unnecessary columns, and check the distribution of key variables like threshold.
  The cleaned data can now be used for further analysis or modeling.

## Exploratory Data Analysis
**1. Trend Analysis of Tree Cover Loss:**

- Plot the trend of tree cover loss from 2001 to 2023 across different regions and canopy cover thresholds.
- Highlight the significant reduction in tree cover loss in 2020-2022, likely due to a logging ban, followed by a spike in 2023 after the ban was lifted.
  ![image](https://github.com/user-attachments/assets/69af4fd5-a2d1-4944-9bcd-684c8e2854f7)

**2.Threshold Distribution Comparison:**

- Create pie charts comparing the distribution of canopy cover thresholds between the years 2001 and 2023.
- We find an overall increase in tree cover loss across all thresholds over the last 13 years.
  ![image](https://github.com/user-attachments/assets/a3cd2489-e8a3-4c9c-9bc5-368511236857)

**3. Regional Trend Analysis for Specific Thresholds:**

- Plot the trend of tree cover loss for specific regions (Meru, Kericho, Kiambu) at selected canopy cover thresholds (75%, 25%, 50%).
- Illustrate how tree cover loss varies in these regions over the years.
  ![image](https://github.com/user-attachments/assets/2a92a0ac-3380-43c1-b5d0-ab02bba08b99)

  ![image](https://github.com/user-attachments/assets/13754df0-4286-4e32-a234-47025ef8d398)

  ![image](https://github.com/user-attachments/assets/005a2b38-3949-4961-926e-82637fd1f44c)


**4. Comparison of Tree Cover Loss in Nakuru and Kiambu:**

- Compare the tree cover loss between Nakuru and Kiambu over the last 10 years for a 20% canopy cover threshold.
- We find that Nakuru has seen greater tree cover loss than Kiambu, though the loss has decreased significantly in the last 5 years.
  ![image](https://github.com/user-attachments/assets/e47cda32-8b1a-47dc-baee-f94160e03a4b)


**5. Top 10 Regions in Tree Cover Loss:**

- Identify and plot the top 10 regions with the highest tree cover loss over the last 10 years for a 20% canopy cover threshold.
- Narok emerges as the most impacted region, likely due to logging or conversion of forested land to agriculture.
  ![image](https://github.com/user-attachments/assets/a707b6b1-29f1-480e-b0f9-d78e1b7bf810)


**6. Regions with Greatest Tree Cover Loss Reduction:**

- Highlight the top 10 regions that have seen the greatest reduction in tree cover loss over the last 10 years.
- Coastal regions like Kilifi, Kwale, and Lamu show significant reductions due to mangrove rehabilitation, farm forestry, and community efforts.
  ![image](https://github.com/user-attachments/assets/e293747a-7bdc-44c6-90c1-19afb037444e)


Overall, we get a comprehensive analysis of tree cover loss trends across different regions and canopy cover thresholds in Kenya, with a focus on understanding the factors contributing to changes in forest cover over time.

## Machine Learning
### Separate Features and Targets
