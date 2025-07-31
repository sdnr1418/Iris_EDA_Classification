# 🌸 Iris Dataset - EDA & Logistic Regression Classification

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A deep dive into one of the most iconic datasets in machine learning!  
This project explores the **Iris flower dataset** using **Exploratory Data Analysis (EDA)** and builds a **Logistic Regression classifier**, culminating in an elegant **decision boundary** visualization.

> 🧠 *If you're new to machine learning, this notebook gives you an insightful and visual introduction to data patterns, class separability, and binary classification in just a few lines of code.*

---

## ✨ Key Highlights

- 📊 Rich visual EDA (histograms, violin plots, correlation heatmaps, etc.)
- 🌱 Feature selection and engineering for binary classification
- ⚙️ Trained **Logistic Regression** model to classify *Setosa vs Others*
- 📐 **Decision Boundary** plotted in 2D space
- 🧼 Clean, beginner-friendly Python & Jupyter code

---

## 🔍 Insights & Observations

✅ *Setosa* flowers are **clearly linearly separable** from the rest, especially when plotting:
- **PetalLength vs PetalWidth**: A striking distinction appears!
- **SepalWidth** shows outliers and less discriminative power.
- **Violin and boxplots** reveal Setosa's tight feature distribution.

📉 Logistic regression performed **exceptionally well** in separating Setosa due to its linear separability.

---

## 🧠 Logistic Regression Decision Boundary

We used `PetalLengthCm` and `PetalWidthCm` as 2D input features to visualize the **decision boundary** learned by the logistic regression model.

The boundary marks where the model is **uncertain (probability = 0.5)** — a classic concept in classification:



---

## 🖼️ Sample Visualizations


---

## 🛠️ How to Run

1. **Clone this repo:**

```bash
git clone https://github.com/your-username/iris-eda-classification.git
cd iris-eda-classification
