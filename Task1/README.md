# `Titanic Survival Prediction` - Data Science Project

## `1. Project Overview`
This project aims to predict survival outcomes for Titanic passengers using machine learning models. The dataset comprises diverse passenger information, and our goal is to develop accurate models for survival prediction.

![Titanic Ship](https://images.nationalgeographic.org/image/upload/t_edhub_resource_key_image/v1638882458/EducationHub/photos/titanic-sinking.jpg)

## `2. Business Understanding`
Understand the problem, define objectives, and establish the significance of predicting survival on the Titanic. 

## `3. Data Collection`
Utilized the Titanic dataset, which includes information about passengers' demographics and their survival status.

## `4. Data Exploration and Analysis`
Explored dataset characteristics, identified missing values, and examined feature distributions. Conducted visualizations to understand relationships between key features.

## `5. Feature Engineering`
Handled missing data, converted categorical variables, and extracted additional information from existing features to enhance predictive capabilities.

## 6. `Exploratory Data Analysis (EDA)`
Analyzed survival patterns based on passenger attributes. Visualized insights through charts and graphs.

## `7. Modeling`
### 7.1 Train-Test Split
Separated features (X) and the target variable (y). Split the data into training and testing sets using an 80-20 ratio.

### 7.2 Baseline Model - Random Forest Classifier
- Achieved perfect accuracy (1.00) on the test set.
- Cross-validation scores indicated potential overfitting.

### 7.3 Logistic Regression
- Achieved perfect accuracy (1.00) on the test set.

### 7.4 Decision Tree Classifier
- Achieved perfect accuracy (1.00) on the test set.
- Consistent cross-validation scores demonstrated robust performance.

### 7.5 Support Vector Machine (SVM) Classifier
- Achieved moderate accuracy (0.60) on the test set.
- Cross-validation scores suggested moderate performance.

### 7.6 K-Nearest Neighbors (KNN) Classifier
- Achieved good accuracy (0.79) on the test set.
- Consistent cross-validation scores indicated reliable performance.

## `8. Model Evaluation`
Compared model performances based on accuracy and AUC. Random Forest, Logistic Regression, and Decision Tree models exhibited exceptional accuracy and AUC scores. SVM model showed perfect AUC but lower accuracy. KNN model demonstrated good accuracy and a respectable AUC score.

## `9. Conclusion and Recommendations`
Successfully addressed the project's goal of predicting survival on the Titanic. Recommendations include continuous monitoring, feature expansion, ensemble strategies, and considerations for interpretability.

## 10. Next Steps
- Deployment priorities and considerations.
- Continuous learning and model validation against new datasets.
