# Lead Scoring Case Study

## Overview

This repository contains the materials for the **Lead Scoring Case Study**, an academic project aimed at helping an education company, **X Education**, improve its lead conversion process. The project involves building a logistic regression model to assign a lead score to potential leads, thereby increasing the efficiency of the sales team by focusing on the most promising leads.

The project is structured around the following deliverables:
- A logistic regression model that predicts the probability of lead conversion.
- A thorough analysis of the dataset using various statistical and machine learning techniques.
- Business insights and recommendations based on the model outcomes.

## Problem Statement

**X Education** offers online courses to industry professionals. The company markets its courses via several online platforms and acquires leads when potential customers submit forms on the website. However, the lead conversion rate is quite low, with only 30% of leads converting into paying customers. The goal of this project is to develop a model that helps the company identify high-potential leads, known as "Hot Leads," to improve the conversion rate to the CEO's target of 80%.

![image](https://github.com/user-attachments/assets/052c33c5-6bb1-46d8-ba1b-ae839d15e66d)


## Project Goals

1. **Logistic Regression Model**: 
   - Build a logistic regression model that assigns a lead score between 0 and 100 to each lead, where higher scores indicate a higher likelihood of conversion.

2. **Data-Driven Insights**:
   - Analyze the dataset to determine key factors that influence lead conversion.
   - Provide actionable insights to the sales team, helping them prioritize leads and improve conversion rates.

3. **Academic Focus**:
   - This case study emphasizes both technical and business analysis, making it an ideal academic project for data science students. The project combines statistical analysis, machine learning, and business strategy to derive meaningful conclusions.

## Dataset Description

The dataset provided contains around **9000 leads** with various attributes such as:
- **Lead Source**: Where the lead originated from (Google, referral, etc.).
- **Total Time Spent on Website**: Time spent by the lead on the company's website.
- **Total Visits**: Number of visits made by the lead.
- **Last Activity**: The most recent activity performed by the lead.
- **Converted**: The target variable indicating whether the lead was converted (1) or not (0).

**Special Handling**: Categorical variables like 'Lead Source' contain values such as 'Select', which are treated as missing data and appropriately handled during preprocessing.

## Files in the Repository

1. **Lead_Scoring_Logistic_Regression_Assignment.ipynb**:
   - This Jupyter Notebook contains the complete code for data preprocessing, exploratory data analysis (EDA), logistic regression model building, prediction, and evaluation. 
   - It is well-commented to ensure clarity and understanding of each step, with detailed descriptions of the applied techniques.

2. **Leads.csv**:
   - This is the dataset provided for the case study, containing various features relevant to lead conversion.

3. **Lead Scoring Case Study PPT.pdf**:
   - A presentation outlining the problem, methodology, and results of the case study.
   - It covers both technical and business aspects, including key visualizations and insights for the company’s decision-makers.

4. **Lead Scoring Case Study_ Q&A_KP_MS_SJ.pdf**:
   - A document answering the company-specific questions provided in the case study. This includes detailed explanations of how the logistic regression model adapts to future business needs and evaluates the model's performance.

5. **Summary Report of Lead Scoring Case Study.pdf**:
   - A 500-word summary report detailing the approach, methodology, and learnings from the project. The report is structured to explain the process followed in building the model and the key takeaways for improving lead conversion.

6. **README.md**:
   - This file provides an overview of the repository, the problem statement, the dataset, and the contents of the repository.

## Project Workflow

1. **Data Preprocessing**:
   - Handle missing values and categorical data.
   - Remove or impute 'Select' values in categorical features.
   - Normalize and scale numerical variables where necessary.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize and analyze key trends in the data.
   - Determine correlations between features and the target variable (Converted).

3. **Model Building**:
   - Implement a logistic regression model to predict lead conversion.
   - Perform hyperparameter tuning and regularization to improve model performance.
   - Assign a lead score to each lead based on the model's output probabilities.

4. **Model Evaluation**:
   - Use standard evaluation metrics such as **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC** to assess model performance.
   - Generate a **confusion matrix** and **ROC curve** to visualize the model’s ability to distinguish between converted and non-converted leads.

5. **Business Insights & Recommendations**:
   - Identify the most influential factors driving lead conversion.
   - Provide actionable recommendations for the sales team to focus on "Hot Leads" and improve conversion rates.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/ManjitSingh2003/Lead-Scoring.git
   ```

2. Open the Jupyter Notebook and run the steps outlined in `Lead_Scoring_Logistic_Regression_Assignment.ipynb` to preprocess the data, build the model, and evaluate the results.

3. Review the analysis and findings in the presentation (`Lead Scoring Case Study PPT.pdf`) and Q&A document (`Lead Scoring Case Study_ Q&A_KP_MS_SJ.pdf`).

4. Read the **Summary Report of Lead Scoring Case Study.pdf** to gain insights into the overall approach and key learnings.

## Key Learnings

This case study provides valuable insights into the following areas:
- **Data Preprocessing**: Handling missing values, encoding categorical variables, and normalizing data.
- **Exploratory Data Analysis (EDA)**: Identifying key variables influencing lead conversion.
- **Modeling and Evaluation**: Using logistic regression for classification tasks and evaluating model performance with standard metrics.
- **Business Strategy**: Translating data science results into actionable business insights to improve lead conversion rates.
