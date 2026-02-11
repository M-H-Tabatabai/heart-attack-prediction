# ❤️ Heart Attack Risk Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Best Accuracy](https://img.shields.io/badge/Best_Accuracy-93.44%25-brightgreen.svg)

> A comprehensive and visually appealing Machine Learning project to predict heart attack risk using clinical patient data. This repository benchmarks four major algorithms: **Decision Tree, KNN, Logistic Regression, and SVM**.

---

## 📌 Project Overview

This project aims to classify patients into **Low Risk** or **High Risk** of heart attack based on several medical attributes. It leverages supervised Machine Learning techniques and evaluates their performance using accuracy metrics.

**Dataset:** Kaggle Heart Disease Dataset
🔗 [https://www.kaggle.com/datasets/arezaei81/heartcsv](https://www.kaggle.com/datasets/arezaei81/heartcsv)

---

## 🧬 Dataset Features

The following clinical attributes are used for prediction:

| Feature  | Description                   |
| -------- | ----------------------------- |
| Age      | Age of the patient            |
| Sex      | Gender (1 = male, 0 = female) |
| cp       | Chest pain type               |
| trtbps   | Resting blood pressure        |
| chol     | Serum cholesterol             |
| fbs      | Fasting blood sugar           |
| rest_ecg | Resting ECG results           |
| thalach  | Maximum heart rate achieved   |
| exang    | Exercise induced angina       |
| ca       | Number of major vessels       |

---

## 🤖 Models Implemented

* ✔ Decision Tree Classifier
* ✔ K-Nearest Neighbors (KNN)
* ✔ Logistic Regression
* ✔ Support Vector Machine (SVM)

---

## 📊 Performance Leaderboard

Each model was evaluated using an 80/20 train-test split.

| Algorithm                        | Accuracy   | Best Use Case                    |
| -------------------------------- | ---------- | -------------------------------- |
| 🏆 **K-Nearest Neighbors (K=6)** | **93.44%** | Most accurate predictions        |
| Decision Tree                    | 88.52%     | High interpretability            |
| Support Vector Machine (RBF)     | 86.89%     | Robust in high-dimensional space |
| Logistic Regression              | 86.89%     | Probabilistic risk scoring       |

---

## 🔬 Methodology & Optimization

### 1️⃣ Data Preprocessing

* **Standardization:** Applied `StandardScaler` to normalize features such as Age and Cholesterol.
* **Data Type Optimization:** Converted numerical columns for improved stability.

### 2️⃣ Algorithm Tuning

* **KNN:** Tested K values from 2 to 10 → Best performance at **K = 6**.
* **SVM:** Compared different kernels → **RBF kernel** achieved best separation.
* **Logistic Regression:** Used `liblinear` solver with `C = 0.1` for balanced generalization.

---

## 🧠 Key Clinical Insights

* 🔍 **Neighborhood Effect:** KNN’s strong performance suggests patients with similar clinical profiles share similar risk patterns.
* 🧪 **Feature Importance:** The most influential predictors were:

  * Age
  * Sex
  * Maximum Heart Rate (thalach)

---

## 🛠 Technologies Used

* Python 🐍
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

---

## 🚀 Installation & Usage

```bash
# Clone repository
git clone https://github.com/your-username/heart-attack-prediction.git

# Install dependencies
pip install pandas numpy matplotlib scikit-learn

# Run notebooks
jupyter notebook
```

---

## 📁 Project Structure

```
heart-attack-prediction/
│
├── data/
│   └── heart.csv
├── notebooks/
│   ├── decision_tree.ipynb
│   ├── KNN.ipynb
│   ├── logistic_regression.ipynb
│   └── svm.ipynb
├── README.md
└── requirements.txt
```

---

## 📈 Future Work

* Add Deep Learning models (Neural Networks)
* Apply Cross-Validation
* Deploy as a web application (Streamlit or Flask)
* Include Explainable AI (SHAP, LIME)

---

## 👨‍💻 Author

Mohammad Hossein

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, please consider giving it a star on GitHub!
