# Iris-Flower-Classification
Iris Flower Classification project built in Google Colab using Scikit-learn. Trains and evaluates multiple ML models (Logistic Regression, KNN, Decision Tree, SVM) to classify Iris species (Setosa, Versicolor, Virginica) with visualization and performance comparison.

# 📌 Project Description — Iris Flower Classification 🌸

This project implements Iris Flower Classification using Scikit-learn in Google Colab.
The classic Iris dataset (150 samples, 3 classes) is used to build and evaluate machine learning models that predict the flower species (Setosa, Versicolor, Virginica) from sepal and petal measurements.

# 🔑 Key Features

Clean, annotated Google Colab notebook for end-to-end workflow

Exploratory Data Analysis (EDA) with visualizations

Supervised ML models: Logistic Regression, KNN, Decision Tree, and SVM

Model evaluation using accuracy, confusion matrix, and classification report

Easy to reproduce — runs fully in Google Colab with no setup needed

# 🎯 Applications

Introductory project for machine learning beginners

Demonstrates classification pipeline from raw data to evaluation

Template for small dataset classification problems

# 🌸 Iris Flower Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your_github_username/iris-flower-classification/blob/main/notebook/iris_classification.ipynb)

This project builds a **machine learning classifier** to predict Iris flower species (*Setosa, Versicolor, Virginica*) based on sepal and petal dimensions.  
It is fully developed and deployed in **Google Colab** for easy reproducibility.

👉 **Project Description:** See [docs/DESCRIPTION.md](docs/DESCRIPTION.md)

---

## 🚀 Features
- Clean and annotated Google Colab notebook
- Uses **Scikit-learn** for model training
- Models: Logistic Regression, Decision Tree, KNN, and SVM
- Evaluation with accuracy, confusion matrix, and classification report
- Easy to run with no local setup required

---

## 📂 Project Structure

iris-flower-classification/

├─ notebook/

│ └─ iris_classification.ipynb

├─ docs/

│ └─ DESCRIPTION.md

├─ README.md

├─ requirements.txt

└─ .gitignore


---

## 📊 Dataset
We use the **classic Iris dataset** (150 samples, 3 classes) provided by Scikit-learn.  
No need to download externally — it’s loaded directly via `sklearn.datasets.load_iris`.

---

## ⚡ How to Run

1. Open the notebook in Colab:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1e1MLMozaCmEtWbKNNvrXQZ1LgiIc4Ogt?usp=sharing)

2. Install dependencies (if running locally):
   ```bash
   pip install -r requirements.txt

   
---

# 📝 3. docs/DESCRIPTION.md

```markdown
# Project Description — Iris Flower Classification 🌸

The Iris dataset is one of the most famous datasets in pattern recognition and machine learning.  
This project uses **supervised learning models** to classify Iris flowers into three species:

- Setosa  
- Versicolor  
- Virginica  

## Workflow
1. Load dataset using Scikit-learn
2. Perform exploratory data analysis (EDA)
3. Split data into training and testing sets
4. Train ML models (Logistic Regression, KNN, Decision Tree, SVM)
5. Evaluate with accuracy, confusion matrix, and classification report
6. Compare results and choose the best model

## Applications
- Educational project for ML beginners
- Demonstrates end-to-end supervised classification
- Template for small dataset classification tasks

# 🗂️ 4. requirements.txt
numpy
pandas
matplotlib
seaborn
scikit-learn

# 🚫 5. .gitignore
__pycache__/
*.csv
*.pkl
*.joblib
*.env
.DS_Store

