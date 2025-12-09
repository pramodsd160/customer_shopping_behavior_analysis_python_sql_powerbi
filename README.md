# **Customer Shopping Behavior Analysis Portfolio Project**

---

## **Summary**
A complete end-to-end data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI.

---

## **Table of Contents**
- [Project Overview](#project-overview)  
- [Business Problem Statement](#business-problem-statement)
- [Dataset](#dataset) 
- [Tools and Technologies](#tools-and-technologies) 
- [Project Structure](#project-structure)
- [Dashboard Requirements & Visuals](#dashboard-requirements--visuals)  
- [Business Recommendations](#business-recommendations) 
- [Report](#report) 
- [Key Learning & Conclusion](#key-learning--conclusion)  
- [How to Run the Project](#how-to-run-the-project)  
- [Author & Contact](#author--contact)  

---

## **Project Overview**
This project simulates a **corporate-grade, end-to-end data analytics workflow**, showcasing the ability to convert raw customer shopping data into meaningful business insights. It includes:

- **Python (Jupyter Notebook)** for Data Preparation, Modeling & Exploratory Data Analysis  
- **Oracle SQL 11g** for analytical queries on customer segments, loyalty trends, and purchase behavior  
- **Power BI** for an interactive business dashboard  
- **Report & Presentation** summarizing insights and business actions  

---

## **Business Problem Statement**
A leading retail company wants to better understand its customers’ shopping behaviour in order to improve sales, customer satisfaction, and long-term loyalty.

The management team has noticed changes in purchasing patterns across demographics, product categories, and sales channels (online vs. offline).

They are particularly interested in uncovering which factors, such as discounts, reviews, seasons, or payment preferences, drive consumer decisions and repeat purchases.

You are tasked with analyzing the company’s consumer behaviour dataset to answer the following overarching business question:

**“How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?”**

---

## **Dataset**
Dataset available in the **dataset** folder (CSV file).

---

## **Tools and Technologies**
- **Python** – Jupyter Notebook (EDA, cleaning, modeling)  
- **Power BI** – Dashboard creation & data modeling  
- **DAX** – KPI calculations and measures  
- **CSV** – Raw dataset  
- **Oracle SQL 11g** – Data cleaning, validation & insights  
- **GitHub** – Version control & repository management  

---

## **Project Structure**
```
customer_shopping_behavior_analysis
	├── dashboard
	├── dataset
	├── images
	├── notebook
	├── other_resources
	├── report
	├── script
	├── Readme.md
```

---

## **Dashboard Requirements & Visuals**

### **1. Customer Insights**
**Business Need:** Understand customer base, satisfaction, and demographics.

**Visuals:**
- **Total Customers (KPI Card)** – Customer volume  
- **Average Review Rating (KPI Card)** – Satisfaction level  
- **Revenue by Age Group (Bar Chart)** – Revenue contribution  
- **Sales by Age Group (Bar Chart)** – Purchase frequency  
- **Gender (Button Slicer)** – Filter by male/female  

---

### **2. Sales & Revenue Performance**
**Business Need:** Track sales trends and revenue performance.

**Visuals:**
- **Average Purchase Amount (KPI Card)** – Avg spending  
- **Revenue by Category (Column Chart)** – Top revenue categories  
- **Sales by Category (Column Chart)** – Category-wise volume  
- **Category (Button Slicer)** – Analyze specific categories  
- **Shipping Type (Slicer)** – Impact of shipping preference  

---

### **3. Subscription Analysis**
**Business Need:** Understand subscription adoption and behavior.

**Visuals:**
- **% Customers by Subscription Status (Donut Chart)** – Subscriber distribution  
- **Subscription Status (Button Slicer)** – Compare subscribers vs non-subscribers  

![Dashboard Preview](https://github.com/pramodsd160/customer_shopping_behavior_analysis_python_sql_powerbi/blob/main/images/Dashboard%20customer_shopping_behaviour.png)


---

## **Business Recommendations**

- **Increase Subscriptions** – Highlight exclusive perks to encourage more users to subscribe.  
- **Enhance Loyalty Programs** – Reward repeat buyers to convert them into loyal customers.  
- **Optimize Discount Strategy** – Use review-based promotions while protecting margins.  
- **Strengthen Product Positioning** – Promote top-rated and best-selling items.  
- **Improve Targeted Marketing** – Focus on high-revenue age groups and express-shipping users.  

---

## **Report**

This project includes a detailed report summarizing the analysis, insights, and business recommendations.  
It explains the full workflow from data preparation to final dashboard interpretation.  

📁 The complete report is available in the **`/report`** folder.  

---

## **Key Learning & Conclusion**
Connecting all stages—from raw data to SQL insights to dashboard—helped me understand how data is transformed into business-ready intelligence.

This project strengthened my end-to-end analytics workflow skills and showcased how data-driven recommendations support business growth and customer engagement.

---

## **How to Run the Project**

### **1. Open Jupyter Notebook**
File: `Customer_Shopping_Behavior_Analysis.ipynb`

Includes:
- Data import  
- Data exploration  
- Data cleaning  
- Export cleaned data (CSV)  
- Oracle SQL DB connection  
- Load data into Oracle SQL  

---

### **2. Oracle SQL Developer**
- Import cleaned CSV into database  
- Open `customer_shopping.sql`  
- Run business queries  

---

### **3. Connect SQL Database to Power BI**
**Power BI > Get Data > More > Oracle Database**

Use:  
`localhost:1521` (default Oracle 11g)

Enter database username & password  
Build dashboard using measures, charts, and slicers  

PBIX file available in **dashboard** folder.

---

## **Author & Contact**
👤 **Author:** Pramod Dhamane (Data Analyst)
  - **[Email](pramodsd160@gmail.com)**
  - **[LinkedIn](www.linkedin.com/in/pramoddhamane)**
  - **[GitHub](https://github.com/pramodsd160)** 
