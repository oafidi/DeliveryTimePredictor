# Delivery Time Prediction – Smart Delivery Time Forecasting

A real-world artificial intelligence project, developed with [Khalid Abouelfaraj], aiming to accurately **predict delivery time** from historical data, while leveraging a complete, robust, and deployed machine learning pipeline.

---

## 🚀 Project Objectives

In fields such as **e-commerce**, **logistics**, **food delivery**, or **express shipping**, accurate delivery time prediction helps to:

- Improve **customer satisfaction** with more precise estimates  
- Optimize **human and logistical resource management**  
- Reduce **costs** related to delays or poor planning  
- Provide **actionable forecasts** in decision-making dashboards  

---

## Complete Project Pipeline

### 1. Data Collection
- Over **40,000 real observations**  
- Historical delivery data including location, weather, traffic, etc.  

### 2. Cleaning & Preprocessing
- Correction of **syntactic and semantic errors**  
- Detection and handling of **outliers**  
- Intelligent imputation of missing values using:  
  - `KNNImputer`  
  - Other techniques (no automatic deletion of rows)  

### 3. Feature Engineering & Selection
- Creation of **new explanatory variables**  
- Selection of the most significant features using **statistical tests**:  
  - Correlation for **quantitative variables**  
  - **ANOVA test** for **qualitative variables**  

### 4. Data Preparation
- **Z-score scaling** for numerical features  
- **One-hot encoding** for categorical features  
- Dimensionality reduction with **PCA** + exploratory analysis:  
  - Study of **distribution**, **skewness**, etc.  

### 5. 🤖 Model Training
- Models tested:  
  - `LinearRegression`  
  - `KNeighborsRegressor`  
  - `SVR`  
  - `RandomForestRegressor`  
  - `XGBoostRegressor`  
- The **XGBoost** model proved to be the **most efficient** on our test dataset  

### 6. Deployment with Streamlit
- Built an **interactive web interface**  
- Allows users (couriers, managers, platforms...) to **predict delivery times in real-time** based on new inputs  

---

## Results

- Best model: `XGBoostRegressor`  
- Evaluation using the **R² score**  
- Excellent **generalization on test data**  

---

## Technologies Used

- Python (pandas, numpy, matplotlib, seaborn)  
- Scikit-learn  
- XGBoost  
- Streamlit  
- Jupyter Notebooks  

---

## What This Project Demonstrates

- My ability to build a **full end-to-end AI pipeline**  
- My expertise in **data analysis**, **modeling**, and **deployment**  
- My commitment to solving **real-world business problems with impact**  
- My **effective teamwork and collaboration skills**  

---

## Opportunities & Collaboration

💬 **Are you working in logistics, delivery, or transportation?**  
I am passionate about **practical innovation** and eager to apply my skills to impactful projects.  
➡️ Feel free to reach out to discuss potential **collaborations or real-world applications** of this system!  

---

## Interface – Preview

![image](https://github.com/user-attachments/assets/c442cdb7-ed13-434b-b627-0344dfb7e2fd)


---


