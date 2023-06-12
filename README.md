# End-to-end Loan Eligibility Prediction
Dream Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban and rural areas. Customers first apply for a home loan after that company validates the customer’s eligibility for a loan. 

The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling out the online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. 

To automate this process, they have given a problem to identify the customer segments, that are eligible for loan amounts so that they can specifically target these customers.
## Notebook Outline
1. Loading and Understanding the Dataset
2. Exploratory Data Analysis
    1. Univariate Analysis
        1. Categorical Features
        2. Numerical Features
        3. Insights
    2. Bivariate Analysis
        1. Categorical Features vs Target Variable
        2. Numerical Features vs Target Variable
        3. Insights
3. Data Preprocessing
    1. Missing Values Treatment
    2. Dropping Unecessary Columns
    3. Feature Encoding 
4. Model Development
    1. Splitting The Dataset
    2. Logistic Regression
    3. Logistic Regression with Stratified k-folds Cross-validation
