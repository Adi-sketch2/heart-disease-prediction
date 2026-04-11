#  Heart Disease Prediction System (Machine Learning)

## 📌 Project Overview

This project predicts the presence of heart disease using Machine Learning techniques.
It uses patient medical data such as age, cholesterol, heart rate, etc., to classify whether a person is likely to have heart disease or not.

---

## 🎯 Objectives

* Build a classification model for heart disease prediction
* Compare multiple algorithms
* Improve model performance by reducing overfitting
* Analyze important medical features affecting predictions

---

## 📊 Dataset

* Contains medical attributes like:

  * Age
  * Sex
  * Chest Pain Type (cp)
  * Cholesterol (chol)
  * Maximum Heart Rate (thalach)
  * Number of vessels (ca)
  * Thalassemia (thal)
* Target:

  * `0 → No Disease`
  * `1 → Disease`

---

## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## 🤖 Machine Learning Models

1. Logistic Regression (Baseline Model)
2. Random Forest Classifier (Improved Model)

---

## 📈 Model Performance

| Model                         | Accuracy           |
| ----------------------------- | ------------------ |
| Logistic Regression           | ~80%               |
| Random Forest (Before Tuning) | ~99% (Overfitting) |
| Random Forest (After Tuning)  | ~88% ✅             |

---

## 🔍 Key Concepts Implemented

* Train-Test Split
* Model Training & Prediction
* Accuracy Evaluation
* Feature Importance Analysis
* Overfitting Detection & Reduction

---

## 🌳 Feature Importance Insights

Top important features:

* Thalassemia (thal)
* Number of vessels (ca)
* Chest Pain Type (cp)
* Maximum Heart Rate (thalach)
* Oldpeak

---

## 📊 Visualization

* Feature Importance Graph
* Logistic Regression Sigmoid Curve (Probability Visualization)

---

## 🚀 How to Run

```bash
pip install numpy pandas matplotlib scikit-learn
```

```bash
python main.py
```

---

## 💡 Future Improvements

* Add GUI interface
* Deploy as a web app
* Use advanced models (XGBoost, Neural Networks)

---

## 🧠 Conclusion

Random Forest performed better than Logistic Regression after tuning.
The project demonstrates how machine learning can be used in healthcare for prediction and decision support.

---

## 🙌 Author

**Aaditya Bhatt**
BCA (AI & Data Science) Student

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
