# Car_data_analysis_with_BigQuery
In this project, I utilized BigQuery to analyze an automotive dataset. The primary objectives were to identify the key features influencing car prices and to develop a predictive model using BigQuery ML logistic regression.

The first step was to understand the data at hand for which I did EDA(Exploratory Data Analysis)
    Verify the Data and Schema:
      Check the Table Schema: Ensure that each column (e.g., car prices, mileage, doors, transmission, owners, fuel type, engine size) is correctly defined with appropriate    
 data types.
      Sample the Data: Run a query to retrieve a few rows from the table to see if the data looks as expected.
    Then I computed summary statistics
      Descriptive Statistics: Calculate metrics like count, minimum, maximum, average (mean), median, and standard deviation for numerical features such as car prices, mileage, and engine size.
      Identify Outliers and Missing Values: This step helps in understanding the range of values and whether any cleaning is needed.
    Examine Data Distributions:

      Distribution Analysis: Create histograms or frequency distributions for key numerical variables to see how the data is spread out.
      Categorical Analysis: For features like transmission and fuel type, use group-by queries to see the distribution of car prices across different categories.
Initial Correlation Analysis:

      Correlation Coefficients: Calculate correlation coefficients between car prices and the other numerical features (e.g., mileage, engine size) to get a preliminary idea of linear relationships.
After this I moved to Data Preparation and Feature Engineering 
  Clean and Transform Data:
    Ensure your dataset is free of issues (missing values, incorrect types, etc.). For categorical features (like transmission or fuel type), convert them into numerical representations (e.g., dummy/one-hot encoding or binary flags).
Build a Predictive Model
  Using BigQuery ML, I created a linear regression model to predict car prices. Linear regression models are interpretable because the weight (coefficient) assigned to each feature shows its impact on the target variable.
  Evaluate the Model and Extract Feature Weights
    Once the model was trained, I inspected the weights (coefficients) associated with each feature to understand their influence.
Validate the Findings
Model Performance Metrics:
It’s important to check how well your model performs to ensure that the conclusions about feature influence are reliable. So I did that at the last.
