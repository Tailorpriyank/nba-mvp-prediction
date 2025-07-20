# NBA MVP Prediction Using Machine Learning

This project aims to predict the NBA's Most Valuable Player (MVP) using player performance data and MVP voting history. We developed a machine learning engine to analyze and rank the most impactful player statistics while testing different models for predictive accuracy.

## 👥 Team Members

- Aradhana Panchal  
- Priyank Tailor  
- Shruthi Kolluru

---

## 🎯 Project Objective

The primary goal is to build a predictive model that can accurately forecast NBA MVP winners using historical data and identify patterns and trends that influence MVP selection.

We investigated:
- Which player statistics most strongly influence MVP selection?
- Does team success (win/loss record, playoff position) impact MVP likelihood?
- Is there position bias (guard, forward, center) in MVP outcomes?
- Have MVP trends shifted over time?

---

## 📊 Data Sources

- **Player statistics & team performance:** Sports-Statistics CSV datasets  
- **MVP voting shares (2001–2021):** [Basketball-Reference](https://www.basketball-reference.com) via web scraping

We used:
- **BeautifulSoup (Python)** for scraping MVP voting data
- Cleaned, merged, and stored final data in a CSV format using Pandas

---

## 🔍 Research Methodology

### 1. Data Collection
- Collected CSV datasets of NBA players and teams from Sports-Statistics
- Scraped MVP voting share data (2001–2021) from Basketball-Reference using BeautifulSoup

### 2. Data Preparation
- Handled missing values, duplicates, and merged datasets
- Created a final DataFrame with all features and target variables
- Performed EDA and correlation analysis

### 3. Feature Selection
- Used correlation matrices and feature importance ranking
- Selected variables that most influenced MVP probability (e.g., PPG, Win%, PER)

### 4. Model Development
- Models used: **Logistic Regression, Random Forest, Support Vector Machine (SVM)**
- Dataset was split into train/test sets (e.g., 80/20 split)
- Hyperparameters were tuned for performance

### 5. Model Evaluation
- Metrics: **Accuracy, Precision, Recall, F1-score**
- Best performance:  
  ✅ **Logistic Regression**  
  📈 **Accuracy:** 98.33%  
  📊 **F1-Score:** 0.8571

---

## ⚙️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Scikit-learn  
- BeautifulSoup  
- Jupyter Notebook  
- Matplotlib, Seaborn

---

## 📈 Results & Insights

- Player stats like PPG (points per game), team win %, and PER were strong predictors.
- Logistic Regression gave the highest prediction accuracy and F1 score.
- Historical MVP patterns suggest a slight bias towards certain positions and team records.
- The approach is scalable for real-time season predictions or sports betting models.

---

## 📂 File Structure
├── data/                # Raw and cleaned datasets
├── notebooks/           # Jupyter notebooks for EDA and modeling
├── scraping/            # Web scraping scripts (BeautifulSoup)
├── models/              # Trained models and evaluation outputs
├── final_df.csv         # Final combined dataset
└── README.md            # Project documentation

---

## 📌 Conclusion

This project demonstrates the feasibility of using machine learning to predict MVP winners with high accuracy. Beyond sports fandom, such insights can aid team strategies, fantasy leagues, and analytics-driven decision-making in professional sports.

---

## 📬 Contact

Feel free to connect:  
**Priyank Tailor** — [LinkedIn](https://www.linkedin.com/in/tailorpriyank/)  
GitHub Repo: [nba-mvp-prediction](https://github.com/Tailorpriyank/nba-mvp-prediction)
