# Data-Driven Policy Innovation (Datathon Project)

## 📌 Overview
This project was developed as part of a **Datathon on Data-Driven Policy Innovation**, with the goal of using large-scale public datasets to derive actionable insights for improving **educational access, retention, and equity** in India.

We analyzed national-level education and demographic data to understand how **infrastructure, socioeconomic factors, and demographics** influence student enrolment and dropout patterns, and translated these findings into **policy-relevant recommendations**.

---

## 🎯 Problem Statements Addressed

The analysis focused on the following three key policy questions:

1. **Do dropout and retention patterns differ between urban and rural districts when disaggregated by gender and caste?**
2. **How does the availability of teachers and functional school infrastructure (especially toilets) influence student retention?**
3. **How do household income, parental education, and employment status relate to student enrolment and dropout rates?**

---

## 📊 Datasets Used

### 1. **UDISE (Unified District Information System for Education)**
- School-level data covering:
  - Enrolment and dropout statistics
  - Teacher availability
  - School infrastructure (e.g., functional toilets)
  - District-level education indicators

### 2. **NFHS (National Family Health Survey)**
- Household-level demographic and socioeconomic data including:
  - Household income indicators
  - Parental education levels
  - Employment status
  - Urban–rural classification

### 📈 Dataset Scale
- **Total records analyzed:** 1,000,000+  
- **Number of variables:** 30+  
- **Granularity:** District-level and school-level

---

## 🔍 Methodology

1. **Data Cleaning & Preprocessing**
   - Standardized district identifiers across datasets
   - Handled missing and inconsistent values
   - Filtered and aggregated data to comparable geographic units

2. **Data Integration**
   - Merged UDISE and NFHS datasets using common geographic identifiers
   - Combined education, infrastructure, and socioeconomic indicators

3. **Exploratory Data Analysis (EDA)**
   - Urban vs. rural comparisons
   - Gender- and caste-wise disaggregation
   - Correlation analysis between infrastructure and retention
   - Socioeconomic factor analysis for enrolment and dropout trends

4. **Visualization & Insight Generation**
   - Built interactive, web-based dashboards using React to explore district-wise and category-wise trends.
   - Enabled dynamic filtering across geography (urban vs. rural), gender, caste, and socioeconomic indicators.
   - Deployed the visualization interface on Vercel for easy access and real-time interaction.


---

## 📌 Key Insights

- **Urban–Rural Disparities:**  
  Rural districts showed higher dropout rates, with pronounced gaps when further disaggregated by **gender and caste**.

- **Infrastructure Matters:**  
  Schools with better **teacher availability** and **functional toilets** demonstrated significantly improved retention outcomes.

- **Socioeconomic Influence:**  
  Lower household income, lower parental education levels, and unstable employment status were strongly associated with higher dropout rates and lower enrolment.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Visualization:** React, node.js  
- **Environment:** Jupyter Notebook  

---
## Author

Developed by Potini Sahiti, Tejas Kollipara, Varun E and Deepak Saai 
