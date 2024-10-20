# 🛒 Supermart Grocery Sales ML Project  

This project focuses on **exploring and analyzing grocery sales data** from a supermart. We’ll perform **feature engineering** and build a **machine learning model** to predict sales, gaining insights into trends that can help improve business decisions.

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
