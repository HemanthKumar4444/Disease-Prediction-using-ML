# Disease Prediction using Machine Learning

This project is a Machine Learning-based system that predicts the most probable disease based on symptoms provided by a user. The system uses supervised learning models including Support Vector Machine (SVM), Gaussian Naive Bayes, and Random Forest classifiers. It enhances prediction accuracy by combining the outputs of these models using majority voting.


##  Dataset

The dataset used is `improved_disease_dataset.csv`, which contains:
- Binary indicators (0/1) for symptoms
- A categorical target column (`disease`) with disease names


## Features

-  Multi-model classification (SVM, Naive Bayes, Random Forest)
-  Class balancing using RandomOverSampler
-  Confusion matrices for performance visualization
-  Cross-validation with StratifiedKFold
-  Combined prediction using majority voting
-  Interactive prediction function based on user-input symptoms


## 🔧 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (RandomOverSampler)
- Matplotlib & Seaborn (visualization)
- Google Colab / Jupyter Notebook


## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/HemanthKumar4444/Disease-Prediction-using-ML.git
cd Disease-Prediction-using-ML
```

### Install Required Libraries
```
pip install -r requirements.txt
```

### 3. Open the Notebook
Use Jupyter Notebook or Google Colab:

Disease_Prediction.ipynb

Make sure to upload or place the dataset file:

improved_disease_dataset.csv
