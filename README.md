# 📊 Bank Marketing Analysis & Customer Subscription Prediction

### Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn

##  Project Overview

This project focuses on analyzing bank marketing campaign data to understand customer behavior and identify factors influencing term deposit subscriptions.

Using Python and machine learning techniques, I performed data cleaning, exploratory data analysis (EDA), visualization, and classification model evaluation to gain insights into customer subscription patterns.

The project helped me strengthen my practical skills in data analysis, data visualization, and machine learning.

## Project Screenshots
### 1. Exploratory Data Analysis

<img width="627" height="506" alt="EDA_Chart" src="https://github.com/user-attachments/assets/56abab61-aab4-4123-a5e4-d23b637920ea" />

### 2. Correlation Heatmap

<img width="897" height="790" alt="Correlation_Heatmap" src="https://github.com/user-attachments/assets/38f55dd5-f865-415e-867d-ffa6b9a2e9a3" />

### 3. Model Evaluation

<img width="462" height="291" alt="Model_results" src="https://github.com/user-attachments/assets/35b1a25c-d409-4dd6-b783-337d81423bba" />

##  Objectives

- Analyze customer data to understand subscription patterns.
- Identify important factors influencing customer decisions.
- Perform data cleaning and exploratory data analysis.
- Visualize relationships between different features.
- Build and evaluate a Logistic Regression classification model.
- Understand the impact of class imbalance on model performance.

##  Tools & Technologies

- **Python** – Data analysis and model development
- **Pandas & NumPy** – Data manipulation and preprocessing
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning and model evaluation
- **Google Colab** – Development environment

##  Dataset

The project uses a Bank Marketing dataset containing approximately **41,000+ customer records**.

The dataset includes customer demographics, financial information, campaign details, and subscription outcomes.

**Target Variable:**
- `0` – Customer did not subscribe
- `1` – Customer subscribed

##  Project Workflow

1. **Data Loading** – Imported the dataset and explored its structure.
2. **Data Cleaning** – Checked data quality and prepared the dataset for analysis.
3. **Exploratory Data Analysis (EDA)** – Analyzed numerical and categorical variables.
4. **Data Visualization** – Created charts and a correlation heatmap to explore patterns.
5. **Data Preprocessing** – Prepared features and target variable for modeling.
6. **Train-Test Split** – Split the dataset into training and testing sets.
7. **Feature Scaling** – Applied StandardScaler to numerical feature values.
8. **Model Building** – Implemented Logistic Regression.
9. **Model Evaluation** – Evaluated performance using accuracy, confusion matrix, precision, recall, and F1-score.
10. **Class Imbalance Handling** – Compared the original model with a class-weighted model.

##  Key Insights

- The dataset contains an imbalance between customers who subscribed and those who did not.
- Exploratory data analysis helped identify patterns in customer and campaign-related features.
- The original Logistic Regression model achieved approximately **90.93% accuracy**.
- Applying class weighting improved the model's ability to identify customers who subscribed.
- The balanced model achieved approximately **91% recall for the subscription class**, with lower overall accuracy.

These results demonstrate why model evaluation should consider multiple metrics rather than accuracy alone.

##  What I Learned

- Practical data cleaning and preprocessing using Pandas.
- Performing EDA and identifying patterns in customer data.
- Creating meaningful visualizations using Matplotlib and Seaborn.
- Preparing data for machine learning.
- Building and evaluating classification models using Scikit-learn.
- Understanding class imbalance and the trade-off between accuracy and recall.

##  Future Improvements

- Explore additional classification algorithms.
- Perform feature importance analysis.
- Tune model parameters to improve performance.
- Compare models using ROC-AUC and other evaluation metrics.
- Develop an interactive dashboard to present key findings.

##  Project Files

- `Bank_Marketing_Analysis.ipynb` – Project notebook containing analysis and model implementation.
- `bankmarketing.csv` – Dataset used for analysis.

##  Author

**Prerna Kishore**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

