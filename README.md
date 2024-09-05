# Healthcare Cost Factors and Prediction Using R

### **By Achala Rao**

## **Project Overview**

This project focuses on **analyzing key healthcare cost factors** and **predicting high-cost clients** for an HMO (Health Management Organization) using **advanced data science techniques in R**. The dataset contains extensive healthcare cost information, with each row representing an individual client. The aim is to deliver actionable insights for the HMO, helping them optimize healthcare costs and better manage resources.

## **Project Objectives**

1. **Predictive Modeling**: Build a robust machine learning model to predict which clients will incur high healthcare costs in the coming year.
   
2. **Data-Driven Insights**: Use advanced statistical and machine learning techniques to uncover the key factors that contribute to high healthcare costs.
   
3. **Cost Optimization**: Provide the HMO with specific, data-driven recommendations to help reduce overall healthcare costs by understanding and managing the key cost drivers.

## **Technologies Used**

- **R**: For data manipulation, statistical analysis, and machine learning.
- **Tidyverse**: For data wrangling and visualization.
- **ggplot2**: For generating high-quality visualizations.
- **caret**: For training and validating machine learning models.
- **imputeTS**: For handling missing data through advanced interpolation methods.
- **arules** and **arulesViz**: For association rule mining, uncovering relationships between various factors and healthcare costs.

## **Key Features**

- **Exploratory Data Analysis (EDA)**: Comprehensive data exploration, including histograms, scatter plots, and box plots to visualize relationships between healthcare costs and client attributes such as age, BMI, smoking status, and exercise habits.
  
- **Missing Data Imputation**: Utilized advanced imputation techniques to handle missing values in key attributes like BMI, ensuring data quality for the predictive models.

- **Data Segmentation**: Grouped clients by age and BMI to gain insights into how different demographics and health factors affect healthcare costs.

- **Cost Categorization**: Implemented a threshold-based system to classify clients as "Expensive" or "Not Expensive" based on their healthcare spending, leveraging the 75th percentile of the cost distribution.

- **Association Rule Mining**: Applied advanced **association rule mining** techniques to identify patterns in healthcare costs, such as the influence of smoking and exercise on cost.

## **Advanced Predictive Modeling**

- **Support Vector Machine (SVM)**: Built a powerful SVM model to predict whether a client would be classified as "Expensive" or "Not Expensive" in the future. This model was tuned using cross-validation and achieved high accuracy.

- **Decision Tree Model**: Created a decision tree using the **rpart** package, providing an interpretable model that outlines the key factors contributing to high healthcare costs.

- **Model Evaluation**: The models were rigorously tested using **confusion matrices** to evaluate their predictive accuracy and optimize their performance.

## **Key Insights**

- **Positive Correlation between Age/BMI and Costs**: Older clients and those with higher BMIs were found to have significantly higher healthcare costs, especially when combined with smoking or a sedentary lifestyle.

- **Geographical Cost Variations**: State-level analysis showed significant differences in healthcare costs across regions, with New York having the highest average cost per client.

- **Behavioral Patterns**: Smoking and inactivity were the two most significant factors associated with high healthcare costs, as identified through association rule mining.

## **Visualizations**

- **Age vs. Healthcare Costs**: Plotted the correlation between age and healthcare costs, highlighting the impact of smoking and exercise.
  
- **BMI vs. Healthcare Costs**: Demonstrated the strong positive correlation between BMI and healthcare costs, especially for smokers.

- **Geographical Heatmaps**: Visualized average healthcare costs across different states, identifying key cost-intensive regions.

## **Future Enhancements**

- **Deep Learning**: Plan to integrate deep learning models to further improve the predictive accuracy and uncover more complex patterns in healthcare costs.
  
- **Time Series Forecasting**: Introduce time series analysis to predict how healthcare costs evolve over multiple years, accounting for temporal factors.
