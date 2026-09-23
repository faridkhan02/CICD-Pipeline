# 🚀 CI/CD Pipeline for Machine Learning

A complete **CI/CD pipeline for a Machine Learning project** using **Python, Scikit-learn, and GitHub Actions**.

This project demonstrates how to automate the machine learning model training process using GitHub Actions whenever changes are pushed to the repository.

---

## 📌 Project Overview

This project implements an automated Machine Learning workflow using the **Iris dataset**.

The pipeline performs the following tasks:

1. 📥 Loads the Iris dataset
2. 🧹 Prepares the data
3. ✂️ Splits the dataset into training and testing sets
4. 🤖 Trains a Machine Learning classification model
5. 📊 Evaluates the model
6. 📈 Generates a confusion matrix
7. ⚙️ Automates the workflow using GitHub Actions

---

## 🛠️ Technologies Used

- 🐍 Python
- 🤖 Scikit-learn
- 🐼 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🔄 GitHub Actions
- 🌐 Git & GitHub

---

## 📂 Project Structure

```text
CICD-Pipeline/
│
├── .github/
│   └── workflows/
│       └── ml-pipeline.yml
│
├── ConfusionMatrix.png
├── iris.csv
├── requirements.txt
├── train_model.py
└── README.md
