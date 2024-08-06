# Classification Airline Passenger Recommendations
 Data includes airline reviews from 2006 to 2019 for popular airlines around the world with multiple-choice and free-text questions. Data is scraped in Spring 2019. The main objective is to predict whether passengers will refer the airline to their friends.
# Project Summary
The airline industry plays a crucial role in modern transportation, with numerous airlines serving various routes worldwide. To make informed decisions in this highly competitive industry, airlines and stakeholders rely on data-driven insights. Machine learning models are indispensable tools in this regard, allowing for the classification of airlines based on different criteria. This document outlines the development and implementation of an airline classification machine learning model.

This is where machine learning can play a vital role. By using historical customer data, a machine learning model can identify patterns and correlations that indicate a high likelihood of referral. This information can then be used by airlines to target specific customers with personalized marketing campaigns or incentives, increasing the chances of referral and promoting growth.

In conclusion, a machine learning model that predicts the likelihood of referral can provide valuable insights for airlines looking to enhance their customer satisfaction and drive growth through word-of-mouth referrals.
![image](https://github.com/vivekMishra121/-Airline-Passenger-Referral-Prediction/assets/143250429/172fc675-9a58-4c95-811a-882aa5403538)


# Problem Statement
The goal of this machine learning project is to classify airlines into categories based on certain features or attributes. Classification can serve multiple purposes, such as identifying potential partners for codeshare agreements, assisting in pricing strategies, or aiding in market analysis. In this project, We will be exploring if flyers would recommend the airline to their friends and families, based on their travel experience, reviews, and ratings.
### There are a few problems that we are looking at in this project:
* Develop a classification model to categorize airlines based on the likelihood of customers recommending them to friends and family.

* Recognize the pivotal role of customer satisfaction and referrals in the growth and success of airlines.

* Enable airlines to strategically utilize customer referral information for codeshare agreements, pricing strategies, and market analysis.

* Identify customers likely to refer the airline, a task complicated by the diverse factors influencing satisfaction and referrals.

* Assess the model's capability to provide actionable insights for airlines to tailor services, improve customer satisfaction, and enhance brand reputation.
This problem statement outlines the key objectives, challenges, and considerations for developing a classification model to predict customer referrals in the airline industry.

# Objective
The primary objective is to deploy a robust classifier model that accurately predicts user recommendations, empowering airlines to strategize effectively, understand user behavior, optimize services, and align business strategies with financial objectives.

### The steps involved are:-

1. Know Your Data

2. Understanding your Data

3. Data Cleaning

4. Data Manipulation

5. Data Visualization

6. Hypothesis Testing
7. Feature Engineering & Data Pre-processing

8. Data Splitting and ML Model Implementation:-

     a. Decision Tress
   
     b. K-Nearest Neighbour
   
     c. Support Vector Machine
   
     d. Random Forest Classifier
9. Feature Importance
10. Deployment File
    * Pickle
    * Joblib
 # Conclusion
 Our dataset consists of airline reviews spanning from 2006 to 2019, covering various popular airlines worldwide. It comprises 131,895 rows and 17 columns. To enhance data quality, you performed several data preprocessing steps, including converting date columns to datetime format, adjusting rating columns, and addressing issues with the "date_flown" column and tackling our NaN values.

During Exploratory Data Analysis (EDA), you discovered that the majority of customers (72%) opt for the economic class, followed by 19.4% in business class. Ratings predominantly fall within the 1-5 range, except for the "overall_rating," which ranges from 1-10. Insights from the EDA process informed your subsequent hypothesis testing, where t-tests, chi-square, and ANOVA tests were employed to validate assumptions.

Feature engineering involved encoding categorical variables and implementing Principal Component Analysis (PCA) for dimensionality reduction. The decision to retain only the first six principal components, explaining 92% of the data variance, allows for a more streamlined dataset with reduced complexity. Finally, the data was split into a training set (70%) and a testing set (30%) for model development and evaluation.

For the classification problem, four models were employed: `Decision Tree`, `KNN`, `SVM`, and` Random Forest`. Initially, the Decision Tree model exhibited overfitting, but through cross-validation and hyperparameter tuning, this issue was mitigated. Subsequent models, including KNN, SVM, and Random Forest, were then applied.

In terms of classification metrics, the business context prioritized F1_score, followed by Precision and Recall, with accuracy considered third. All four models achieved accuracy rates exceeding 90%, and after evaluation, SVM emerged as the top-performing model by a slight margin.

The evaluation metrics comparison highlighted SVM's superior accuracy, making it the preferred choice among the models tested. Notably, the most influential features contributing to predictions were identified as "Value for money" and "cabin_service."

The developed classifier models are valuable for predicting passenger referrals, allowing airlines to identify impactful passengers who can potentially bring in more revenue. The insights gained from the models suggest that improving cabin service, ground service, food and beverage offerings, entertainment, and seat comfort will enhance the likelihood of passengers recommending the airline to others. This strategic focus on key features can contribute to business growth and increased customer satisfaction.
