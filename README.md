# Predictive-Analysis
Conducted a predictive analysis on Percentage Prediction based on Number of Hours Studied using Supervised Learning.
Used a simple supervised learning linear regression model to predict the percentage score of a student based on the number of hours devoted to study.
The steps involved are as follows:
1. Importing modules i.e. numpy, pandas, sklearn, matplotlib and seaborn.
2. Creating a pandas data frame using the read_csv method from the data set provided as url.
3. All the missing values are replaced by NaN, this makes data easier to clean in a larger set. Thus considered a good practice.
4. Create a Linear Regression object of LinearRegression method from sklearn.linear_model.
5. Train the model to fit the data with X as Hours studied and Y as Scores obtained.
