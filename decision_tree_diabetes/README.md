# 🌳 Decision Tree Classifier – Pima Indians Diabetes Prediction

This project applies a **Decision Tree Classifier** to predict the onset of diabetes in female patients of Pima Indian heritage, using clinical diagnostic measurements.

The model was trained and evaluated using the publicly available **Pima Indians Diabetes Dataset**, sourced from the [UCI Machine Learning Repository](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

---

## 📄 Dataset

- **Total samples**: 768
- **Features used**: `pregnant`, `glucose`, `bp`, `skin`, `insulin`, `bmi`, `pedigree`, `age`
- **Target variable**: `label` (0 = no diabetes, 1 = diabetes)
- The dataset contains no missing values after loading.

---

## 🧪 Model Overview

The model is a basic **DecisionTreeClassifier** from `scikit-learn`. The data was split into **training and testing sets**, and the model was trained on the training set with default hyperparameters.

A confusion matrix and classification report were generated to evaluate performance, and the decision tree was visualized using `plot_tree()`.

---

## 📈 Results

- **Accuracy**: **0.76**
- **Precision (class 1 – diabetic)**: 0.72
- **Recall (class 1 – diabetic)**: 0.56
- **F1-score (class 1 – diabetic)**: 0.63

🔍 The model performs well in identifying non-diabetic patients but shows moderate recall on diabetic cases. This indicates a tendency to miss some true positives (i.e., patients with diabetes).

---

## 📊 Visualization

The decision tree was visualized using `matplotlib`, allowing inspection of the most significant splits in the dataset.

---

## 🛠️ Tools & Technologies

- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook

---

> ✍️ This notebook was developed and customized by **Manuel Villajos Ortega** as part of a personal data analytics portfolio.
