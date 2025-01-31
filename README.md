# Life-Insurance-Prediction
Built and deployed a predictive model to automate risk classification in life insurance applications, improving underwriting efficiency. 

# Predictive Modeling for Life Insurance Risk Classification

## Overview
This project focuses on developing a predictive model to automate risk classification in life insurance applications. By leveraging machine learning techniques, the model enhances accuracy and efficiency in assessing applicant risk levels.

## Objectives
- Automate risk classification for life insurance applications.
- Improve risk assessment using predictive modeling.
- Handle high-dimensional data with effective feature selection techniques.
- Address class imbalance and optimize model performance.

## Data Description
The dataset consists of life insurance applicant information, including:
- **Demographics:** Age, height, weight, BMI
- **Employment details:** Work history, job status
- **Insurance history:** Past claims, policy records
- **Family and medical history:** Health-related risk factors
- **Categorical and numerical variables:** Mix of discrete, continuous, and dummy variables

## Data Challenges & Solutions
- **Missing Data:** Handled using imputation and removal techniques.
- **Imbalanced Target Variable:** Applied down-sampling and class weighting.
- **Outliers:** Detected and treated in features like BMI, height, and weight.
- **Categorical Encoding:** Converted categorical variables using encoding techniques.
- **High Dimensionality:** Used PCA to reduce the feature space while retaining significant variance.

## Exploratory Data Analysis (EDA)
- **Risk Categorization:** Classified applicants into High, Average, and Low risk based on BMI, weight, and age.
- **Feature Distributions:** Identified skewed distributions and outliers.
- **Correlation Analysis:** Assessed relationships between key features and risk levels.

## Model Development
### Algorithms Used:
- **Random Forest**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **XGBoost**
- **Voting Classifier (Ensemble Model)**

### Best Model:
- **Voting Classifier (Random Forest + XGBoost + Logistic Regression)**
- **Achieved Accuracy: 54.4%**

## Tools & Technologies Used
- **Programming Language:** Python
- **Libraries:** Scikit-Learn, XGBoost, Pandas, NumPy, Matplotlib, Seaborn

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd your-repo-name
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the model training script:
   ```bash
   python train_model.py
   ```
