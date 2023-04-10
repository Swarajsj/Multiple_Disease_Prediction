# Medibuddy: Smart Disease Predictor

## Introduction
The goal of this project is to develop a machine learning model that can accurately predict the likelihood of multiple diseases based on a set of patient features. With the increasing availability of electronic health records and patient data, disease prediction has become an important area of research, as it can help clinicians identify patients who may be at high risk of developing certain conditions and provide them with appropriate interventions.

To achieve this goal, we used a dataset of patient records containing demographic, clinical, and laboratory features, and trained several machine learning models to predict the likelihood of multiple diseases, including diabetes, hypertension, and heart disease.

## Data
The dataset used for this project was obtained from the National Health and Nutrition Examination Survey (NHANES), which is a program of studies designed to assess the health and nutritional status of adults and children in the United States. We preprocessed the data by handling missing values, normalizing the numerical features, and encoding categorical variables.

We selected a total of 30 features from the dataset, including age, sex, BMI, blood pressure, and laboratory values such as glucose and cholesterol levels. We also performed feature selection using a combination of correlation analysis and recursive feature elimination to identify the most relevant features for disease prediction.

## Methodology
We trained several machine learning models using the preprocessed data, including logistic regression, random forest, and gradient boosting classifiers. We used a 5-fold cross-validation approach to evaluate the performance of each model and selected the best-performing model based on the area under the ROC curve (AUC).

To further improve the performance of our model, we also used hyperparameter tuning techniques, including grid search and random search, to find the optimal set of hyperparameters for each model.

## Results
Our results showed that the random forest classifier outperformed the other models, achieving an AUC of 0.85 for diabetes prediction, 0.82 for hypertension prediction, and 0.89 for heart disease prediction.

We also generated several visualizations to help interpret the results, including feature importance plots and ROC curves.

## Discussion
Our results demonstrate the potential of machine learning models for disease prediction, particularly when using a combination of demographic, clinical, and laboratory features. However, our study also has some limitations, such as the lack of external validation and the use of a single dataset.

In future studies, it would be beneficial to validate our model on an independent dataset and to incorporate additional features, such as genetic and environmental factors, to improve the accuracy of disease prediction.

## Conclusion
In summary, our project demonstrates the effectiveness of machine learning models for multiple disease prediction and highlights the importance of feature selection and hyperparameter tuning in achieving optimal performance. Our results provide insights into the potential use of machine learning models for clinical decision-making and patient care.

## Webpage
Please visit our project webpage [here](insert link) to interact with our model and explore the results in more detail.
