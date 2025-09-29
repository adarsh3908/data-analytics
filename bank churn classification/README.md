# Bank Customer Churn Classification

## Project Overview
This project analyzes bank customer data to predict churn (customers leaving the bank) using machine learning classification techniques. The analysis includes comprehensive exploratory data analysis, feature engineering, and comparison of multiple classification algorithms to identify customers at risk of churning.

## Dataset
- **File**: `Bank_Churn.csv`
- **Source**: Bank customer data with demographic and account information
- **Size**: 10,000 customer records
- **Target Variable**: `Exited` (1 = churned, 0 = stayed)
- **Key Features**:
  - **Demographics**: Age, Gender, Geography
  - **Financial**: CreditScore, Balance, EstimatedSalary
  - **Banking Behavior**: Tenure, NumOfProducts, HasCrCard, IsActiveMember

## Business Problem
Customer churn is a critical issue for banks as:
- Acquiring new customers costs 5-25x more than retaining existing ones
- Churned customers represent lost revenue and relationship value
- Early identification allows proactive retention strategies
- Understanding churn drivers helps improve service offerings

## Analysis Approach

### 1. Exploratory Data Analysis (EDA)
- **Data Quality Assessment**: Missing values, data types, distributions
- **Statistical Summary**: Descriptive statistics for all variables
- **Correlation Analysis**: Identifying relationships between features
- **Visual Analysis**: Distributions, patterns, and churn relationships

### 2. Feature Engineering
- **Derived Features**: 
  - `balance_to_income`: Balance-to-salary ratio indicating financial health
  - `income_v_product`: Income per product ratio showing value density
- **Data Preprocessing**: One-hot encoding for categorical variables
- **Feature Selection**: Removing non-predictive identifiers

### 3. Machine Learning Models
- **Logistic Regression**: Baseline linear model with interpretable coefficients
- **Random Forest**: Ensemble method for capturing non-linear patterns
- **Model Optimization**: Hyperparameter tuning using GridSearchCV/RandomizedSearchCV

### 4. Model Evaluation
- **Classification Metrics**: Accuracy, Precision, Recall, F1-Score
- **ROC Curve Analysis**: AUC score for model discrimination ability
- **Precision-Recall Curves**: Threshold optimization for business needs
- **Feature Importance**: Understanding key churn drivers

## Key Findings

### Customer Segmentation Insights
- **High-Risk Demographics**: Specific age groups and geographic regions show higher churn
- **Product Usage Patterns**: Customers with extreme numbers of products (too few/many) are at risk
- **Financial Indicators**: Balance-to-income ratios reveal financial stress patterns

### Predictive Model Performance
- **Logistic Regression**: Provides interpretable baseline with moderate performance
- **Random Forest**: Superior performance with ensemble learning approach
- **Feature Importance**: Age, geography, and product usage emerge as top predictors

### Business Recommendations
- **Targeted Retention**: Focus on high-risk customer segments identified by the model
- **Product Portfolio**: Optimize product offerings based on usage patterns
- **Geographic Strategy**: Customize retention approaches by region
- **Proactive Monitoring**: Implement early warning systems using model predictions

## Technical Implementation

### Data Science Techniques
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning pipeline and model evaluation
- **Seaborn/Matplotlib**: Statistical visualization and model interpretation
- **Feature Engineering**: Creating business-relevant derived variables

### Model Pipeline
1. **Data Loading & Cleaning**: Handle missing values and data types
2. **Exploratory Analysis**: Understand patterns and relationships
3. **Feature Engineering**: Create predictive derived features
4. **Model Training**: Train and validate multiple algorithms
5. **Evaluation**: Compare models using multiple metrics
6. **Interpretation**: Extract business insights from results

## Files Structure
```
bank churn classification/
├── README.md
├── Bank Churn Classificaton.ipynb
└── Bank_Churn.csv
```

## Requirements
- Python 3.x
- pandas
- scikit-learn
- seaborn
- matplotlib
- numpy

## Usage
1. Install required libraries
2. Open the Jupyter notebook
3. Run cells sequentially to reproduce the analysis
4. Modify hyperparameters or try additional models as needed

## Model Performance Summary
- **Logistic Regression**: Interpretable baseline model with good performance
- **Random Forest**: Best performing model with ensemble approach
- **Business Impact**: Models enable proactive customer retention strategies

## Future Enhancements
- **Advanced Models**: Deep learning, XGBoost, ensemble methods
- **Feature Engineering**: Time-series features, customer lifecycle analysis
- **Deployment**: Real-time scoring API for production use
- **A/B Testing**: Validate retention strategy effectiveness
- **Cost-Benefit Analysis**: ROI calculation for retention campaigns

---
*This analysis demonstrates the practical application of machine learning to solve real business problems in the financial services industry.*