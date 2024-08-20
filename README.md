# Trees Cover Loss in Kenya - Machine Learning Prediction
This project demonstrates the potential of machine learning to forecast environmental changes, offering valuable insights for planning and conservation efforts.


## Table Of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Data Collection and Pre-processing](#data-collection-and-pre-processing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings and Possible Conservation Efforts](#findings-and-possible-conservation-efforts)
- [Machine Learning](#machine-learning)
  - [Separate Features and Targets](#separate-features-and-targets)
  - [Splitting data into Train and Test data](#splitting-data-into-train-and-test-data)
  - [Model Training - Linear Regression](#model-training---linear-regression)
  - [Make Predictions](#make-predictions)
  - [Model Evaluation - Mean Squared Error](#model-evaluation---mean-squared-error)
  - [Making Predictions](#making-predictions)

## Project Overview
This project aims to predict tree cover loss for subnational regions over the next two years (2024 and 2025) using historical data spanning from 2001 to 2023. The predictions are made using a Linear Regression model trained on this historical data, allowing for the estimation of future tree cover loss based on observed trends.

**Key Objectives:**
- Accurate Prediction: Provide reliable predictions for tree cover loss to help stakeholders anticipate and respond to environmental changes.
- Data Integration: Seamlessly integrate predictive insights into existing datasets for comprehensive analysis.
- Accessibility: Ensure that the results are easily accessible and interpretable by saving the predictions in user-friendly formats (Excel, CSV).

## Dataset
The [dataset](https://www.globalforestwatch.org/dashboards/country/KEN/?category=forest-change&location=WyJjb3VudHJ5IiwiS0VOIl0%3D) used in this project provides a comprehensive overview of tree cover loss across various subnational regions in Kenya from 2001 to 2023. It includes detailed annual data on the extent of tree cover loss, which serves as the basis for analyzing trends and predicting future changes in forest cover.

## Data Collection and Pre-processing
- Perform initial data loading, cleaning, and exploration tasks on national and subnational tree cover loss data in Kenya. 
- Rename columns for clarity, remove unnecessary columns, and check the distribution of key variables like threshold.
  The cleaned data can now be used for further analysis or modeling.

## Exploratory Data Analysis
**1. Trend Analysis of Tree Cover Loss**

- Plot the trend of tree cover loss from 2001 to 2023 across different regions and canopy cover thresholds.
- Highlight the significant reduction in tree cover loss in 2020-2022, likely due to a logging ban, followed by a spike in 2023 after the ban was lifted.
  ![image](https://github.com/user-attachments/assets/69af4fd5-a2d1-4944-9bcd-684c8e2854f7)

**2.Threshold Distribution Comparison**

- Create pie charts comparing the distribution of canopy cover thresholds between the years 2001 and 2023.
- We find an overall increase in tree cover loss across all thresholds over the last 13 years.
  ![image](https://github.com/user-attachments/assets/a3cd2489-e8a3-4c9c-9bc5-368511236857)

**3. Regional Trend Analysis for Specific Thresholds**

- Plot the trend of tree cover loss for specific regions (Meru, Kericho, Kiambu) at selected canopy cover thresholds (75%, 25%, 50%).
- Illustrate how tree cover loss varies in these regions over the years.
  ![image](https://github.com/user-attachments/assets/2a92a0ac-3380-43c1-b5d0-ab02bba08b99)

  ![image](https://github.com/user-attachments/assets/13754df0-4286-4e32-a234-47025ef8d398)

  ![image](https://github.com/user-attachments/assets/005a2b38-3949-4961-926e-82637fd1f44c)


**4. Comparison of Tree Cover Loss in Nakuru and Kiambu**

- Compare the tree cover loss between Nakuru and Kiambu over the last 10 years for a 20% canopy cover threshold.
- We find that Nakuru has seen greater tree cover loss than Kiambu, though the loss has decreased significantly in the last 5 years.
  ![image](https://github.com/user-attachments/assets/e47cda32-8b1a-47dc-baee-f94160e03a4b)


**5. Top 10 Regions in Tree Cover Loss**

- Identify and plot the top 10 regions with the highest tree cover loss over the last 10 years for a 20% canopy cover threshold.
- Narok emerges as the most impacted region, likely due to logging or conversion of forested land to agriculture.
  ![image](https://github.com/user-attachments/assets/a707b6b1-29f1-480e-b0f9-d78e1b7bf810)


**6. Regions with Greatest Tree Cover Loss Reduction**

- Highlight the top 10 regions that have seen the greatest reduction in tree cover loss over the last 10 years.
- Coastal regions like Kilifi, Kwale, and Lamu show significant reductions due to mangrove rehabilitation, farm forestry, and community efforts.
  ![image](https://github.com/user-attachments/assets/e293747a-7bdc-44c6-90c1-19afb037444e)


Overall, we get a comprehensive analysis of tree cover loss trends across different regions and canopy cover thresholds in Kenya, with a focus on understanding the factors contributing to changes in forest cover over time.

## Findings and Possible Conservation Efforts
### Findings:
**1. Significant Trends in Tree Cover Loss:**
- Analysis of the data revealed that tree cover loss has fluctuated over the years, with notable reductions in certain regions during specific periods. For instance, a marked decrease in tree cover loss was observed across Kenya from 2020 to 2022, likely influenced by the national logging ban.
- However, a concerning spike in tree cover loss was predicted for 2023, potentially linked to the lifting of the logging ban, indicating a possible resurgence of deforestation activities.

**2. Regional Variations:**
- The data analysis highlighted that different regions within Kenya have experienced varying degrees of tree cover loss. Regions like Nakuru and Kiambu have shown distinct trends, with Nakuru experiencing greater loss in recent years, while Kiambu demonstrated a more significant reduction, particularly in the last five years.
- Coastal regions such as Kilifi, Kwale, and Lamu were identified as having the greatest reduction in tree cover loss, possibly due to concerted efforts in mangrove rehabilitation, farm forestry, and capacity building.

**3. Prediction Insights:**
- The predictions for 2024 and 2025 indicate that certain regions may continue to experience high levels of tree cover loss unless intervention measures are put in place. Narok, for instance, is forecasted to face severe deforestation, which may be driven by factors such as logging, agricultural expansion, or other land-use changes.

### Possible Conservation Efforts:
**1. Strengthening Logging Regulations:**
- To mitigate the predicted increase in tree cover loss, Kenya could consider re-implementing or tightening logging regulations. A balanced approach that allows sustainable logging while protecting vital forested areas could prevent further deforestation.

**2. Community-Based Forest Management:**
- Encouraging community involvement in forest management, especially in regions like Narok and Nakuru, could help reduce deforestation rates. Programs that promote sustainable agriculture, agroforestry, and reforestation could empower local communities to protect their natural resources.

**3. Mangrove and Coastal Forest Conservation:**
- The success observed in coastal regions through mangrove rehabilitation and farm forestry efforts should be expanded and replicated in other vulnerable areas. These efforts not only reduce tree cover loss but also enhance biodiversity, support fisheries, and protect against coastal erosion.

**4. Reforestation and Afforestation Initiatives:**
- Large-scale reforestation and afforestation projects could be key to reversing tree cover loss trends. By planting trees in deforested and degraded areas, regions like Narok and Nakuru could see long-term ecological recovery.
  
**5. Policy Development and Enforcement:**
- Developing and enforcing environmental policies that prioritize forest conservation is crucial. This could include incentives for private landowners to maintain forest cover, penalties for illegal logging, and the creation of protected areas where deforestation is strictly controlled.

**6. Public Awareness and Education:**
- Raising awareness about the importance of forests and the impact of deforestation can mobilize public support for conservation efforts. Educational campaigns could target schools, communities, and industries to promote sustainable practices.

**7. International Collaboration:**
- Kenya could benefit from international partnerships focused on forest conservation, including funding for conservation projects, technical assistance, and knowledge sharing. Collaborating with global organizations could also help address transboundary deforestation issues.

By implementing these conservation efforts, Kenya can work towards reducing tree cover loss, protecting its rich biodiversity, and ensuring sustainable land use for future generations.

## Machine Learning
### Separate Features and Targets
Set up a supervised learning scenario where the model will be trained to predict the next year's tree cover loss using the data from the current year.

### Splitting data into Train and Test data
- Split the data into training and testing sets with an 80-20 ratio.
- This splitting is essential for evaluating the performance of machine learning models, as it allows you to train the model on one subset of the data and test it on a separate subset.

### Model Training - Linear Regression
Build and train a linear regression model to understand and predict tree cover loss trends over time using historical data.

### Make Predictions
Generate predictions of tree cover loss for the next year based on the test dataset, enabling you to evaluate the model's performance and accuracy.

### Model Evaluation - Mean Squared Error
Assess the accuracy and effectiveness of the linear regression model in predicting tree cover loss for the test data and print the result.

### Making Predictions
- Generate predictions for tree cover loss in 2024 and 2025 for different subnational regions based on historical data
- Integrate those predictions into the existing dataset
- Save the updated dataset to files for further analysis or reporting.
  ![image](https://github.com/user-attachments/assets/fe609821-e4df-4fa5-8b61-1532eef6e4e6)
