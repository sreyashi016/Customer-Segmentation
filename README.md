# 🛍 *CUSTOMER SEGMENTATION*

---

## 🧾 *PROJECT DESCRIPTION*
Group customers into meaningful clusters based on their purchasing behavior and demographic data using Machine Learning.  

This project applies *K-Means Clustering* to segment customers into groups for better understanding and targeted marketing strategies.  

---

## 📚 *TABLE OF CONTENTS*
- 📌 *Project Title*
- 🧾 *Project Description*
- 📚 *Table of Contents*
- 📊 *Dataset Information*
- 🛠 *Tech Stack Used*
- 🧠 *Workflow & Methodology*
- 📈 *Model Performance*
- 🧪 *How to Use*
- 🏁 *Results*
- 👥 *Author*

---

## 📊 *DATASET INFORMATION*
- *Name: *Mall Customers Dataset  
- *Format*: CSV  
- *Total Entries*: 200 customers  
- *Columns*:
  - CustomerID: Unique ID for each customer  
  - Gender: Male/Female  
  - Age: Age of customer  
  - Annual Income (k$): Annual income in thousands  
  - Spending Score (1–100): Score assigned based on spending pattern  

---

## 🛠 *TECH STACK USED*
- *Programming Language: 🐍 *Python 3  
- *Libraries & Tools*:
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn (KMeans, StandardScaler)  

---

## 🧠 *WORKFLOW & METHODOLOGY*
1. *Load and Inspect Data*  
2. *Data Preprocessing*  
   - Handle missing values  
   - Standardize numerical features  
3. *Exploratory Data Analysis (EDA)* 📊  
   - Visualize distributions & relationships  
4. *Clustering with K-Means*  
   - Use *Elbow Method* to find optimal number of clusters  
   - Apply *K-Means Algorithm*  
5. *Cluster Visualization*  
   - Plot customer groups in 2D space (Income vs Spending Score, etc.)  

---

## 📈 *MODEL PERFORMANCE*
- K-Means successfully divided customers into *5 clusters*  
- Clusters represent distinct spending & income groups:
  - Low Income – Low Spending  
  - Low Income – High Spending  
  - Average Customers  
  - High Income – Low Spending  
  - High Income – High Spending  

---

## 🧪 *HOW TO USE*
- Open the notebook: Customer_Segmentation.ipynb  
- Run the cells step by step  
- Check visualizations of customer clusters  
- Try changing the number of clusters (k) to experiment  

---

## 🏁 *RESULTS*
- ✔ Customers were segmented into *meaningful groups*  
- ✔ Businesses can target specific customer clusters 🎯  
- ✔ Visualization shows clear differences between groups  
