# Project: Car Price Predictiopn

**Description:**
Developed a machine learning model to predict the price of a car using a dataset obtained from Kaggle. Explored various algorithms such as Linear Regression, Support Vector Machines, K-Nearest Neighbors, Random Forest, and Decision Tree for the regression problem.

**Technologies and Libraries:**
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Statmodels

**Key Steps:**
1. **Understand The Data:** Begin by understanding the dataset, including the features, target variable, and the nature of the data.
2. **Data Cleaning:** Performed data cleaning to handle inconsistent data.
3. **Handling Missing Values:** There is no any Missing Values in this Data Set
4. **Handling Duplicates:** Identify and remove any duplicate records from the dataset.
5. **Handling Outliers:** Identify and address outliers in the dataset, considering whether to remove, transform, or handle them through robust modeling techniques. Here used IQR technique and intuition of the real world scenarios.
6. **Handling Categorical Variables:** Convert categorical variables into a format suitable for regression modeling . In here One Hot Encoding was used.
7. **Data preprossessing and feature Scalling:** Preprocess the data, involve scaling numerical features to a standardized range.
8. **Model Building and Model Selection:** Try out Linear Regression, KNN, SVR, Decision Tree, Random Forest models and Compared the performance of different models based on root mean squared error.
9. **Hyper paraneter tuning:** Fine-tune the hyperparameters of the selected regression model(s) using Random search.
10. **Checking for Overfitting and Underfitting** Check final model is generalized well or not.

Please visit the [repository](https://github.com/tillyshan/Car_Price_Prediction/blob/main/Car_Price_Prediction.ipynb) for the Code.

### RMSE

RMSE is the standard deviation of the residuals. So, RMSE gives us the standard deviation of the unexplained variance by the model. It can be calculated by taking square root of Mean Squared Error. RMSE is an absolute measure of fit. It gives us how spread the residuals are, given by the standard deviation of the residuals. 

### Model Selection 

After evaluating multiple machine learning models using cross validation, the final model was selected based on its performance, with gave minimum mean squarred error. Random Forest was the best model.

#### Best Model: [Random Forest]

Then carry out hyperparameter tuning to further increase model performance.

