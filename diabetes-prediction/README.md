# Diabetes Prediction - KNN vs Logistic Regression

A machine learning project that predicts whether a patient has diabetes or not using the Pima Indians Diabetes dataset from Kaggle. I compared two models, KNN and Logistic Regression, to see which one performs better on this dataset.

---

## Dataset

Pima Indians Diabetes Database from Kaggle - 768 patients, 8 features, binary target (diabetic or not).

Download it here: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

---

## What I did

- Loaded and explored the dataset
- Replaced biologically impossible zero values with the column median
- Scaled the features using StandardScaler
- Trained KNN and Logistic Regression
- Compared both models using accuracy, confusion matrix and classification report

---

## Results

| Model               | Accuracy |
|---------------------|----------|
| KNN                 | ~75%     |
| Logistic Regression | ~78%     |

Logistic Regression performed better on this dataset. Glucose and BMI were the most correlated features with the outcome.

---

## How to run it

1. Clone the repo
```
git clone https://github.com/your-username/diabetes-prediction.git
cd diabetes-prediction
```

2. Install the requirements
```
pip install -r requirements.txt
```

3. Download the dataset from Kaggle and place diabetes.csv in the same folder as the notebook

4. Open the notebook
```
jupyter notebook diabetes_prediction.ipynb
```

---

## Libraries used

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
