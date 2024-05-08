# Heart Disease Prediction using Classification Techniques

This project focuses on predicting the likelihood of heart disease in patients using various classification techniques in machine learning. Heart disease is a prevalent health condition globally, and early prediction can lead to better management and improved outcomes for patients.

## Introduction

Heart disease, also known as cardiovascular disease, encompasses a range of conditions affecting the heart and blood vessels. Machine learning models can analyze patient data to identify patterns and risk factors associated with heart disease, enabling early intervention and personalized treatment plans. In this project, we explore classification algorithms to predict the presence of heart disease based on patient demographics, medical history, and clinical measurements.

## Dataset

The dataset used in this project is sourced from the Framingham Heart Study, a long-term epidemiological study initiated in 1948 to identify risk factors for cardiovascular disease. It contains demographic information, medical history, and clinical measurements of patients enrolled in the study. The target variable, 'TenYearCHD', indicates whether the patient is at risk of developing coronary heart disease within ten years.
The dataset is available as https://media.geeksforgeeks.org/wp-content/uploads/20240307152534/framingham.csv

## Data Preprocessing

- Checked dataset information and description.
- Handled missing values by imputing them with means or mode values.
- Conducted exploratory data analysis (EDA) to understand the distribution of features and relationships between variables.
- Detected gender bias and applied stratum sampling to balance the dataset.

## Model Building

- Explored various classification algorithms, including Decision Tree, Random Forest, and Logistic Regression.
- Split the dataset into training, validation, and test sets.
- Trained the models on the training set and evaluated their performance using appropriate metrics.
- Tuned hyperparameters using techniques such as Grid Search to improve model accuracy.

## Results

- Decision Tree and Random Forest models achieved moderate accuracy in predicting heart disease risk.
- Logistic Regression, fine-tuned with Lasso Regression and Grid Search, demonstrated higher accuracy compared to other models.

## Conclusion

The project demonstrates the potential of machine learning in predicting heart disease risk based on patient data. By leveraging classification techniques and appropriate feature engineering, we can develop accurate predictive models to assist healthcare professionals in identifying individuals at higher risk of developing heart disease.

## Future Work

- Further optimization of model hyperparameters to improve performance.
- Integration of additional features or datasets to enhance predictive accuracy.
- Deployment of the predictive model in clinical settings for real-time risk assessment.
