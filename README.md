# Customer Churn Analysis and Prediction Using Machine Learning

**Author:** Vinay Sancheti  
**Program:** B.Tech Computer Science and Engineering  
**Institution:** Pimpri Chinchwad University, Pune  
**Internship:** IBM SkillsBuild Data Analytics with AI Academic Internship Program

## 1. Project Overview

This project analyzes customer churn in a telecommunications dataset and develops machine-learning classification models to identify customers who are more likely to churn.

The project follows an end-to-end data analytics workflow:

1. Data collection
2. Data understanding
3. Data cleaning
4. Exploratory Data Analysis (EDA)
5. Data preprocessing and encoding
6. Model training
7. Model evaluation
8. Interpretation of important factors
9. Business-oriented insights

## 2. Problem Statement

Customer churn is an important business problem for telecommunications companies. The objective of this project is to analyze customer characteristics and service information, identify patterns associated with churn, and build a machine-learning model that can classify whether a customer is likely to churn.

## 3. Objectives

- Understand the structure and quality of the customer dataset.
- Clean missing and inconsistent values.
- Explore demographic, service, contract, and billing patterns.
- Identify customer segments associated with higher churn.
- Train classification models for churn prediction.
- Compare model performance using standard classification metrics.
- Interpret the factors that contribute to churn.
- Provide data-driven insights that can support customer-retention analysis.

## 4. Dataset

The project uses the **IBM Telco Customer Churn sample dataset**.

- Approximate records: **7,043 customers**
- Variables: **21 columns**
- Target variable: `Churn`
- Target classes: `Yes` and `No`

### Dataset source

IBM's archived sample repository:

https://github.com/IBM/telco-customer-churn-on-icp4d/blob/master/data/Telco-Customer-Churn.csv

Raw CSV used by the notebook:

https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv

> The dataset represents a fictional telecommunications customer population and is intended as sample/educational data.

## 5. Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 6. Machine Learning Models

The notebook trains and evaluates:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

## 7. Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Preparation
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Feature Interpretation
   ↓
Insights & Conclusion
```

## 8. Setup Instructions

### Step 1: Install Python

Python 3.9 or later is recommended.

### Step 2: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 3: Run the notebook

```bash
jupyter notebook VinaySancheti_CustomerChurnPrediction.ipynb
```

Open the notebook and run the cells from top to bottom.

### Dataset handling

The notebook first looks for:

```text
data/Telco-Customer-Churn.csv
```

If the file is not present, it attempts to download the CSV from the IBM GitHub repository.

For a completely offline run, download the dataset from the source link and place it at:

```text
data/Telco-Customer-Churn.csv
```

## 9. Expected Outputs

Running the notebook produces:

- Dataset summary
- Missing-value analysis
- Churn distribution
- Churn analysis by contract
- Churn analysis by payment method
- Churn analysis by internet service
- Tenure and monthly-charge analysis
- Correlation/association visualizations
- Model comparison table
- Confusion matrices
- Classification reports
- ROC curves
- Feature-importance analysis

## 10. Limitations

The dataset is a cross-sectional sample rather than a sequence of monthly customer snapshots. Therefore, the model should be treated as an educational classification exercise and not as proof that a particular retention action will cause a customer to remain.

## 11. Conclusion

The project demonstrates how data analytics and machine learning can be combined to understand customer churn. The analysis focuses on identifying patterns in customer tenure, contracts, services, billing characteristics, and other attributes and then uses classification algorithms to predict churn.

The notebook is designed to be reproducible: the same dataset and preprocessing pipeline can be used to rerun the analysis and generate the evaluation results.

## 12. Author

**Vinay Sancheti**  
B.Tech Computer Science and Engineering  
Pimpri Chinchwad University, Pune
