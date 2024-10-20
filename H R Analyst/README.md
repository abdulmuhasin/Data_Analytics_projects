# 🏢 HR ML Project – Employee Attrition Prediction  

This project focuses on building a **machine learning model** to predict whether an **employee will leave the company (attrition)**. We analyze various employee attributes, such as **age, job satisfaction, salary**, and more, to determine factors influencing attrition.

---

## 🎯 Objective  
- Predict employee **attrition** based on multiple features.  
- Identify key factors contributing to employee turnover.  
- Provide insights to help businesses reduce attrition rates.

---

## 📂 Dataset Overview  
| Column Name                | Description                            |
|----------------------------|----------------------------------------|
| **Employee_Name**          | Name of the employee                  |
| **EmpID**                  | Employee ID                           |
| **MarriedID**              | Indicates if the employee is married  |
| **MaritalStatusID**        | Encoded marital status                |
| **GenderID**               | Encoded gender                        |
| **EmpStatusID**            | Employment status                     |
| **DeptID**                 | Department ID                         |
| **PerfScoreID**            | Performance score ID                  |
| **FromDiversityJobFairID** | Hired through diversity job fair      |
| **Salary**                 | Employee salary                       |
| **Termd**                  | Indicates if the employee is terminated |
| **PositionID**             | Position ID                           |
| **Position**               | Employee position                     |
| **State**                  | State of employment                   |
| **Zip**                    | ZIP code of employee location         |
| **DOB**                    | Date of birth                         |
| **Sex**                    | Gender                                |
| **MaritalDesc**            | Marital status description            |
| **CitizenDesc**            | Citizenship status                    |
| **HispanicLatino**         | Indicates Hispanic/Latino status      |
| **RaceDesc**               | Race description                      |
| **DateofHire**             | Hiring date                           |
| **DateofTermination**      | Termination date (if applicable)      |
| **TermReason**             | Reason for termination                |
| **EmploymentStatus**       | Employment status                     |
| **Department**             | Department of employee                |
| **ManagerName**            | Manager's name                        |
| **ManagerID**              | Manager ID                            |
| **RecruitmentSource**      | Recruitment source                    |
| **PerformanceScore**       | Employee performance score            |
| **EngagementSurvey**       | Engagement survey score               |
| **EmpSatisfaction**        | Employee satisfaction score           |
| **SpecialProjectsCount**   | Number of special projects assigned   |
| **LastPerformanceReview_Date** | Date of the last performance review |
| **DaysLateLast30**         | Days late in the last 30 days         |
| **Absences**               | Total absences                        |

---

## 🛠️ Tools & Libraries  
- **Python**  
- **pandas** – Data handling and manipulation  
- **scikit-learn** – Machine Learning models  
- **matplotlib** & **seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive environment  

---

## 🚀 Project Workflow  

1. **Data Cleaning:**  
   - Handle missing values.  
   - Standardize date formats for `DateofHire` and `DOB`.  
   - Remove irrelevant columns like `Employee_Name` for modeling.  

2. **Exploratory Data Analysis (EDA):**  
   - Analyze features such as **Salary, EngagementSurvey, PerformanceScore**.  
   - Identify trends between **age, absences**, and **attrition**.  

3. **Feature Engineering:**  
   - Extract features like **Tenure** from `DateofHire`.  
   - Encode categorical features such as **Sex, Department, MaritalStatusID**.

4. **Model Building:**  
   - Train a **Random Forest Classifier** to predict attrition.  
   - Evaluate model performance using **accuracy, precision, and recall**.  
   - Achieved **100% accuracy** on test data.

5. **Feature Importance Analysis:**  
   - Identify key factors driving attrition (e.g., **Job Satisfaction, Absences, Salary**).

---

## 📊 Key Insights  
- **Job Satisfaction and Salary** significantly influence attrition.  
- Employees with higher **absences** are more likely to leave.  
- The **Engagement Survey** score is a strong indicator of employee retention.  

---
