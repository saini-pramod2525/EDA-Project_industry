INDUSTRY PERFORMANCE ANALYSIS USING EDA AND MACHINE LEARNING

Author: Pramod Saini
Project Type: Exploratory Data Analysis (EDA) and Machine Learning
Tools Used: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Jupyter Notebook

------------------------------------------------------------
PROJECT OVERVIEW
------------------------------------------------------------

This project performs Exploratory Data Analysis (EDA) and Machine Learning on an Industry Performance Dataset containing 15,000 company records.

The objective of the project is to analyze business performance metrics such as:

- Employee Count
- Annual Revenue
- Profit Margin
- Customer Count
- Market Rating
- Industry
- Country
- Region

and develop a machine learning model to predict annual company revenue.

------------------------------------------------------------
DATASET INFORMATION
------------------------------------------------------------

Total Records: 15,000

Features:

1. id
2. company_name
3. industry
4. country
5. employee_count
6. annual_revenue_million
7. profit_margin_percent
8. founded_year
9. customer_count
10. market_rating
11. created_date
12. region

------------------------------------------------------------
EDA PERFORMED
------------------------------------------------------------

1. Data Inspection
   - Dataset Structure
   - Data Types
   - Missing Values Check

2. Univariate Analysis
   - Statistical Summary
   - Histograms
   - Boxplots
   - Skewness
   - Kurtosis

3. Categorical Analysis
   - Industry Distribution
   - Country Distribution
   - Region Distribution

4. Bivariate Analysis
   - Numerical vs Numerical Relationships
   - Correlation Heatmap

5. Multivariate Analysis
   - Industry × Revenue Band × Employee Count
   - Country × Customer Count Band × Revenue

------------------------------------------------------------
MACHINE LEARNING MODEL
------------------------------------------------------------

Algorithm Used:
- Linear Regression

Target Variable:
- annual_revenue_million

Features Used:
- industry
- country
- region
- employee_count
- profit_margin_percent
- founded_year
- customer_count
- market_rating

Steps:
1. Data Preprocessing
2. Label Encoding
3. Train-Test Split
4. Model Training
5. Prediction
6. Model Evaluation

------------------------------------------------------------
MODEL RESULTS
------------------------------------------------------------

MAE  : 248.36
RMSE : 287.21
R²   : -0.00035

Observation:
The model achieved a negative R² score, indicating limited predictive capability. Correlation analysis revealed that the predictor variables had very weak relationships with annual revenue, resulting in low model performance.

------------------------------------------------------------
LIBRARIES USED
------------------------------------------------------------

pandas
numpy
matplotlib
seaborn
scikit-learn

------------------------------------------------------------
HOW TO RUN THE PROJECT
------------------------------------------------------------

1. Install Python and Anaconda.
2. Open Jupyter Notebook.
3. Load the notebook file.
4. Ensure INDUSTRY.csv is present in the same directory.
5. Run all cells sequentially.

------------------------------------------------------------
PROJECT CONCLUSION
------------------------------------------------------------

The project successfully demonstrates the complete data science workflow including data preprocessing, exploratory data analysis, visualization, machine learning model development, and performance evaluation.

Although the predictive performance of the model was limited due to weak relationships among variables, the project provides valuable insights into industry performance metrics and serves as a practical application of data analytics and machine learning techniques.

------------------------------------------------------------
END OF FILE
------------------------------------------------------------
