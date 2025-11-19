# 📱 Smartphone Usage and App Trends  
### *Data Mining Project — Phase 1 & Phase 2 Submission*  

---

## 🧩 Project Overview
This project analyzes global smartphone app usage patterns using the Google Play Store dataset.  
The study investigates how app categories, ratings, reviews, monetization strategies, and regional differences influence popularity and user satisfaction.  
The project also includes interactive dashboards, exploratory analysis, and predictive modeling.

---

## 🎯 Problem Statement
The rapid growth of mobile applications has created a need to understand what drives app success.  
This project explores:
- Which app categories dominate downloads  
- Whether ratings correlate with installs  
- How monetization affects user satisfaction  
- What user reviews reveal about evolving concerns  
- How regional and cultural differences influence app adoption  

---

## 🎓 Objectives
- Analyze category-wise dominance and install patterns  
- Study relationships between installs, ratings, and reviews  
- Compare free vs. paid apps  
- Perform text-based analysis of user reviews  
- Build regression and classification models for app success prediction  
- Create interactive visualizations for dynamic exploration  

---

## 📂 Dataset
- **Primary Dataset:** Google Play Store Apps Dataset (Kaggle)  
  https://www.kaggle.com/datasets/lava18/google-play-store-apps  
- **Secondary Sources:** App Annie, SimilarWeb, open APIs  

---

## 🧹 Data Preprocessing
Performed cleaning and pre-processing including:
- Duplicate removal  
- Missing value treatment  
- Normalization of numerical values  
- Outlier detection (IQR method)  
- Encoding categorical variables  
- Converting textual numerical columns (Installs, Price) into usable formats  

The dataset is now clean, consistent, and ready for analysis.

---

## 📚 Literature Review (Updated)
Prior research shows app success is influenced by:
- Ratings and review volumes (Linares et al., 2021)  
- Pricing and monetization strategy (Kim & Lee, 2020)  
- User sentiment and review-based complaints (Almeida et al., 2022)  

This project extends prior work by combining EDA, predictive modeling, and interactive dashboards.

---

# 🔎 Phase 2 — Exploratory Data Analysis (Completed)
The analysis includes:
- Distributions of installs, ratings, reviews  
- Category-level comparisons  
- Free vs. Paid performance analysis  
- Correlation heatmaps  
- Outlier detection  
- App-size and update-frequency patterns  
- Preliminary text analysis (keyword frequency)  

### **Interactive Visualizations**
- Top 5 apps by Category + Type selector  
- Install-based insights  
- Trend exploration using Plotly  

---

# 🤖 Modeling Plan (Phase 3 Preview)
### **Regression**
- Linear Regression  
- Random Forest  
- XGBoost Regression  

### **Classification**
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  
---

## 📊 Visualization Plan
- Category-wise bar charts  
- Free vs. Paid comparison boxplots  
- Heatmaps for correlations  
- Growth trend line charts  
- Geographic preference visualizations  
- Word clouds and sentiment plots  

---

## 🧠 Methodology Justification
- **EDA:** Understand structure, detect anomalies, guide modeling  
- **Regression/Classification:** Predict installs, ratings, and success tiers  
- **XGBoost:** Handles non-linear relationships, missing values, and provides feature importance  

---

## 👥 Team & Task Division
| Member | Role | Responsibilities |
|--------|------|------------------|
| Bhavishya Sahay | Lead (Phase 1) | Preprocessing, EDA, modeling setup |
| Asmit Kumar | Lead (Phase 2) | Visualizations, interactive dashboard |
| Aman Kumar | Lead (Phase 3) | Predictive modeling, NLP, evaluation |

**Tools Used:**  
Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, scikit-learn, spaCy  
Google Colab • GitHub • Trello  

---

## 📅 Deliverables Completed
### **Phase 1**
- Problem statement  
- Objectives  
- Preprocessing pipeline  
- Literature review  
- Methodology outline  
- IEEE report draft  

### **Phase 2**
- Complete EDA  
- Visualizations & insights  
- Interactive Plotly dashboard  
- Updated preprocessing  
- Exploratory findings summary  

---

## 🚀 Next Steps (Phase 3)
- Full predictive modeling  
- Feature engineering  
- NLP sentiment and topic analysis  
- Streamlit dashboard  
- Final IEEE report  

---

## 🧾 References
1. Linares et al., *Predicting Mobile App Success Using Store Features*, ACM, 2021.  
2. Kim & Lee, *App Market Dynamics*, Elsevier, 2020.  
3. Almeida et al., *User Sentiment Analysis of Mobile Apps*, IEEE, 2022.  

---
