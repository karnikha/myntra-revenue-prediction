#  Myntra Brand Revenue Prediction using Customer Lifetime Value (CLV) with Machine Learning Techniques

## Problem Statement
The objective of this project is to predict brand-wise revenue on Myntra using machine learning techniques. This helps in understanding customer behavior, identifying high-performing brands, and improving business decision-making.

## Project Pipeline
Data Collection  
→ Data Preprocessing  
→ Exploratory Data Analysis (EDA)  
→ Feature Engineering  
→ Feature Selection  
→ Model Training  
→ Model Evaluation  
→ Prediction  

## Dataset Details
- **Source**: Myntra Brand Dataset  
- **Description**: Contains customer, product, and transaction-related information used to predict revenue.

### Features:
- Brand  
- Product Category  
- Customer Gender  
- Membership Status  
- Customer City  
- Order Frequency  
- Recency Days  
- Payment Method  
- **Target Variable**: Brand Total Revenue  

## Data Preprocessing
- Handled missing values (mean, median, mode)
- Removed duplicate records
- Encoded categorical data (Label Encoding & One-Hot Encoding)
- Outlier detection using IQR method
- Feature scaling using Standardization and MinMax Scaling

## Exploratory Data Analysis
- Distribution plots (histograms, boxplots)
- Correlation heatmap
- Revenue distribution analysis
- Categorical feature analysis
- Relationship visualization between features


## Feature Engineering & Selection
- Feature transformation and cleaning
- Correlation-based filtering
- Recursive Feature Elimination (RFE)
- Feature importance using Random Forest


## Models Implemented
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Support Vector Regressor (SVR)  
- K-Nearest Neighbors (KNN)  


## Best Model
- **Gradient Boosting**
- Selected based on better performance and stability


## Model Evaluation
- Evaluation Metric: **R² Score**
- Compared all models and selected the best-performing one


## Results
- Accurate revenue prediction achieved
- Identified important features influencing revenue


## How to Run the Project

### Step 1:
Open the notebook from GitHub in Google Colab

### Step 2:
Run all cells:

## Required Libraries
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- joblib  
👉 (For Colab) 

## Team Members
- Joshega K
- Karniha P
- Karnikha R
- Sharon Rithika A  
 
