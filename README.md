# Naive-Bayes-Car-Evaluation

This repository contains a **Naive Bayes Classifier** implementation on the **Car Evaluation dataset** using Python and `scikit-learn` to predict car acceptability based on categorical attributes like buying price, maintenance cost, number of doors, capacity, luggage boot size, and safety.

---

## 🤖 What is Naive Bayes?

**Naive Bayes** is a simple yet powerful **probabilistic classifier** based on Bayes' theorem:
\[
P(y|X) = \frac{P(X|y) P(y)}{P(X)}
\]
It assumes **feature independence** and is:
- Fast and efficient for classification tasks.
- Particularly effective for **categorical data and multiclass problems**.

---

## 🚀 Features

✅ Loads **Car Evaluation dataset** and assigns clear column names.  
✅ Encodes categorical data into numerical labels using **Label Encoding**.  
✅ Splits the dataset into **training and testing sets (70%-30%)**.  
✅ Trains a **Gaussian Naive Bayes Classifier** to predict car acceptability classes.  
✅ Evaluates the model using:
- **Classification report (precision, recall, f1-score)**
- **Accuracy score (%)**

---

## 🗂️ Dataset

The **Car Evaluation dataset** contains:
- **Features:**
  - Buying price
  - Maintenance cost
  - Number of doors
  - Persons capacity
  - Luggage boot size
  - Safety
- **Target:**
  - Car acceptability (`unacc`, `acc`, `good`, `vgood`)

The dataset is converted into numerical format using `LabelEncoder` to prepare it for the classifier.

---

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies using:
```bash
pip install pandas numpy scikit-learn
