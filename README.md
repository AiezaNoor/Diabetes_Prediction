# Diabetes_Prediction
**Project Overview**

This project focuses on developing an accurate diabetes prediction system using machine learning techniques. Diabetes is a chronic disease affecting millions worldwide, and early detection is crucial for effective management. The project addresses the challenge of imbalanced datasets in medical diagnostics by employing SMOTE (Synthetic Minority Oversampling Technique) and evaluates various ensemble learning models to achieve optimal prediction performance.

**Key Features**

- Dataset: Uses a comprehensive diabetes prediction dataset from Kaggle containing 100,000 patient records with 9 features including age, BMI, HbA1c levels, and blood glucose levels.
- Data Preprocessing: Includes feature scaling, categorical encoding, and SMOTE for handling class imbalance (91,500 non-diabetic vs 8,500 diabetic cases).
- Models: Evaluates multiple machine learning algorithms including:
Random Forest

Logistic Regression

Gradient Boosting

XGBoost

CatBoost (best performing model)

- Performance Metrics: Models evaluated on accuracy, precision, recall, and F1-score.

**Results**
- CatBoost achieved the highest accuracy of 97.07% after SMOTE application
- Significant improvement in minority class (diabetic) recall after balancing
- Comparative analysis shows ensemble methods outperform traditional models
- Full performance metrics available in the paper
  
**Dependencies**
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, imbalanced-learn, catboost, xgboost
- Visualization: matplotlib, seaborn

**Future Work**
- Deployment as a web application for clinical use
- Integration with electronic health record systems
- Expansion to predict diabetes complications
- Exploration of deep learning approaches

**Acknowledgments**
- Co-authors: Aqdas Bibi and Sohail Afridi
- Dataset source: Kaggle Diabetes Prediction Dataset
- Research guidance from FAST NUCES Islamabad
