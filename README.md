# 🏥 Hospital Infection Risk Analysis

**Author:** Allen Arriaga  
**Date:** October 2025  
**Tools Used:** R, Statistics, Data Visualization, Linear Regression, Cross Validation  

---

## 📘 Overview

This project explores the factors influencing **hospital-acquired infection risk** across U.S. hospitals.  
Using statistical modeling and data visualization, I analyzed how **average patient age**, **hospital stay length**, and **regional differences** contribute to infection rates.

The analysis highlights how **hospital management practices**—especially patient stay duration—impact infection outcomes and provides insights for improving healthcare quality.

---

## 📊 Dataset

The dataset contains records from **113 hospitals** nationwide, including:

- **Stay:** Average length of patient stay (days)  
- **Age:** Average patient age (years)  
- **Region:** Hospital’s geographic region (NE, NC, S, W)  
- **Census, Beds, Nurses, Facilities, Culture, Xray, MedSchool:** Hospital resource and diagnostic variables  
- **InfctRsk:** Infection risk (%) — *dependent variable*

Data was cleaned and preprocessed in **R**, with 3 incomplete records removed before statistical analysis.

---

## 🔍 Methods

- **Exploratory Data Analysis (EDA):** Regional comparisons of infection rates through summary statistics and visualizations.  
- **Model 1:** Infection Risk ~ Stay + Region  
- **Model 2:** Infection Risk ~ Stay + Age  
- **Validation:** 10-fold cross-validation to evaluate model performance.

Both models were built using **multiple linear regression** in R, with model diagnostics and RMSE comparison to assess accuracy.

---

## 📈 Key Findings

- **Length of Stay** was the strongest and most significant predictor of infection risk (*p < 0.001*).  
- **Age** had little statistical influence once stay duration was considered.  
- **Regional effects** were minor but slightly higher in the **Western region**.  
- Both models achieved a similar **RMSE of 1.14**, with Model 1 performing slightly better overall.  

---

## 🧠 Conclusion

Longer hospital stays substantially increase infection risk, while patient age has limited influence.  
Results suggest that reducing average hospital stay durations may be one of the most effective strategies for minimizing infection risk.

For the full statistical tables, model outputs, and visualizations, see the complete report below:  

📄 **[View Full Analysis (PDF)](./Hospital_data.pdf)**
