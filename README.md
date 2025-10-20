# Extraalearn Data Science Project
## 🧭 Overview
This project focuses on predicting the likelihood of a lead converting into a paying customer for **ExtraaLearn**, an online education platform.  
Using data-driven insights and machine learning, the goal is to help the company identify which factors — such as occupation, marketing channels, and user engagement — most influence lead conversion.

---

## 📊 Objectives
- Analyze lead behavior and engagement through **exploratory data analysis (EDA)**  
- Identify key features that influence conversion outcomes  
- Build and tune a **Random Forest Classifier** to predict lead conversion probability  
- Provide **actionable insights and recommendations** to improve marketing efficiency  

---

## 🧩 Dataset
The dataset (`ExtraaLearn.csv`) includes lead-level information such as:
- Demographics (age, occupation, etc.)  
- Source of first interaction (digital, print, referral, etc.)  
- Profile completeness and engagement activity  
- Lead conversion status (target variable)

**Size:** ~4,000+ records  
**Type:** Mixed categorical and numerical  

---

## ⚙️ Data Preprocessing
- Handled missing values and inconsistent categorical entries  
- Encoded multi-category and binary variables  
- Created new features (e.g., number of channels engaged, profile completeness score)  
- Split data into training and testing sets for model validation  

---

## 🧠 Modeling Approach
- **Model Used:** Random Forest Classifier  
- **Tuning:** `GridSearchCV` and `RandomizedSearchCV` for optimal parameters  
- **Key Parameters Tuned:**
  - `n_estimators`, `max_depth`, `min_samples_leaf`, `max_features`, `ccp_alpha`
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix

**Final Model Accuracy:** ~86%  
**Observation:** Slight overfitting on training data → mitigated with parameter tuning and pruning (`ccp_alpha`).

---

## 📈 Key Insights
1. **Occupation** strongly influences conversion — working professionals and self-employed users are more likely to enroll.  
2. **Referral** and **digital marketing channels** show higher conversion rates than print media.  
3. Leads with **more complete profiles** have significantly higher conversion probabilities.  
4. **First interaction channel** plays a key role — early impressions matter.  

---

## 🚀 Recommendations
- Prioritize **referral and digital campaigns** for better ROI.  
- Target marketing efforts toward **professionals and self-employed leads**.  
- Incentivize users to **complete their profiles** (e.g., with demo sessions or personalized course suggestions).  
- Simplify and optimize **first-contact experiences** (landing pages, chatbots, inquiry forms).  
- Continue monitoring model performance and retrain quarterly to adapt to behavioral changes.

---

## 🧰 Tech Stack
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Tools:** Jupyter Notebook / Google Colab  
- **ML Techniques:** Feature Engineering, Model Tuning, Ensemble Learning  

---
