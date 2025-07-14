# Titanic Survival Prediction using Logistic Regression

This project predicts passenger survival on the Titanic using Logistic Regression with different penalty options (L1, L2, ElasticNet, None). Hyperparameter tuning is performed using GridSearchCV. Data preprocessing includes feature scaling, label encoding, and the modeling pipeline.

## 📌 Project Description

The goal is to classify whether a passenger survived the Titanic disaster based on various features such as age, sex, ticket class, and fare. Different logistic regression penalties and hyperparameters are explored to optimize model performance. Data is preprocessed with encoding categorical features and scaling numeric features, all integrated into a scikit-learn pipeline.

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn

## 📈 Models and Tools Used

- **Logistic Regression** with penalties: L1, L2, ElasticNet, None  
- **GridSearchCV** for hyperparameter tuning  
- **LabelEncoder** for encoding categorical variables  
- **train_test_split** for dataset splitting  
- **Pipeline** for combining preprocessing and modeling steps  
- Feature scaling with **StandardScaler**

## 🧪 Evaluation Metrics

- Accuracy Score  
- Precision, Recall, F1-Score  
- Confusion Matrix  
- Cross-validation results  
- Best hyperparameters from GridSearchCV  

## 📂 Dataset

- From Kaggle: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
