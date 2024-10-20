# 🛒 Supermart Grocery Sales ML Project  

This project focuses on **exploring and analyzing grocery sales data** from a supermart. We’ll perform **feature engineering** and build a **machine learning model** to predict sales, gaining insights into trends that can help improve business decisions.

---
## Overview

This project focuses on using a dataset containing information about grocery sales at a supermart.We’ll explore this data, perform feature engineering, and build a machine learning model to predict sales
The dataset includes columns such as Order ID,Customer Name,Category, Sub Category, City, Order Date, Region, Sales, Discount,Profit, State, month_no, Month, and year.
On this ML Project performs EDA,Handling Outliers,Uses different visualization tools,Restructure Date column,label encoding for categorical values for convertion,Linear regression for model building,and check the MSE and R2 for perfection.
At last the model is performs well
MSE is 126.98 it lower MSE indicates better model performance. the MSE is relatively low, meaning the model's predictions are quite close to the actual values.R² value is closer to 1 indicate that the model explains most of the variance. An R² of 0.9617 means your model explains around 96% of the variance in the data.

---
## 🎯 Objective  
- Use a dataset containing information about grocery sales at a supermart.  
- Perform **data exploration** and **feature engineering**.  
- Build a **machine learning model** to predict **sales** and analyze factors impacting profit.

---

## 📂 Dataset Overview  
| Column Name      | Non-Null Count | Description                               |
|------------------|----------------|-------------------------------------------|
| **Order ID**     | 9994           | Unique identifier for each order          |
| **Customer Name**| 9994           | Name of the customer                      |
| **Category**     | 9994           | Product category                          |
| **Sub Category** | 9994           | Product sub-category                      |
| **City**         | 9994           | City where the order was placed           |
| **Order Date**   | 9994           | Date when the order was placed            |
| **Region**       | 9994           | Region where the order was placed         |
| **Sales**        | 9994           | Total sales amount                        |
| **Discount**     | 9994           | Discount applied on the product           |
| **Profit**       | 9994           | Profit earned from the order              |
| **State**        | 9994           | State where the order was placed          |

---

## 🛠️ Tools & Libraries  
- **Python**  
- **pandas** – Data handling and cleaning  
- **scikit-learn** – Model building and evaluation  
- **matplotlib** & **seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive coding environment  

---

## 🚀 Project Workflow  

1. **Data Cleaning:**  
   - Handle missing values (if any)  
   - Convert date columns to appropriate formats  
   - Perform **label encoding** for categorical features  

2. **Exploratory Data Analysis (EDA):**  
   - Analyze **sales trends** by category, region, and time  
   - Study the relationship between **discount and profit**  
   - Identify **high-profit products** and **key regions** contributing to sales  

3. **Feature Engineering:**  
   - Extract features such as **month**, **year**, or **day** from `Order Date`  
   - Create new features like **Profit Margin** **Sales Margin**

4. **Model Building:**  
   - Train a **Linear Regression** model to predict sales  
   - Evaluate the model with **R² score** and **MSE (Mean Squared Error)**  

5. **Achieved:**  
   - model achieved an **R² score of 0.961**  
   - **MSE** is **126.99**

---

## 📊 Key Insights  
- **Sales and Discounts:** A higher discount doesn’t always result in higher profits.  
- **Regions:** Some regions outperform others in terms of both sales and profit.  
- **Category Analysis:** Product categories like **Furniture** and **Technology** contribute significantly to sales.  

---
