# Heart Disease Prediction using Logistic Regression
This project aims to predict the presence of heart disease in patients using logistic regression. The dataset used is the Heart Disease UCI dataset from Kaggle, which contains data on patient characteristics and whether or not they have heart disease. The goal of the project is to build a machine learning model that can accurately predict the presence of heart disease based on the patient's characteristics.

Dataset
The Heart Disease UCI dataset contains 303 observations and 14 features, including age, sex, chest pain type, and maximum heart rate. The data has already been cleaned and preprocessed, so no additional preprocessing was needed for this project.

Modeling
Logistic regression was chosen as the machine learning algorithm for this project because it is a simple yet effective classification algorithm that works well with binary classification problems like heart disease prediction. The logistic regression model was built using scikit-learn in Python. Hyperparameter tuning was done using GridSearchCV to find the optimal hyperparameters for the model.

Results
The model achieved an accuracy of 85% on the test set, which indicates that it is a good predictor of heart disease. Evaluation metrics such as precision, recall, and F1 score were also calculated to assess the performance of the model.

Conclusion
In conclusion, this project demonstrates the effectiveness of logistic regression in predicting the presence of heart disease in patients. The insights gained from this project can be used by healthcare professionals to identify patients at high risk for heart disease and take preventative measures to reduce their risk. Future work could involve exploring other machine learning algorithms or incorporating additional data sources to improve the accuracy of the model.
