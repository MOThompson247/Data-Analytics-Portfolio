# CharityML Donor Prediction Project Summary

The machine learning project focuses on predicting whether individuals make more than $50,000, a crucial task for identifying potential donors for CharityML. The project follows a structured approach:

1. **Data Exploration:** Explore the census dataset, examining features like age, education, and occupation.

2. **Data Preprocessing:** Prepare data by handling missing values, encoding categorical features, and scaling numerical features.

3. **Model Selection:** Choose three supervised learning models (Random Forest, Gradient Boosting, Logistic Regression) for evaluation.

4. **Initial Model Evaluation:** Train and assess models on different sample sizes, evaluating performance using accuracy and F-score.

5. **Model Comparison:** Compare models based on metrics, prediction/training time, and suitability for the data.

6. **Model Tuning:** Optimize the best model (Gradient Boosting) using grid search to improve F-score by tuning hyperparameters.

7. **Final Model Evaluation:** Assess the optimized model's accuracy and F-score on testing data, comparing with naive predictor benchmarks.

8. **Feature Importance:** Identify top five features crucial for predicting income levels using a feature importance analysis.

9. **Feature Selection:** Evaluate the impact of using only the top five features on model performance, comparing accuracy and F-score.

The final recommendation is to use the optimized Gradient Boosting model for predicting potential donors, considering its higher accuracy and F-score on testing data. Insights into feature importance provide valuable information about key predictors.

