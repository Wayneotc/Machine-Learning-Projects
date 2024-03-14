# Factors Affecting Life Expectancy
This machine learning project aims to analyze various factors affecting life expectancy across 193 countries from 2000 to 2015. By considering immunization, mortality, economic, and social factors, the project seeks to identify the key predictors influencing life expectancy and provide insights for improving population health.
## Methodology
•	Exploratory Data Analysis (EDA): Conduct exploratory data analysis to gain insights into the dataset and understand the relationships between variables.
•	Data Preprocessing: Perform data cleaning, handle missing values, and preprocess the dataset for further analysis.
•	Feature Selection: Select the most relevant features that strongly correlate with life expectancy.
•	Data Visualization.
•	Model Development: Build and train machine learning using various regression models including Linear Regression, Lasso, Elastic Net, Ridge Regression, Random Forest and Decision Tree Regression. 
•	Model Evaluation: The models were evaluated based on their R-squared scores, because it is a comprehensive metric that assesses the overall fit of the regression model.

## Conclusion
1.Linear Regression : R-squared Score: 80.03 
2.Lasso : R-squared Score: 80.03 
3.Elastic Net : R-squared Score: 80.02 
4.Ridge Regression : R-squared Score: 80.03 
5.Random Forest : R-squared Score: 95.90 
6.Decision Tree Regression : R-squared Score: 90.29

Random Forest achieves the lowest Mean Squared Error (MSE), implying better accuracy in predictions. It also has the lowest Mean Absolute Error (MAE), indicating better precision in predicting the target variable. Random Forest achieves the highest R-squared score, indicating a strong fit to the data and capturing a significant portion of the variance in the target variable. Random Forest also has the lowest Root Mean Squared Error (RMSE), which represents the standard deviation of the residuals and signifies the model's accuracy in predicting the target variable.
Random Forest outperform the other models.


