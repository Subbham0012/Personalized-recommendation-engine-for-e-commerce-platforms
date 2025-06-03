# Personalized-recommendation-engine-for-e-commerce-platforms
# 🛍️ Personalized Recommendation Engine for E-Commerce Platforms

## 🔍 Overview
This project builds a personalized recommendation engine for e-commerce platforms using machine learning models. It leverages customer transaction data, product metadata, and behavior logs to provide tailored product suggestions.

The system uses a hybrid approach combining **Collaborative Filtering**, **Content-Based Filtering**, and **Clustering** to segment customers and enhance the recommendation accuracy.

---

## 📊 Business Motivation

- **35–40%** of e-commerce revenue is driven by recommendation systems.
- Personalized AI recommendations can improve **customer retention by 20–30%**.
- Reduces cart abandonment and enhances customer satisfaction.

---

## 🗂️ Dataset

- **Source:** Internal dataset (`online_sales.csv`)
- **Size:** ~52,924 records
- **Features:**
  - `CustomerID`
  - `Transaction_ID`
  - `Product_SKU`
  - `Product_Category`
  - `Quantity`
  - `Avg_Price`
  - `Delivery_Charges`
  - `Discount_pct`
  - `Revenue`

---

## 🧹 Data Preprocessing

- Handling missing values
- Feature Engineering:
  - `Revenue = Quantity * (Avg_Price + Delivery_Charges - Discount)`
- Encoding categorical data
- Dimensionality reduction using **PCA**
- Final dataset: **44 features**

---

## 📈 Exploratory Data Analysis (EDA)

- Seasonal peaks in customer spending (e.g., holidays)
- Top-selling categories: Electronics, Clothing, Home Appliances
- Peak purchase hours: 6 PM to 10 PM
- Avg revenue per transaction: `$50–$200`

---

## 👥 Customer Segmentation

- **K-Means Clustering** used to group customers:
  - Budget Shoppers
  - Mid-Tier Shoppers
  - Premium Shoppers
- **RFM Analysis** validated the segmentation

---

## 🧠 Machine Learning Models

### ✅ Models Used:
- **Collaborative Filtering** – User-item interaction
- **Content-Based Filtering** – Product feature similarity
- **Hybrid Recommender** – Combination of both

### 🔍 Classification Models:
- **Random Forest Classifier** (Accuracy: 82%)
- **Logistic Regression** (Accuracy: 76%)

### 📊 Evaluation Metrics:
- Precision, Recall, F1-Score
- Confusion Matrix

---

## 📊 Results

- **+15–20%** increase in avg revenue per customer
- **10%** reduction in cart abandonment
- Users interacted more with recommended products

---

## 🖥️ Dashboard & Visualization

- Real-time recommendation UI (prototype)
- Visualized:
  - Product category trends
  - Revenue patterns
  - Customer clusters
- Tools: **Matplotlib**, **Seaborn**, **Power BI/Tableau**

---

## 🔮 Future Enhancements

- Integrate **Deep Learning** (Transformers, Neural Nets)
- Real-time recommendations via **Reinforcement Learning**
- Extend to **multi-platform recommendations** (e.g., streaming + shopping)

