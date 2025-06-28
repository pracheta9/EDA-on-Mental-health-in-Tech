# 🧠 Mental Health in Tech — Exploratory Data Analysis

This repository contains an in-depth Exploratory Data Analysis (EDA) of a global survey dataset on mental health in the technology industry. The goal is to uncover patterns and key predictors of mental health challenges, treatment-seeking behavior, and attitudes toward mental health in the workplace.

---

## 📌 Project Overview

Despite increasing awareness of mental health issues, many employees in the tech sector continue to struggle with untreated mental health conditions due to stigma, lack of resources, and workplace culture. This analysis aims to identify what factors influence treatment seeking and willingness to seek help so that companies can design better mental health programs.

---

## 🎯 Problem Statement

Mental health challenges are prevalent in the tech industry, yet many employees do not seek help due to stigma or insufficient workplace support. Understanding the drivers of these behaviors is crucial for creating mentally healthy workplaces.

---

## ✅ Business Objective

Identify key predictors of mental health treatment-seeking and help-seeking behavior among tech employees, so organizations can design effective interventions, reduce stigma, and improve employee well-being and productivity.

---

## 📊 Dataset

- **Source**: Mental Health in Tech Survey
- **Rows**: 1,470 respondents
- **Columns**: 27 variables including demographics, mental health history, attitudes, workplace factors, and perceptions.

---

## 🔧 Data Preparation

- Handled missing values in `state`, `work_interfere`, and `self_employed` by imputing with sensible defaults.
- Cleaned the inconsistent `Gender` column, consolidating dozens of messy entries into consistent categories: Male, Female, Nonbinary, and Other.
- Converted `work_interfere` into an ordered categorical variable for meaningful analysis.
- Created age groups for generational insights.
- Ensured categorical responses were standardized for accurate visualization and modeling.

---

## 📈 Key Analyses & Visualizations

- **Univariate Analysis**: Distribution of treatment-seeking, family history, company size, and age groups.
- **Bivariate Analysis**: Relationships like family history vs. treatment, benefits vs. help-seeking, and comfort with supervisors vs. willingness to seek help.
- **Multivariate Analysis**: Interactions between benefits, company size, and stigma perceptions.
- **Correlation Heatmaps & Pair Plots**: Explored numeric relationships and guided feature selection.
- **Predictive Modeling**: Logistic regression and random forest feature importance identified the strongest predictors of treatment-seeking behavior.

---

## 💡 Key Insights

✅ Family history is a strong predictor of mental health treatment seeking.  
✅ Having mental health benefits dramatically increases willingness to seek help.  
✅ Fear of negative consequences discourages treatment, highlighting workplace stigma.  
✅ Comfort discussing mental health with supervisors is low overall, suggesting the need for manager training.  
✅ Younger employees are more open to seeking help, indicating shifting generational attitudes.

---

## 🏢 Recommendations

- Offer and clearly communicate mental health benefits.
- Foster an open culture to reduce stigma.
- Train managers to handle mental health conversations sensitively.
- Provide anonymous support options to protect privacy.
- Tailor programs by age or region to match diverse employee needs.

---

## 📌 Project Structure

