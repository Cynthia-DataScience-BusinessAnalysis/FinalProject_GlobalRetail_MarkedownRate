# 📊 FinalProject_GlobalRetail_MarkedownRate
Final project made during my Data Science and Business Analytics course, to a real customer. Goal: exploring and analyzing performance data through an interactive Power BI dashboard and build a classification model in Python, designed to predict product sales based on their specific attributes.

# 🏷️ Markdown Rate for Close-to-Expiration Products

## 🧐 Overview
At Global Retail, special tags called **Pink Labels** are placed on products nearing the end of their shelf life. Each label is distinct and personalized depending on the product. The main goal is to reduce potential waste, improve labeling effectiveness, and understand the variables that influence sales of near-expiration items.  

This project is divided into two main phases:  
1. **Performance Analysis:** Explore and analyze the effectiveness of labeling using an interactive Power BI dashboard.  
2. **Predictive Modeling:** Build supervised classification models in Python to predict whether a product will sell or not.  

The objectives include:  
- Forecasting sales based on business strategy and product characteristics.  
- Identifying the variables that most impact labeling effectiveness (e.g., discount percentage fluctuations, timing of labeling) to improve strategies, efficiency, and profitability.  

## 🛠️ Technologies Used
- **Power BI** – for data visualization and dashboard creation  
- **Python** – for data processing and predictive modeling  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`  

## 📂 Project Structure
The project is organized as follows:  
Project Folder
- Datasets/ # Contains raw and processed datasets
- Power BI/ # Power BI dashboard files
- Python/ # Python scripts for data cleaning, modeling, and analysis
- README.md # Project documentation

## 🚀 Main Features
### 📊 Dashboard
The Power BI dashboard analyzes labeling performance on products, including:  
- Total sales metrics by district, store, brand, and product  
- Evaluation of sales quality  
- Timing of label placement and average days until sale  
- Assessment of product waste  

### 🧩 Clustering Phase
Two clustering models were initially created:  
- **SKU-level segmentation** → to differentiate product profiles  
- **Store-level segmentation** → to capture behavior and operational differences  

### 🤖 Classification Models
Python models predict whether a product will sell or not using:  
- **KNN**  
- **Logistic Regression**  
- **Random Forest**  

**Evaluation metrics:** 
- **Precision** → reliability of predicted positives  
- **Accuracy** → percentage of correct predictions  
- **Recall** → ability to capture all true positives  
- **AUC-ROC** → confidence score of model predictions  

## 🏃 How to Run
The Python scripts are executed in **Google Colab**. Major libraries include:  

## 📦 Requirements
- Python 3.10+  
- pandas  
- numpy  
- scikit-learn  
- matplotlib  
- seaborn  
- joblib  

## 📊 Results / Insights

**Performance Analysis:**  
- Overall markdown rate (labeling effectiveness) achieved: **54%**  
- Highest sales peak: **Thursday & Friday**, influenced by label placement date  
- **80% of products sold within 0–1 days** of label placement  
- Realized profit: **52%** of potential, recovering **14%** compared to initial profit  
- Markdown rate by discount: relatively stable, most applied discount is **30%**  
- Markdown rate by remaining shelf life: fluctuates between **41%–58%**, most products sold with **30–40% or 60–70%** of remaining shelf life  
- Brand 2 stands out, representing **43% of total sales**  
- Top SKUs: **227 and 105**, achieving markdown rates above average (**77% and 79%**)  
- Labels are placed, on average, at **48% of product life**  

**Predictive Modeling:**  
- The **Random Forest** model outperformed the others across all metrics (ranging between **70% and 80%**).  
- **Main driver:** Selling area (`selling_square_ft`)  
- **Secondary drivers:** Product weight, price, margin, % expiration, and brand  

## 📬 Contact
This project was developed as part of the **Data Science and Business Analytics** course at EDIT school, for a real customer, **LTPLabs**.  
For questions or collaborations, feel free to reach out via **LinkedIn** or **email**.  
