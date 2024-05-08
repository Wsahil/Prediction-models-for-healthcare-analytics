# Predictive Modeling for Smoking and Drinking Trends
This project aimed to leverage machine learning techniques to predict smoking and drinking behaviors based on health metrics and personal data. By analyzing a comprehensive dataset obtained from the Korean National Health Insurance Service, the project sought to uncover underlying patterns and trends influencing these lifestyle choices.

## Project Overview

- **Dataset**: Smoking and Drinking Dataset with Body Signal (Kaggle), containing 991,346 rows and 24 columns of health metrics and personal information. 
https://www.kaggle.com/datasets/sooyoungher/smoking-drinking-dataset/data
![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/952089b8-7298-42c8-be10-6b2d31a3653b)

- **Technologies Used**: Python (NumPy, Pandas, Scikit-learn, Seaborn, Matplotlib, PySpark), Machine Learning Algorithms (Logistic Regression, Decision Trees, Random Forest, SVM, Gradient Boosting)
- **Key Objectives**:
  - Conduct exploratory data analysis (EDA) to gain insights and guide feature selection.
  - Develop predictive models for smoking and drinking behaviors using machine learning algorithms.
  - Optimize model performance through cross-validation and hyperparameter tuning.
  - Leverage distributed computing with PySpark to handle large datasets efficiently.

## Project Implementation

1. **Exploratory Data Analysis (EDA)**: Performed detailed EDA using Seaborn, Matplotlib, and Z-score analysis to reveal patterns, correlations, and identify outliers. Key findings included the influence of age, gender, and health metrics like hemoglobin on smoking and drinking habits.
![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/d1e06efc-2f97-44bd-beca-bc23c7c6e19e) ![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/25bcbc3c-e710-46e3-9067-558baa0927cf)

![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/216a23c2-5fda-43d4-a7a1-436b870ea4cc) ![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/69a07a57-a1fd-4a8d-ab50-ed2172945f83)

2. **Data Preprocessing**: Handled missing values, vectorized numerical features, scaled the features, and indexed categorical variables to prepare the data for modeling.

3. **Model Development**: Employed five machine learning algorithms (Logistic Regression, Decision Trees, Random Forest, SVM, and Gradient Boosting) to construct predictive models for smoking and drinking behavior. Cross-validation and hyperparameter tuning were applied to optimize model performance.

4. **Distributed Computing (PySpark)**: Utilized PySpark for distributed computing on the large dataset, enabling efficient processing and analysis.


## Key Findings and Results

- **Smoking Behavior Prediction**:
  - Best performing model: Decision Tree (Accuracy: 68%)
  - Hemoglobin identified as a crucial feature for classifying smoking behavior.
![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/db3b430f-56f0-410f-b48e-3bbf31c8868c)

- **Drinking Behavior Prediction**:
  - Best performing model: Logistic Regression (Accuracy: 77%)
![image](https://github.com/Wsahil/Prediction-models-for-healthcare-analytics/assets/71370836/5342b6e4-eef8-46ce-8683-cfa8366d0ab8)

- **Model Interpretability**: Feature importance graphs from Decision Tree and Random Forest models highlighted the significance of features like gamma-GTP, hemoglobin, and age in predicting drinking behavior.

- **Insights for Healthcare and Insurance**: The project's findings and predictive models can assist insurance companies and health management organizations in making informed decisions, optimizing health interventions, and improving business outcomes.


## Conclusion

By combining machine learning techniques, advanced data analysis, and distributed computing, this project successfully developed predictive models for smoking and drinking behaviors. The insights gained from this project can contribute to informed decision-making in the healthcare and insurance industries, enabling targeted interventions, awareness campaigns, and personalized healthcare strategies.
