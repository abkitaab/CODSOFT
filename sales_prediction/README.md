Sales Prediction using Machine Learning
##Project Overview

This project demonstrates how Machine Learning can be used to predict sales based on advertising expenditures across different platforms (TV, Radio, Newspaper).
By applying regression models, businesses can estimate future sales and optimize their advertising budget for maximum impact.

 ##Dataset

The dataset advertising.csv contains 200 rows with the following columns:

TV → Advertising budget spent on TV (in $)

Radio → Advertising budget spent on Radio (in $)

Newspaper → Advertising budget spent on Newspaper (in $)

Sales → Units sold (target variable)

##Tools & Libraries Used

Python

Pandas, NumPy → Data handling & preprocessing

Matplotlib, Seaborn → Visualization

Scikit-learn → Linear Regression, Random Forest, evaluation metrics

**Workflow**
1. Data Exploration & Visualization

Pairplot (Seaborn) → To check pairwise relationships between features.

Correlation Heatmap → To identify which advertising channels correlate most with Sales.

 Observation:

TV and Radio show strong positive correlation with Sales.

Newspaper has weaker correlation.

2. Model Building

Linear Regression model was trained on 80% of the data and tested on 20%.

Random Forest Regressor was also used for comparison.

3. Model Evaluation

Linear Regression

Mean Squared Error (MSE): 2.90

R² Score: 0.90

**Random Forest Regressor**

R² Score: 0.95

 Random Forest gave better accuracy than Linear Regression.

4. Visualization

Scatter plot of Actual vs Predicted Sales shows model reliability.

5. Prediction Example

A new prediction was made for the following advertising budget:

new_ad_budget = pd.DataFrame({'TV':[200], 'Radio':[50], 'Newspaper':[100]})
predicted_sales = model.predict(new_ad_budget)


Output:

Predicted Sales: 21.09

##Results & Insights

The model can accurately forecast sales from ad spend.

TV and Radio ads have the highest influence on sales.

Newspaper ads contribute less compared to TV & Radio.

Random Forest provides a more robust prediction than Linear Regression.

##Conclusion

This project shows how businesses can use machine learning in Python to make data-driven decisions for advertising strategies.
By identifying the most effective advertising channels, companies can maximize sales while minimizing costs.

##Author
Ankita Biswas - ankitaab 
