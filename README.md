# Medical-Insurance-Cost-Prediction-Using-Ensemble-Learning
# Project Overview

This project predicts medical insurance costs using Machine Learning regression techniques.

The project compares different regression models and identifies the best-performing model based on MAE, MSE, RMSE, and R² Score.

# Dataset

The dataset contains 1,338 records and 7 columns:

##### age – Age of the person
sex – Gender
bmi – Body Mass Index
children – Number of children
smoker – Smoking status
region – Residential region
charges – Medical insurance cost (Target)
# Machine Learning Models

The following models are used:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
AdaBoost Regressor
Gradient Boosting Regressor
Extra Trees Regressor

# Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook

# Evaluation Metrics

The models are evaluated using:

MAE (Mean Absolute Error) – Measures the average prediction error.
MSE (Mean Squared Error) – Measures the squared prediction error.
RMSE (Root Mean Squared Error) – Shows the prediction error in the same unit as the target.
R² Score – Measures how well the model explains the variation in insurance costs.
# Results

The performance of all models is compared using the above evaluation metrics.

A graph is also generated to compare the R² scores of the models.
Among the six models, Gradient Boosting achieved the highest R² score of approximately 0.88, followed by Random Forest (0.87) and Extra Trees (0.84). Decision Tree performed the lowest with an R² of about 0.73. Overall, ensemble models provided better prediction performance for medical insurance costs.

# Conclusion

This project demonstrates how Machine Learning and ensemble regression techniques can be used to predict medical insurance costs. Different models are compared to determine which algorithm provides better prediction performance.

# Future Scope
Use larger and more diverse healthcare datasets
Apply advanced ensemble techniques
Perform hyperparameter tuning
Use feature importance for better interpretation
Develop a web application for insurance cost prediction
