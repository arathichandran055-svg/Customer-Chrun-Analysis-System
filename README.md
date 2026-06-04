Introduction

Customer churn analysis helps businesses understand why customers leave their services. This project uses synthetic data to analyze customer behavior and identify churn patterns.

Problem Statement

Customer churn leads to revenue loss and increased customer acquisition cost. Manual analysis of large customer data is time-consuming and inefficient.

Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on customer data. It aims to identify patterns, trends, and key factors influencing customer churn.

Dataset Overview

This project uses a synthetically generated dataset of 1,00,000 customers. The dataset simulates real-world banking or telecom customer data.

Dataset Features (Columns Used)

Customer_ID – Unique ID for each customer

Age – Customer age (18–70)

Gender – Male / Female

Tenure – Years with company (0–10)

Balance – Account balance

CreditScore – Credit score (300–900)

EstimatedSalary – Annual income

NumOfProducts – Number of products used

IsActiveMember – Active status (Yes/No)

Churn – Target variable (0 = No, 1 = Yes)

Tools & Technologies

Python Google Colab Pandas NumPy Matplotlib Seaborn Faker (for data generation)

Methodology

Data Generation
Synthetic customer data is generated using Faker and NumPy. It simulates real-world customer attributes and behavior.

Data Preprocessing
Missing values are checked and data types are verified. Categorical data is converted into numerical format.

Exploratory Data Analysis (EDA)
Statistical measures like mean, median, and standard deviation are calculated. Data is analyzed to understand distribution and trends.

Churn Analysis
Customers are divided into churn and non-churn groups. Patterns and differences between these groups are studied.

Group-Based Analysis
Churn is analyzed based on age, gender, activity, and product usage. This helps identify high-risk customer segments.

Relationship Analysis
Relationships between variables like balance, salary, and credit score are analyzed. Correlation is used to understand feature impact on churn.

Data Visualization
Various charts are used:

Bar charts Pie charts Histograms Scatter plots Box plots Heatmaps

Key Insights

Inactive customers are more likely to churn. Customers with low balance tend to leave more frequently. Product usage and tenure also influence churn behavior.

Conclusion

Customer churn can be reduced by identifying key patterns and behaviors. Businesses can take preventive actions based on data insights to retain customers.

                                                    OUTPUT
<img width="679" height="488" alt="image" src="https://github.com/user-attachments/assets/3938ef93-afe9-4cca-a17c-624504ca59db" />
<img width="641" height="488" alt="image" src="https://github.com/user-attachments/assets/43931664-5bca-4f5a-b697-b3bce8d878b0" />
<img width="766" height="532" alt="image" src="https://github.com/user-attachments/assets/5af6db3e-fd35-40e5-803b-f7c78f8044f9" />
<img width="704" height="492" alt="image" src="https://github.com/user-attachments/assets/ea5a96ca-c175-42cb-b29b-c6fbac58c944" />
<img width="652" height="478" alt="image" src="https://github.com/user-attachments/assets/efd11a98-aecd-4e0a-ac0c-12609686d646" />


