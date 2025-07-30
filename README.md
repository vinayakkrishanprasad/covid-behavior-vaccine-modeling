# 🧠 COVID-19 Behavior & Belief-Based Prediction

**Team !404 Team Found**  
*Vinayak Prasad, Ian Hash, Kavi Sarna, Rishika Thiruvengadam Dwaraghanath*  
Carnegie Mellon University – Machine Learning for Problem Project

---

## 📌 Overview

This project explores the predictive power of self-reported behavioral and belief-based indicators in forecasting:

- **14-day COVID-19 test positivity rates**  
- **Cumulative vaccination rates**

Using the **COVID-19 Trends and Impact Survey (CTIS)** by CMU Delphi Research Group, we modeled health outcomes at the county level to support informed public health strategies.

---

## 🔍 Methodology

- **Data Source:** CTIS data from Jan–Feb 2021 (25k+ county-level records)
- **Feature Engineering:** Included behavior signals (e.g. mask use, social activity), belief indicators (e.g. vaccine trust), and interaction terms
- **Models Used:**
  - Linear Regression (baseline)
  - Ridge Regression
  - **Random Forest (optimized - best performance)**
  - Gradient Boosting Regressor (for comparison)
- **Evaluation Metrics:** R², MAE, RMSE with 5-fold cross-validation

---

## 💡 Key Findings

- Mask-wearing and reported COVID-like illness are top predictors of test positivity
- Social influence (e.g. friends’ vaccine attitudes) predicts vaccination rates more strongly than institutional trust
- Optimized Random Forest models improved predictive power by over **90%** compared to baselines

---

## 📈 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- JupyterLab

---

## 📄 Report Access

Full technical report with modeling code, visualizations, and policy insights available upon request.

---

## 📬 Contact

For access to the full report or collaboration inquiries, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/vinayakprasad02).

