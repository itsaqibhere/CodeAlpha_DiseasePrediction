# 🏥 Disease Prediction from Medical Data
### CodeAlpha Machine Learning Internship — Task 

## 📌 Overview
A machine learning project that predicts whether a patient has diabetes
based on medical features like glucose level, BMI, age, and insulin.
Four classification algorithms are trained and compared to find the
best performing model.

## 📂 Dataset
- **Name:** Pima Indians Diabetes Dataset
- **Source:** UCI Machine Learning Repository / Kaggle
- **Size:** 768 patients, 8 features + 1 target
- **Target:** Outcome (0 = No Diabetes, 1 = Diabetes)

## ⚙️ Features Used
| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Blood glucose level |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Tricep skin fold thickness |
| Insulin | 2-hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Genetic/family history score |
| Age | Age of patient |

## 🤖 Models Trained
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score

## 📈 Visualizations Generated
- Class distribution pie chart
- Feature distributions by outcome
- Correlation heatmap
- Confusion matrices for all 4 models
- ROC curves comparison
- Model metrics bar chart
- Feature importance (Random Forest)

## 🛠️ Tech Stack
- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 🚀 How to Run
1. Clone the repository
   git clone https://github.com/itsaqibhere/CodeAlpha_DiseasePrediction.git

2. Install dependencies
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost

3. Add diabetes.csv to the project folder

4. Open and run the notebook
   jupyter notebook disease_prediction.ipynb

## 📁 Project Structure
CodeAlpha_DiseasePrediction/
│
├── disease_prediction.ipynb   # Main notebook
├── diabetes.csv               # Dataset
├── README.md                  # Project documentation
└── outputs/                   # Generated graphs
    ├── class_distribution.png
    ├── feature_distributions.png
    ├── correlation_heatmap.png
    ├── confusion_matrices.png
    ├── roc_curves.png
    ├── metrics_comparison.png
    └── feature_importance.png

## 🏆 Results
Best performing model selected based on ROC-AUC score.
Glucose and BMI identified as the most important predictors of diabetes.

## 👨‍💻 Author
**Aqib Anwar**
Machine Learning Intern — CodeAlpha
[LinkedIn](https://www.linkedin.com/in/aqib-anwar-4b1768300/)
[GitHub](https://github.com/itsaqibhere)
