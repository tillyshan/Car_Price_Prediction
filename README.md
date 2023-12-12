# Project: Car Price Prediction

## Description:
Developed a machine learning model to predict car prices using a dataset with diverse features. Explored and implemented various algorithms, including Linear Regression, Support Vector Machines, K-Nearest Neighbors, Random Forest, and Decision Tree, to address the regression problem.

**Interactive APP:**
- Built an interactive web application using the Flask framework, enabling users to obtain predicted car prices through an intuitive interface.

![Car Price Prediction APP Interface](https://github.com/tillyshan/Car_Price_Prediction/blob/main/clip.gif)


## Technologies and Libraries:
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Statmodels
- Flask
- Postman

**Other Languages:**
- HTML
- CSS
- Java Script

## Key Steps:
 here is the quick summary:

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
11. **Test the final model** Check the model performance on the test dataset.

Please visit the [repository](https://github.com/tillyshan/Car_Price_Prediction/blob/main/Car%20Price%20Prediction.ipynb) for the Code with detailed process.

**RMSE**

RMSE is the standard deviation of the residuals. So, RMSE gives us the standard deviation of the unexplained variance by the model. It can be calculated by taking square root of Mean Squared Error. RMSE is an absolute measure of fit. It gives us how spread the residuals are, given by the standard deviation of the residuals. 

### Model Selection 

After evaluating multiple machine learning models using cross validation, the final model was selected based on its performance, with gave minimum mean squarred error. Random Forest was the best model.

### Hyper Parameter Tuning

Then carry out hyperparameter tuning to further increase model performance.Following two methods are used.
- RandomizedsearchCV : First apply randomizedsearch method and narrow down parameter space
- GridsearchCV : After narrow down parameter space gridsearch method used to find best values for hyperparameters.

### Model Finalizing

Final Model was save as pickle file. Other required data for the app were save as json files.

## Build web Application

### Key Features
- **Flask Server** : Developed a Flask server to handle user inputs and predict car prices using a machine learning model.
- **User Interface Design** : Designed an interactive and visually appealing web interface using CSS, JavaScript, and HTML.
- **Responsive Design** : Ensured a responsive and adaptive design for the web interface, allowing users to access and interact with the application seamlessly.
- **Technological Stack:**
  - Leveraged Flask for server-side logic and handling requests.
  - Utilized CSS for styling to enhance the visual appeal of the web interface.
  - Employed JavaScript for interactive elements and dynamic functionality.
  - Structured the web pages using HTML for effective layout and content presentation.
 
 ## usage

This repository contains the necessary files to run a car price prediction web application. Follow the steps below to set up and start the server.

### File Downloads

1. **[model.rar](https://github.com/tillyshan/Car_Price_Prediction/blob/main/model.rar)**: Contains a pickle file and other JSON files required to run the machine learning model.

2. **[server.rar](https://github.com/tillyshan/Car_Price_Prediction/blob/main/server.rar)**: Includes two Python files (`server.py` and `util.py`) and an `artifacts` folder containing Flask implementation for the server.

3. **[client.rar](https://github.com/tillyshan/Car_Price_Prediction/blob/main/client.rar)**: Contains the `app.html` file, which is the designed web app for predictions.

### Setup and Run

#### 1. Extract Files

   - Extract the contents of `model.rar`, `server.rar`, and `client.rar` using your preferred archive tool.

#### 2. Start Server

   - Open any command line interface.
   - Navigate to the extracted `server` folder.
   - Run the command: `python server.py` to start the web server.

#### 3. Open Web App

   - Open the extracted `client` folder.
   - Open the `app.html` file in a web browser to access and use the car price prediction web application.

#### 4. Make Predictions

   - Use the web interface to input data and obtain car price predictions.

Feel free to explore the code and make adjustments as needed.

 




