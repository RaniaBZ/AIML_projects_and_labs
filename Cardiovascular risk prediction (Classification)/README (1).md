# **Project Summary**

The Cardiovascular Risk Prediction project aims to develop a robust and accurate machine learning model to classify patients into two different cardiovascular risk categories based on their health and lifestyle attributes. Cardiovascular diseases (CVDs) remain a leading cause of mortality worldwide, making early risk assessment and intervention crucial for reducing their impact on public health.

## **Objective:**

The primary objective of this project is to create a predictive model that can accurately categorize patients into one of the following cardiovascular risk groups:
1 - Patient has 10-year risk of coronary heart disease.
0- Patient doesn't have 10-year risk of coronary heart disease.
This classification will be based on a diverse set of input features, including demographic data, medical history, lifestyle choices, and clinical measurements.

# **Methodology:**

Data Collection: A comprehensive dataset containing information on a diverse group of individuals will be collected. This dataset will include variables such as age, gender, blood pressure, cholesterol levels, smoking status, family history of CVD, and more.

## **EDA:**

The insights gained during EDA will inform subsequent steps in the project, including feature selection, data preprocessing, and model development. EDA is crucial for selecting the most relevant features, understanding the data's underlying patterns, and ensuring the machine learning model's robustness and accuracy.
Moreover, EDA findings can be used to create informative visualizations and reports that convey the dataset's characteristics and provide healthcare professionals and stakeholders with a better understanding of the data, which can be useful for decision-making and model interpretation.
Data Preprocessing: Data preprocessing will involve cleaning and transforming the dataset, handling missing values, encoding categorical variables, and scaling numerical features. Special attention will be given to ensure data privacy and compliance with ethical standards.

## **Feature Selection** 
Feature selection techniques will be applied to identify the most relevant features for predicting cardiovascular risk. This step will help reduce model complexity and improve interpretability.

## **Model Selection** 
Below supervised machine learning classification algorithms will be evaluated.We will use total 10 algorithms.

Logistic regression
Decision Tree
KNeighbors Classifier
Random Forest Classifier
Support vector Machine
Naive-Bayes
Voting Classifier
AdaBoost Classifier
GredientBoosting classifier
XGB Classifier
## **Model Evaluation** 
The performance of the selected model(s) will be assessed using appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and area under the receiver operating characteristic curve (AUC-ROC).

## **Cross-validation & Hyper Parameter Tuning:**
Hyperparameter tuning and cross-validation will be used to optimize model performance.

## **Interpretability** 
Interpretability techniques, such as feature importance analysis and SHAP (SHapley Additive exPlanations) values, will be applied to make the model's predictions more transparent and explainable to healthcare professionals and patients.

## **Expected Outcomes**

A highly accurate machine learning model for cardiovascular risk classification. Insights into the most influential factors contributing to cardiovascular risk. A user-friendly interface for healthcare practitioners to input patient data and receive risk assessments. Recommendations for personalized interventions to mitigate cardiovascular risk for individuals. Impact: This project has the potential to significantly impact public health by providing a tool that can assist healthcare professionals in identifying individuals at higher risk of cardiovascular diseases earlier. Early intervention and lifestyle changes can help reduce the burden of cardiovascular diseases on both individuals and healthcare systems.

## Ethical Considerations
Data privacy and ethical concerns related to healthcare data will be a top priority throughout the project. All data handling and model development will strictly adhere to legal and ethical standards, ensuring the confidentiality and security of patient information.

By leveraging the power of machine learning, this project aims to enhance cardiovascular risk assessment, ultimately contributing to better preventive care and improved health outcomes for individuals at risk of heart diseases.

# **Problem Statement**

Cardiovascular diseases (CVDs) continue to pose a significant global health challenge, and the need for effective risk assessment and prevention has become even more critical in the current healthcare landscape. With the advent of advanced data collection technologies and an increased focus on personalized medicine, there is an opportunity to enhance cardiovascular risk prediction using supervised machine learning classification.

# **Conclusion**

In this cardiovascular risk prediction project, we applied a 10 machine learning approach to classify patients into two different cardiovascular risk categories, considering the critical healthcare problem of imbalanced data.

Our primary focus was on maximizing recall, a crucial metric in healthcare, to minimize false negatives and ensure that individuals at risk of cardiovascular diseases are accurately identified.

Among the ten supervised machine learning classification algorithms evaluated, the Voting Classifier emerged as the top-performing model for our specific problem. It achieved an impressive recall of 0.71 and a test ROC-AUC of 0.70. This indicates its ability to effectively identify individuals at risk of cardio.The Adaboost classifier also demonstrated strong performance with a recall of 0.70 and a test ROC-AUC of 0.69. This algorithm's simplicity and effectiveness make it a noteworthy choice, particularly for scenarios where computational efficiency is a priority.vascular diseases, making it a valuable tool for healthcare practitioners.

Addressing the class imbalance in our dataset was crucial for model performance. We employed the Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic samples of the minority class, enhancing the classifier's ability to recognize individuals at higher risk. This strategy significantly contributed to the improved recall scores achieved by both the Voting Classifier and Adaboost classifier.

the most important features are age,education 3.0,cigs_per_day,education 2.0,pulse pressure,glucose,BMI,Total cholesterol,sex_M and education 4.0.
Prevalent_hype,heart rate,diabetes,prevalent stroke and bp_meds are very less important features.
