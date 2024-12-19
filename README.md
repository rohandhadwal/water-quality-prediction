# Water Quality Prediction  

## Overview  
This project focuses on predicting water quality using machine learning and data analysis techniques. The goal is to classify water samples as safe or unsafe based on chemical properties and contaminants, ensuring reliable and actionable insights for water quality monitoring. The dataset includes various numeric attributes representing chemical concentrations, with thresholds to determine potential health risks.  

By leveraging data preprocessing, exploratory data analysis (EDA), feature engineering (including polynomial feature generation), and hyperparameter optimization using Optuna, this project demonstrates a robust approach to predictive modeling.  

## Features  
- **Exploratory Data Analysis (EDA):**  
  Understand the distribution of features, visualize relationships between contaminants, and identify potential outliers in the data.  
- **Feature Engineering:**  
  Employ advanced techniques such as polynomial feature generation to capture non-linear relationships and enhance model performance.  
- **Modeling:**  
  Multiple classification algorithms were evaluated, including Support Vector Machines (SVC), Random Forest, and Logistic Regression. The best-performing model was identified based on metrics such as accuracy, F1 score, and AUC.  
- **Hyperparameter Optimization:**  
  Fine-tuned models using Optuna to maximize generalization performance on unseen data.  
- **Evaluation:**  
  Comprehensive evaluation metrics, including accuracy, F1 score, and AUC, were used to compare models and assess feature engineering's impact.  

## Dataset  
https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction 

The dataset consists of numeric attributes, each representing the concentration of various chemical contaminants in water. Specific thresholds are provided for each contaminant to determine its dangerous levels. For example:  
- **Aluminium:** Dangerous if > 2.8  
- **Ammonia:** Dangerous if > 32.5  
- **Arsenic:** Dangerous if > 0.01  
... and more (refer to the code for the complete list).


## Key Steps  
1. **Data Preprocessing:**  
   - Handling missing values.  
   - Normalizing and standardizing features to ensure consistency.  
2. **EDA:**  
   - Visualized correlations and distributions.  
   - Explored contaminant thresholds and their effects on water quality classification.  
3. **Feature Engineering:**  
   - Added polynomial features to enhance non-linear modeling.  
   - Evaluated the impact of feature engineering on test set performance.  
4. **Model Training and Evaluation:**  
   - Trained multiple models and compared their generalization performance.  
   - Optimized the best-performing model using Optuna for hyperparameter tuning.  

## Results  
The project achieved significant improvements in model performance through feature engineering and hyperparameter tuning. Key highlights:  
- The **Random Forest model** demonstrated superior generalization performance, achieving the highest AUC score and consistent F1 scores across datasets.  
- Feature engineering using polynomial features enhanced the ability of models to capture complex relationships in the data.  

## Author
Rohan Dhadwal
