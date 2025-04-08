# Telecom_Churn_Analysis
## Project Overview
This project analyzes customer churn in a telecommunications company to identify at-risk customers, understand churn drivers, and quantify the economic impact of customer attrition. The analysis combines exploratory data analysis, machine learning, and financial modeling to create actionable business insights.
## Dataset
The analysis uses the Iranian Churn Dataset, which contains customer data from a telecom provider, including:
- Customer demographics
- Contract information
- Call behavior metrics
- Charge amounts
- Churn status (target variable)
Citation: Jafari-Marandi, R., Denton, J., Idris, A., Smith, B. K., & Keramati, A. (2020). Optimum Profit-Driven Churn Decision Making: Innovative Artificial Neural Networks in Telecom Industry. Neural Computing and Applications.
## Key Objectives:
- Identify factors that significantly influence customer churn
- Segment customers based on behavior and churn risk
- Develop predictive models to identify customers likely to churn
- Quantify financial impact of churn and potential ROI of retention efforts

## Technical Approach
The analysis follows a structured methodology:
1. Exploratory Data Analysis
- Distribution analysis of numerical features
- Correlation analysis with significance testing
- Temporal patterns in customer behavior
2. Feature Engineering & Customer Segmentation
- Principal Component Analysis (PCA) for dimensionality reduction
- K-means clustering for customer segmentation
- Time-based cohort analysis
3. Predictive Modeling
- Multiple model comparison (Logistic Regression, Random Forest, Gradient Boosting)
- Feature importance analysis
- Customer risk scoring framework
4. Economic Impact Analysis
- Quantification of revenue loss due to churn
- ROI calculation for retention initiatives
- Scenario modeling for various intervention strategies

## Key Findings
Customer Behavior Insights:
- Churn risk declines sharply after customers pass the 12-month mark
- Month-to-month contract customers show 3-5x higher churn rates than those on longer contracts
- Distinct customer segments exhibit dramatically different churn propensities

Predictive Capability:
- The best model accurately identifies ~80% of potential churners before they leave
- Feature importance analysis revealed the top predictors of churn
- 15-20% of customers fall into high or very high-risk categories

Financial Impact:
- Calculated annual revenue loss due to customer churn
- Even modest improvements in retention (10-20%) would save significant revenue
- Retention campaigns focused on high-risk customers can achieve 200-300% ROI with a 30% success rate

Business Recommendation:
- Implement special onboarding and milestone-based loyalty programs for customers in their first 12 months
- Develop segment-specific retention strategies based on the identified customer clusters
- Establish tiered retention protocols based on risk level
- Allocate retention budget proportional to customer value and churn probability

## Installation & Usage
Requirements
- Python 3.7+
- Key libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Data source: Kaggle
Dataset description: UCI Machine Learning Repository
