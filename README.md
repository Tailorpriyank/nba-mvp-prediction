# 🤖 Classification Project: KNN vs Decision Tree

This project explores the performance of two popular classification algorithms — **K-Nearest Neighbors (KNN)** and **Decision Tree Classifier** — applied to a preprocessed dataset. The goal is to train both models, evaluate their accuracy, and compare their strengths in handling structured data.

---

## 📊 Project Overview

- **Domain**: Supervised Machine Learning – Classification
- **Techniques**: Data preprocessing, model training, hyperparameter tuning, confusion matrix evaluation
- **Algorithms Used**: K-Nearest Neighbors (KNN), Decision Tree Classifier
- **Tools**: Python, Pandas, NumPy, Matplotlib, Scikit-learn, Seaborn

---

## 📁 File

| File Name | Description |
|-----------|-------------|
| `P_Tailor_Final.ipynb` | Jupyter notebook implementing both KNN and Decision Tree classifiers with evaluation |

---

## 🔍 Key Steps

1. **Data Preprocessing**
   - Label encoding and feature scaling
   - Null value handling
2. **Train-Test Split**
   - 80:20 ratio using `train_test_split()`
3. **Modeling**
   - Trained and evaluated both KNN and Decision Tree
   - Used `confusion_matrix` and `classification_report` for evaluation
4. **Visualization**
   - Displayed confusion matrices for each model
5. **Comparison**
   - Compared accuracy, strengths, and weaknesses of each algorithm

---

## 🧠 Final Insights

- Decision Tree classifier performed better on this dataset with **higher accuracy and better interpretability**.
- KNN was simpler but more sensitive to scaling and noisy features.
- The exercise demonstrated how **different models behave under the same data pipeline**, highlighting the importance of model selection based on data context.

---

## 🛠️ How to Run

1. Clone this repo:
```bash
git clone https://github.com/Tailorpriyank/DAV_5400_Analytics-_Programing.git
