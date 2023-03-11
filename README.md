# Customer Churn Prediction with Machine Learning
This project is a machine learning project that aims to predict customer churn for a telecom company. Customer churn refers to the number of customers who leave a company's products or services during a given time period. Predicting customer churn is crucial for businesses as it helps them retain their customers and increase revenue.

## Dataset
The dataset used for this project can be found [here](https://github.com/agusabdulrahman/customer-churn-prediction/blob/main/Churn%20Modeling.csv). The dataset contains information on customer demographics, account information, and service details. The target variable is a binary variable indicating whether the customer has churned or not.

## Methodology
The project was divided into the following steps:

- Data Cleaning and Preprocessing: The dataset was cleaned and preprocessed to remove missing values, outliers, and other inconsistencies
- Exploratory Data Analysis: Various exploratory data analysis techniques were used to understand the relationship between different variables and the target variable.
- Feature Engineering: New features were created to improve the performance of the machine learning models.
- Model Selection: Several machine learning models were trained and tested to select the best performing model.
- Hyperparameter Tuning: The hyperparameters of the selected model were tuned to optimize the performance.
- Model Evaluation: The final model was evaluated on a test dataset to measure its performance.

## Results
The final model decision tree model showed us overfitting problem. Hence the randomised search cv on random forest classifier gave us better accuracy which is 87 percent and wrong predictions made by the model are 243/2000 and grid search cv gave us 87 percent accuracy and wrong predictions are 246/2000. 

## Conclusion
The machine learning model developed in this project can be used by the telecom company to predict customer churn and take appropriate actions to retain customers. The model can also be improved further by incorporating additional data sources and refining the feature engineering process.

## Future Work
Future work could include:

- Incorporating additional data sources to improve the model's performance.
- Refining the feature engineering process to create more relevant features.
- Developing a web application for the telecom company to use the model in real-time.
- Deploying the model on a cloud platform for scalability and accessibility.

## References
[Scikit-Learn Library](https://scikit-learn.org/)

[Python Programming Language](https://www.python.org/)
