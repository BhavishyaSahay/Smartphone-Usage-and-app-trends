# 📱 Smartphone Usage and App Trends  
### *Data Mining Project — Phase 1 Submission*  

---

## 🧩 Project Overview
This project analyzes global **smartphone app usage trends** using data from the **Google Play Store dataset** on Kaggle.  
The goal is to understand how factors such as app category, ratings, reviews, and monetization strategy (free vs. paid) influence app popularity and user satisfaction.  
The analysis also explores how user concerns evolve over time through review text analysis and visualizes app adoption patterns across regions and categories.

---

## 🎯 Problem Statement
Smartphones have revolutionized the way users interact with technology, but the factors influencing app success and engagement remain complex.  
With millions of apps available, identifying what drives downloads, satisfaction, and retention is essential for both developers and analysts.  
This project explores **what makes apps popular**, **how usage varies across categories and regions**, and **how consumer expectations evolve** through quantitative and textual analysis.

---

## 🎓 Objectives
- Analyze category-wise dominance and growth trends in app downloads.  
- Study correlations between app ratings, reviews, and install counts.  
- Compare user satisfaction across free and paid apps.  
- Perform text analysis of user reviews to uncover key concerns and sentiments.  
- Visualize global patterns in app adoption and cultural preferences.  
- Develop descriptive and predictive models to forecast app success metrics.  

---

## ⚙️ Data Source
**Dataset:** [Google Play Store Apps Dataset (Kaggle)](https://www.kaggle.com/datasets/lava18/google-play-store-apps)  
**Additional Sources:** App Annie archives, regional smartphone adoption datasets, and open data APIs.

---

## 🧹 Data Preprocessing
The raw dataset contained missing values, outliers, duplicate records, and inconsistent formats across attributes such as `ratings`, `reviews`, `price`, and `installs`.  
Preprocessing involved:
- Handling missing data (mean/median imputation or removal).  
- Detecting and treating outliers using IQR-based filtering.  
- Encoding categorical variables (`category`, `type`) for analysis.  
- Normalizing numeric variables for modeling.  
- Cleaning textual data (reviews) using NLP preprocessing steps.  
This process ensured a clean, structured dataset ready for reliable analysis.

---

## 📚 Literature Review (In Progress)
Preliminary studies suggest that app success is influenced by user engagement metrics like ratings and reviews (Linares et al., 2021), while cultural and market dynamics shape app adoption trends (Kim & Lee, 2020).  
Further literature exploration focuses on using sentiment analysis to understand evolving user expectations (Almeida et al., 2022).

---

## 🔬 Exploratory Data Analysis Plan
- Examine trends in installs and ratings by app category and year.  
- Correlate ratings, reviews, and installs to test hypotheses.  
- Compare free vs. paid app performance.  
- Perform regional and temporal analysis to detect cultural patterns.  
- Conduct NLP-based exploration of review content.  

---

## 📊 Visualization Plan
- Interactive bar charts for top apps by category and type.  
- Heatmaps to show feature correlations.  
- Line charts for app growth trends.  
- Boxplots comparing free vs. paid app ratings.  
- Geo maps for regional app adoption.  
- Word clouds and topic models for review analysis.  

---

## 🤖 Modeling Plan
| **Goal** | **Type** | **Algorithm** | **Output** |
|-----------|-----------|---------------|-------------|
| Predict installs | Regression | Linear Regression, Random Forest | Estimate app popularity |
| Predict rating | Regression | XGBoost, Ridge Regression | Estimate average rating |
| Classify app success | Classification | Logistic Regression, Decision Tree | High vs. Low performing apps |
| Cluster market patterns | Unsupervised | K-Means / PCA | Segment apps by category |
| Analyze review themes | NLP | LDA Topic Modeling | Identify key user concerns |


**Tools Used:**  
Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly, scikit-learn, spaCy)  
Google Colab • GitHub • Trello / Notion  

---

## 📅 Phase 1 Deliverables
✅ Defined research problem and objectives  
✅ Literature review (in progress)  
✅ Data preprocessing workflow  
✅ Exploratory analysis and visualization plan  

---

## 🧭 Next Steps (Phase 2 Preview)
- Complete feature engineering and full EDA.  
- Train and validate predictive models.  
- Develop interactive visualization dashboard.  
- Finalize literature review and theoretical grounding.  
- Document findings and insights.

---

## 🧾 References
1. Linares et al., *Predicting Mobile App Success using Store Features*, ACM, 2021.  
2. Kim & Lee, *App Market Dynamics: Understanding Consumer Behavior*, Elsevier, 2020.  
3. Almeida et al., *User Sentiment Analysis of Mobile Apps*, IEEE, 2022.  
