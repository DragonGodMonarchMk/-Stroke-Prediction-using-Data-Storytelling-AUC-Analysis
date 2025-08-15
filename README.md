# -Stroke-Prediction-using-Data-Storytelling-AUC-Analysis
This project explores stroke prediction using a dataset of health indicators. Through EDA, feature engineering, and classification models, it emphasizes interpretability and AUC-based performance evaluation to deliver insights for healthcare decision-making.
# Stroke Prediction using Data Storytelling & AUC Analysis

## 📌 Overview
This project focuses on **predicting strokes** using health-related features such as age, hypertension, heart disease, and lifestyle factors.  
It leverages **data storytelling techniques** to communicate insights effectively and **AUC-focused evaluation** to measure predictive performance.

The goal is to provide a **clear, interpretable**, and **data-driven approach** for healthcare analytics and early stroke risk detection.

---

## 📂 Project Structure
├── data.csv # Dataset used for training and testing
├── data-storytelling-auc-focus-on-strokes.ipynb # Jupyter Notebook with full analysis
├── README.md # Project documentation
---

## 📊 Dataset Details
- **Source**: Provided dataset (`data.csv`)
- **Rows**: ~5,000 records
- **Columns**: Includes demographic, medical, and lifestyle attributes
- **Target Variable**: `stroke` (0 = No Stroke, 1 = Stroke)

**Key Features:**
- Age
- Gender
- Hypertension
- Heart disease
- Average glucose level
- BMI
- Smoking status

---

## 🧠 Methodology
1. **Data Cleaning & Preprocessing**
   - Missing value handling
   - Feature encoding
   - Outlier treatment
2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries
   - Visual storytelling for patterns
3. **Model Building**
   - Logistic Regression
   - Random Forest
   - XGBoost
4. **Performance Evaluation**
   - **AUC Score** as primary metric
   - Accuracy, Precision, Recall, and F1-Score
5. **Insights & Recommendations**
   - High-risk factor identification
   - Practical healthcare implications

---

## 📈 Results
- **Best Model**: [Insert model name after running notebook]
- **AUC Score**: [Insert score here]
- Feature importance analysis highlights **age**, **hypertension**, and **average glucose level** as top predictors.

---

## 🚀 Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/stroke-prediction-auc.git
cd stroke-prediction-auc

📌 Requirements
Python 3.8+
pandas
numpy
scikit-learn
matplotlib
seaborn
xgboost
jupyter

👤 Author
Manish Kumar Das
LinkedIn: www.linkedin.com/in/manishkumardas2002
GitHub: DragonGodMonarchMk

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

