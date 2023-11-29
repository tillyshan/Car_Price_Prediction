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
6. **Handling Categorical Variables:** onvert categorical variables into a format suitable for regression modeling . In here One Hot Encoding was used.
7. **Data preprossessing and feature Scalling:** Preprocess the data, which may involve scaling numerical features to a standardized range.
8. **Model Building and Model Selection:** Try out Linear Regression, KNN, SVR, Decision Tree, Random Forest models and Compared the performance of different models based on root mean squared error.
9. **Hyper paraneter tuning:** Fine-tune the hyperparameters of the selected regression model(s) using Random search.

Please visit the [repository](https://github.com/tillyshan/Heart-Disease-detection/blob/main/heart%20disease%20detection.ipynb) for the Code.

### Model Selection and Web Application

After evaluating multiple machine learning models, the final model was selected based on its performance, with a focus on recall for the positive class, ensuring accurate identification of heart disease patients.

#### Best Model: [Logistic Regression]

To make the model accessible and user-friendly, a basic web application was created using the Streamlit library. The application allows users to input relevant data and get predictions regarding the likelihood of heart disease. It provides a basic user-friendly interface.

Please visit the [repository](https://github.com/tillyshan/Heart-Disease-detection/blob/main/web%20application.py) for the model.

![App interface](https://github.com/tillyshan/Heart-Disease-detection/blob/main/image.png)


### Usage
To run the Heart Disease Detection application, follow these steps:

1. **Clone the Repository:** Clone the GitHub repository to your local machine using the following command:

   ```bash
   git clone https://github.com/tillyshan/Heart-Disease-detection.git
    ```

2.**Run the Application:** Start the application by running the following command in your Anaconda Prompt, Command Prompt, or PyCharm Terminal:

   ```bash
   streamlit run web application.py
   ```

3. **Access the Application:** Open a web browser and navigate to the URL provided in the terminal (usually, it will be something like http://localhost:8501). You will see the user-friendly interface where you can enter your details.

Please note that the application is for demonstration and educational purposes.

### Future Enhancements
"The model achieves a 70% accuracy rate. Various models and model combinations can be employed to enhance performance."

This README provides an overview of the "Heart Disease Detection" project, highlighting its key components and the development of a user-friendly web application for predicting heart disease. For more detailed information and access to the code, please visit the [repository] (https://github.com/tillyshan/Heart-Disease-detection)).

This project showcased the significance of prioritizing recall for the positive class in the context of heart disease detection, emphasizing the accurate identification of patients at risk. It demonstrated the effective use of machine learning and data preprocessing techniques to build a robust predictive model for healthcare applications.

