# Sales Transactions Classification – Fashion Industry

## 📌 Overview
A data mining project that classifies fashion retail sales 
transactions into Low, Medium, and High sales categories 
using the J48 Decision Tree algorithm in WEKA. The dataset 
contains 100,000 instances with 20 mixed attributes sourced 
from Kaggle.

## 🎯 Problem Statement
Fashion retailers generate massive volumes of sales data 
daily. This project explores whether machine learning 
classification can automatically categorise sales performance 
levels to support inventory and marketing decisions.

## 🔄 Methodology
1. **Data Preparation** — Loaded 100,000-instance dataset, 
   handled missing values and noise
2. **Feature Selection** — Tested multiple dataset variants 
   with different attribute combinations
3. **Modelling** — Applied J48 Decision Tree classifier
4. **Evaluation** — Compared results across:
   - 10-fold cross-validation
   - 20-fold cross-validation
   - 70:30 percentage split
   - 80:20 percentage split
5. **Analysis** — Examined Kappa statistics and accuracy 
   trends to evaluate model reliability

## 📊 Key Results
- ✅ Dataset: **100,000** sales instances, 20 attributes
- ✅ Best accuracy: **35.34%** 
- ✅ Found that high noise levels and overlapping class 
  boundaries in retail data significantly impact 
  classifier performance
- ✅ Demonstrated importance of feature selection in 
  improving model accuracy

## 🛠️ Tools & Technologies
- WEKA (J48 Decision Tree, cross-validation)
- Techniques: Data Mining, Feature Selection, 
  Classification, Cross-Validation

## 👤 Author
Muhammad Nurhilman Bin Mohd Rozalee
hilmanrozalee7@gmail.com
