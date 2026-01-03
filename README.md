# 🏦 Banking-Customer-Churn-Prediction-Using-Machine-Learning

## ABSTRACT

Customer churn has become a critical challenge in the banking sector, as acquiring new customers is significantly more expensive than retaining existing ones. With increasing competition and digital banking services, banks must proactively identify customers who are likely to leave and take preventive actions. Traditional analytical approaches often fail to capture complex customer behavior patterns, making machine learning an effective solution for churn prediction.

This project focuses on developing a machine learning-based system to predict customer churn in the banking sector. Multiple classification models are trained using historical customer data to identify customers who are likely to discontinue banking services. The models are evaluated on unseen data to measure their predictive performance and robustness. A comparative analysis is conducted to determine the most effective model for customer churn prediction.

<br>
<b>Keywords:</b> Customer Churn Prediction, Banking Analytics, Machine Learning, Imbalanced Data, Logistic Regression, Random Forest, XGBoost, LightGBM.

---

## Overview

In today’s competitive banking environment, customer retention plays a vital role in sustaining long-term profitability. Banks collect large volumes of customer data related to demographics, account activity, and financial behavior. Analyzing this data can help institutions understand customer behavior and predict potential churn.

Customer churn refers to the scenario where a customer stops using a bank’s services or closes their account. Churn can occur due to various reasons such as dissatisfaction with services, better offers from competitors, or changes in personal financial needs. Predicting churn in advance enables banks to implement targeted retention strategies and improve customer satisfaction.

This project applies machine learning techniques to analyze customer data and accurately predict churn behavior, helping banks make data-driven decisions to reduce customer attrition.

---

## Project Goals

The primary objective of this project is to build a reliable predictive model that can identify customers who are at high risk of churn. The project emphasizes both predictive accuracy and business relevance.

The key goals include:

- Performing exploratory data analysis to understand customer behavior  
- Identifying important features influencing customer churn  
- Handling class imbalance in churn prediction data  
- Implementing and comparing multiple machine learning models  
- Evaluating models using appropriate classification metrics  
- Selecting the best-performing model for churn prediction  

---

## Data Source

The dataset used in this project contains banking customer information, including demographic details, account activity, and service usage patterns. The dataset is structured and suitable for supervised machine learning classification tasks.

Key features include:
- Customer demographics (age, gender, geography)
- Account information (balance, tenure, credit score)
- Banking product usage (number of products, active membership)
- Target variable indicating churn status  

The target variable is binary:
- **1:** Customer has churned  
- **0:** Customer is retained  

---

## Exploratory Data Analysis (EDA)

Exploratory data analysis was performed to gain insights into customer behavior and churn patterns. Key observations include:

- Customer churn is influenced by factors such as age, balance, and geography  
- Customers with higher balances and inactive membership show higher churn tendencies  
- The dataset exhibits class imbalance, with fewer churned customers compared to retained customers  

Visualizations and statistical analysis were used to support these findings and guide model selection.

---

## Machine Learning Techniques Used

The following machine learning algorithms were implemented and evaluated in this project:

- Logistic Regression  
- Decision Tree-based Random Forest Classifier  
- XGBoost Classifier  
- LightGBM Classifier  

These models were chosen to compare traditional linear approaches with advanced ensemble learning methods capable of capturing complex non-linear relationships in customer data.

---

## Model Evaluation Metrics

To ensure reliable model performance, multiple evaluation metrics were used:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC Score  

Special emphasis was placed on recall and ROC-AUC to effectively identify churned customers in an imbalanced dataset.

---

## Results and Insights

The comparative analysis of models demonstrates that ensemble-based algorithms outperform traditional models in predicting customer churn. Tree-based models such as Random Forest, XGBoost, and LightGBM provide better generalization and capture complex feature interactions.

Among all models, gradient boosting techniques show superior performance in terms of ROC-AUC and recall, making them suitable for real-world churn prediction scenarios.

---

## Future Work

The project can be further enhanced in several ways, including:

- Hyperparameter tuning for improved model performance  
- Applying advanced resampling techniques such as SMOTE  
- Incorporating customer transaction history for deeper insights  
- Deploying the model using Flask or FastAPI for real-time predictions  
- Integrating the model into a business dashboard using Power BI or Streamlit  

---

## Conclusion

This project demonstrates the effectiveness of machine learning techniques in predicting customer churn in the banking sector. By analyzing customer behavior and applying multiple classification models, the study highlights the importance of data-driven decision-making for customer retention. Ensemble models such as Random Forest, XGBoost, and LightGBM show strong predictive performance, making them valuable tools for banks aiming to reduce churn and enhance customer loyalty.

---

## 👤 Author

**Shivam Yadav**  
Aspiring Data Scientist | Machine Learning & Analytics Enthusiast  
