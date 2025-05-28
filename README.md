# Wine Quality Prediction – Capstone Project

This capstone project explores the use of machine learning models to predict the quality of red and white wines based on physicochemical characteristics. The dataset is sourced from the UCI Machine Learning Repository.

## 🧠 Objective

To develop a predictive model that estimates wine quality (score from 0–10) using features such as acidity, sugar content, pH, alcohol, and more.

## 📊 Dataset

- **Original dataset:** `wine_quality.csv`
- **Cleaned version:** `wine_quality_cleaned.csv`
- Source: [UCI ML Repository – Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)

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

## 🧰 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)
- Jupyter Notebook

## ✅ Results

- Best model: **Random Forest Classifier**
- Achieved an accuracy of ~78% on the test set
- Alcohol, volatile acidity, and sulphates were among the most influential features

## 📁 File Structure
wine-quality-capstone/
├── Capstone Projectipynb.ipynb  # Main analysis and modeling notebook
├── wine_quality.csv             # Raw dataset
├── wine_quality_cleaned.csv     # Cleaned dataset used for modeling
├── README.md                    # Project documentation (this file)

## 📌 Key Takeaways

- Feature engineering and model tuning significantly improved model performance.
- Alcohol content is a strong predictor of wine quality.
- Ensemble methods (Random Forest, XGBoost) outperformed simple classifiers.

---

## 🙋‍♀️ About Me

Jennifer Arneson | Data Scientist  
🔗 [LinkedIn](https://linkedin.com/in/jenniferraearneson)  
📬 jarneson55@gmail.com

---

## 📌 Next Steps

- Deploy model using Streamlit or Flask (coming soon!)
- Explore additional datasets to combine with wine reviews
