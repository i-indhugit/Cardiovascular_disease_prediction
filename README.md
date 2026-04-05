# ❤️ Cardiovascular Disease Prediction using Machine Learning

## 📌 Overview

Cardiovascular disease (CVD) is one of the leading causes of death worldwide. Early detection and analysis of risk factors such as age, blood pressure, cholesterol, and lifestyle habits can significantly reduce mortality.

This project uses **Machine Learning techniques** to:

* Analyze cardiovascular health data
* Identify hidden patterns using clustering
* Predict heart disease using classification models

---

## 🎯 Objectives

* Perform data preprocessing and cleaning
* Analyze feature relationships using visualization
* Apply **K-Means Clustering** to group patients
* Build and evaluate multiple ML models
* Compare performance and identify the best model

---

## 📂 Dataset

The dataset contains medical attributes of patients such as:

* Age (converted from days to years)
* Gender
* Height & Weight
* Blood Pressure (ap_hi, ap_lo)
* Cholesterol & Glucose levels
* Lifestyle factors (smoking, alcohol, activity)
* Target variable: `cardio` (0 = No disease, 1 = Disease)

---

## 🧹 Data Preprocessing

* Converted age from days to years
* Removed irrelevant feature (`id`)
* Handled missing values using mean imputation
* Removed outliers in blood pressure values
* Standardized features using **StandardScaler**

---

## 📊 Exploratory Data Analysis

* Correlation heatmap to identify relationships
* Distribution plots for key features
* Blood pressure and cholesterol analysis
* Insights:

  * Higher cholesterol → higher disease risk
  * Higher blood pressure → strong correlation
  * Age increases risk

---

## 🔍 Feature Selection

* Selected relevant features based on correlation and domain knowledge
* Removed redundant or less impactful attributes

---

## 🤖 Machine Learning Models

### 🔹 Unsupervised Learning

**K-Means Clustering**

* Used to group patients into clusters
* Elbow method used to determine optimal K
* PCA used for 2D visualization

### 🔹 Supervised Learning Models

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest

---

## 📉 Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Model Comparison Graph

---

## 📊 Results

* Random Forest and SVM achieved the highest accuracy
* K-Means clustering identified:

  * Low-risk group
  * Medium-risk group
  * High-risk group

---

## 🧠 Key Insights

* Blood pressure and cholesterol are major indicators
* Lifestyle factors significantly influence risk
* Clustering helps identify patient categories even without labels

---

## 🏁 Conclusion

This project demonstrates how machine learning can assist in early detection of cardiovascular disease. Combining clustering and classification provides both **insightful analysis** and **accurate prediction**, making it useful for healthcare applications.

---

## 🚀 Future Work

* Deploy as a web application
* Integrate real-time health data
* Improve accuracy using deep learning
* Add explainable AI for medical interpretation

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Google Colab

---

## 📎 How to Run

1. Upload dataset to Google Colab
2. Run the notebook step by step
3. View outputs and visualizations

---

## 👩‍💻 Author

**Indhu Priya**
Computer Science Student

---

## ⭐ Acknowledgment

Dataset and problem inspired by cardiovascular disease research and machine learning applications in healthcare.
