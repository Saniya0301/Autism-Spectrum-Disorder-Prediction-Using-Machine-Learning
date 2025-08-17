# Autism Spectrum Disorder Prediction Using Machine Learning

## Overview
This project uses machine learning techniques to analyze behavioral patterns and predict Autism Spectrum Disorder (ASD) with high accuracy. The model leverages Python and popular ML libraries to preprocess the dataset, engineer features, train classification models, and evaluate performance.

## Features
- Data preprocessing including handling missing values and encoding categorical variables
- Feature engineering and outlier detection with IQR method
- Imbalanced dataset handling using SMOTE oversampling technique
- Model training with Decision Tree, Random Forest, and XGBoost classifiers
- Model evaluation using accuracy, confusion matrix, and cross-validation scores
- Hyperparameter tuning for improved model performance

## Dataset
The dataset used for this project is available on Kaggle:  
https://www.kaggle.com/datasets/shivamshinde123/autismprediction

---

## How It Works
- Data is loaded and cleaned by replacing missing or inconsistent values.
- Categorical data is encoded with label encoding.
- Outliers in numerical features are replaced using median values calculated via the IQR method.
- The SMOTE algorithm is applied to address class imbalance in training data.
- Multiple classifiers are trained and evaluated using cross-validation.
- Hyperparameter tuning is done for optimized model accuracy.

## Results
- Decision Tree Classifier achieved around 86% accuracy.
- Random Forest Classifier achieved around 92% accuracy.
- XGBoost Classifier achieved around 90% accuracy.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for bug fixes, enhancements, or new features.

## Acknowledgments
- The dataset provider: Shivam Shinde on Kaggle
- Libraries used: Scikit-learn, XGBoost, Imbalanced-learn, Pandas, NumPy, Seaborn, Matplotlib

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, please contact:  
SANIYA CHHABRA 

