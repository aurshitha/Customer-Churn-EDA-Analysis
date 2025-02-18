# Customer-Churn-EDA-Analysis
Exploratory Data Analysis (EDA) and Descriptive Analysis on a credit card customer dataset to understand churn patterns. This project investigates key attributes influencing customer attrition using statistical analysis, data visualization (Seaborn, Matplotlib, Plotly), and data preprocessing techniques. The insights help in predicting churn and improving customer retention strategies.

**Problem Statement:** EDA on Credit Card Customer Churn
Happy Bank provides various credit cards to customers. The manager of Happy Bank is disturbed by more and more customers leaving their credit card services. The team did a customer survey to check customer attrition. Various customer attributes like Customer_Age, Credit_Limit, Dependent_Count. The team would really appreciate it if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction.

**Exploratory Data Analysis (EDA)**
In this section, I performed an initial exploration of the dataset to understand its structure and gain insights that would guide further analysis.

**1. Data Loading**
Loaded the dataset using Pandas and checked the initial structure to understand the columns and data types.
**2. Missing Values**
Checked for any missing values in the dataset and handled them appropriately to ensure the dataset is clean.
**3. Data Visualization**
Created basic visualizations such as histograms and boxplots to understand the distribution of numerical features and identify any potential outliers.
**4. Correlation Analysis**
Analyzed correlations between numerical features using a correlation matrix to identify any highly correlated features.
**5. Feature Engineering**
Performed basic feature engineering by encoding categorical variables to prepare the data for modeling.


**Technologies Used**
**Python:** Programming language for data manipulation, analysis, and visualization.
**Pandas:** Data manipulation and cleaning.
**Matplotlib:** Basic plotting for visualizing data distributions and relationships.
**Seaborn:** Advanced statistical visualizations (e.g., pair plots, heatmaps, bar plots).
**Plotly:** Interactive plots for more engaging visualizations.

**Key Insights**
**Data Distribution:** Numerical features exhibited varied distributions, indicating the need for potential transformation in future steps.
**Missing Values:** Some columns had missing values, which were handled by imputation or removal as necessary.
**Correlation:** A few features were found to be highly correlated, which may need attention during modeling.
**Outliers:** Outliers were detected in the dataset, which may require handling in the preprocessing stage.
