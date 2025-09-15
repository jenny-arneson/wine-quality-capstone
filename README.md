# 🍷 Wine Quality Prediction – Capstone Project

This capstone project explores the use of machine learning models to predict the quality of red and white wines based on physicochemical characteristics.  
The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).  

---

## 🧠 Objective
Develop a predictive model that estimates wine quality (score from 0–10) using features such as acidity, sugar content, pH, alcohol, and more.

---

## 📊 Dataset
- **Original dataset:** `wine_quality.csv`  
- **Cleaned version:** `wine_quality_cleaned.csv`  
- **Sample provided:** `sample_wine_quality.csv` (100 rows for quick testing)  
- Source: [UCI ML Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)  

---

## 🔧 Methods Used
- Exploratory Data Analysis (EDA)  
- Data Cleaning & Preprocessing  
- Feature Engineering  
- Correlation Analysis  
- Model Training:  
  - Logistic Regression  
  - Decision Trees  
  - Random Forest  
  - XGBoost  
- Model Evaluation (Accuracy, Precision, Recall, F1)  

---

## 🛠️ Tools & Libraries
- **Python:** pandas, NumPy, matplotlib, seaborn, scikit-learn, XGBoost  
- **Notebook:** Jupyter Notebook  
- **Collaboration:** Git, GitHub, GitHub Actions (CI/CD)  

---

## ✅ Results
- Best model: **Random Forest Classifier**  
- Achieved an accuracy of ~78% on the test set  
- Alcohol, volatile acidity, and sulphates were among the most influential features  

📌 **Feature importance (Random Forest):**  
![Feature Importance](images/feature_importance.png)  

📌 **Confusion matrix (Random Forest):**  
![Confusion Matrix](images/confusion_matrix.png)  

---

## 📂 Repository Structure
wine-quality-capstone/
├─ notebooks/
│  └─ Wine_Quality_Capstone.ipynb
├─ src/
│  ├─ data_prep.py
│  ├─ train.py
│  └─ utils.py
├─ data/
│  ├─ sample_wine_quality.csv   # 100-row sample for quick testing
│  ├─ wine_quality.csv          # Original dataset
│  └─ wine_quality_cleaned.csv  # Cleaned dataset
├─ images/
│  ├─ feature_importance.png
│  ├─ confusion_matrix.png
│  └─ wine_quality_distribution.png
├─ requirements.txt
└─ README.md

---

## 🚀 How to Run Locally
```bash
# Clone repo
git clone https://github.com/jenny-arneson/wine-quality-capstone.git
cd wine-quality-capstone

# Create environment & install dependencies
python -m venv .venv
source .venv/bin/activate     # Windows: .venv\Scripts\activate
pip install -r requirements.txt

# Launch notebook
jupyter notebook notebooks/Wine_Quality_Capstone.ipynb