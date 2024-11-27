# Telecom-Churn

0. Problem Statement
- In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.
- For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.
- In this competition, your goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.

1. Goal
- It is your job to predict if a customer will churn, given the ~170 columns containing customer behavior, usage patterns, payment patterns, and other features that might be relevant. Your target variable is "churn_probability"
  
2. Metric
- Submissions are evaluated on Classification Accuracy between the value of the predicted value and the actual value of churn for each of the customers.

3. Accuracy score formula
- Accuracy = ((TP+TN)/(TP+TN+FP+FN))¶

4. Suggested Steps
In the competition link, check the Code tab for the Starter Notebook that you can use as a reference for this entire case study. Some of the steps that you can use are as follows:
A) Data Understanding, Preparation, and Pre-Processing :
- Data understanding, identification of potentially useful and non-useful attributes and variable importance and impact estimation
- Data preparation, performing data cleaning, missing values imputation, outlier removal, and column level standardization (for e.g., date, etc.) into one format
B) Exploratory Data Analysis :
- Performing basic preliminary data analysis including finding the correlation between variables and scatter plots to identify relationships between variables
- Performing advanced data analysis, including plotting relevant heatmaps, histograms, and basic clustering to find patterns in the data
C) Feature Engineering and Variable Transformation :
- Feature engineering and performing one or more methods on attributes that can lead to the creation of a new potentially useful variable; for e.g., day from the date
- Variable transformation and applying categorical variable transformations to turn into numerical data and numerical variable transformations to scale data
D) Model Selection, Model Building, and Prediction :
- Identifying the type of problem and making a list of decisive models from all available choices
- Choosing a training mechanism; for e.g., cross-validation, etc., and tuning hyperparameters of each model
- Testing each model on the respective model evaluation metric
- Choosing the best model based on the fit of the data set and output variable
- Using ensemble options to improve the efficacy based on the evaluation metric stated in the problem¶
