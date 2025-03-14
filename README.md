# Customer Churn Analysis

## Overview
This project analyzes customer churn using the **Customer Churn Analysis** dataset from Kaggle. The objective is to understand the factors influencing customer churn and develop predictive models to mitigate customer attrition.

## Dataset Description
The dataset contains customer-related information such as demographics, subscription details, usage patterns, and service feedback. The key features help in understanding the reasons for customer churn and building predictive models.

### Key Features:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **SeniorCitizen**: Indicates if the customer is a senior citizen (0 - No, 1 - Yes).
- **Partner**: Whether the customer has a partner (Yes/No).
- **Dependents**: Whether the customer has dependents (Yes/No).
- **Tenure**: Number of months the customer has stayed with the company.
- **PhoneService**: Whether the customer has phone service (Yes/No).
- **MultipleLines**: Whether the customer has multiple lines (Yes/No).
- **InternetService**: Type of internet service (DSL, Fiber Optic, No).
- **OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies**: Subscription to additional services (Yes/No).
- **Contract**: Type of contract (Month-to-month, One year, Two year).
- **PaperlessBilling**: Whether the customer has opted for paperless billing (Yes/No).
- **PaymentMethod**: Method of payment (Electronic check, Mailed check, Bank transfer, Credit card).
- **MonthlyCharges**: Monthly charges incurred by the customer.
- **TotalCharges**: Total amount charged to the customer.
- **Churn**: Target variable indicating if the customer has churned (Yes/No).

## Objective
- **Descriptive Analysis**: Identify trends and characteristics of churned customers.
- **Predictive Modeling**: Develop machine learning models to predict customer churn.
- **Prescriptive Analysis**: Provide recommendations to minimize churn.

## Methodology
1. **Data Cleaning & Preprocessing**:
   - Handle missing values and incorrect data types.
   - Encode categorical variables.
   - Normalize numerical variables.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize customer demographics and behavior.
   - Identify correlations between features and churn.
   - Analyze customer tenure, charges, and service subscriptions.

3. **Model Development**:
   - Use classification models like Logistic Regression, Decision Trees, Random Forest, XGBoost, and Neural Networks.
   - Evaluate model performance using accuracy, precision, recall, and F1-score.

4. **Insights & Recommendations**:
   - Identify key factors influencing churn.
   - Suggest business strategies to improve customer retention.

## Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Expected Outcomes
- A comprehensive analysis of churn patterns.
- A predictive model that can classify customers at risk of churning.
- Business insights to improve customer retention strategies.

## How to Use
1. Download the dataset from Kaggle.
2. Load the dataset in Python using Pandas.
3. Perform data preprocessing and EDA.
4. Train and evaluate predictive models.
5. Generate insights and recommendations for reducing churn.

## References
- Kaggle Dataset: [Customer Churn Analysis](https://www.kaggle.com)
- Related research papers and industry articles on churn prediction.

## Author
Aryaman Pillay
