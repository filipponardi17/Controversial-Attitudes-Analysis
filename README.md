# Introduction

This research project explores societal attitudes towards divisive topics like abortion, same-sex marriage, and immigration, focusing on their correlation with demographic characteristics such as age, gender, education, income, and cultural background. Utilizing data from the World Values Survey, we apply both exploratory techniques, including Latent Class Analysis and Factor Analysis, and predictive models like Support Vector Machines and Random Forest, to uncover patterns and predict attitudes.

## Methodology

### Data Collection
- **Source:** Joint European/World Values Survey (EVS-WVS) 2017-2020.
- **Focus:** Data from Germany, France, Spain, and Italy.
- **Data Points:** Responses to questions on controversial issues, supplemented with demographic information.

### Data Preprocessing
- **Cleaning:** Handling of missing data through imputation methods like Predictive Mean Matching.
- **Feature Engineering:** Construction of a binary target variable based on attitudes towards abortion, homosexuality, and immigration.

### Exploratory Analysis
- **Latent Class Analysis (LCA):** Identification of subpopulations within the dataset to discern distinct groups based on their attitudes.
- **Principal Component Analysis (PCA):** Reduction of dimensionality to discover influential variables.
- **Factor Analysis:** Investigation of underlying factors that explain correlations among variables, aiding in understanding complex data structures.

## Predictive Analysis

### Algorithms Used:
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM) with different kernels (Polynomial, RBF, Linear)
- Gradient Boosting
- Logistic Regression

### Model Optimization:
- Hyperparameter tuning using grid search with cross-validation to enhance model performance.

### Evaluation Metrics:
- AUC, accuracy, sensitivity, specificity, precision, and F1 score.

## Results

The analysis revealed key insights into how demographic factors influence attitudes towards controversial issues. Distinct subpopulations were identified, highlighting differences in views shaped by various demographic traits. Feature importance analysis pointed to moral and ethical judgments as significant predictors of attitudes. The predictive models demonstrated effectiveness in distinguishing between controversial and non-controversial attitudes, with Random Forest and Logistic Regression showing robust performance across multiple metrics.

## Conclusion

This study underscores the complex interplay of demographic characteristics in shaping societal attitudes towards controversial topics. 
