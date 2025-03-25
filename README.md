# 📊 Power BI Capstone Project - Tailwind Traders

## 🚀 Overview
This project demonstrates data preparation, transformation, and modeling for **Tailwind Traders** using **Microsoft Excel** and **Power BI**. It involves working with sales and purchases data to develop a refined **data model** and gain business insights.

---

## 📌 Part 1: Data Preparation & Transformation

### 🟢 **Exercise 1: Prepare Sales Data (Excel)**
1. **Download & Open Data**  
   - Open `Tailwind Traders Sales.xlsx`
   - Use the `Sales` worksheet.

2. **Data Cleaning & Calculations**  
   - **Calculate Cost per Unit:** `=E2*0.35`
   - **Calculate Gross Revenue:** `=E2*H2`
   - **Calculate Total Tax:** `=G2*H2`
   - **Calculate Net Revenue:** `=I2-J2`
   - **Calculate Profit:** `=K2-(F2*G2)`

3. **Assign Correct Data Types**  
   - Whole Number: `Quantity Purchased, Loyalty Points, Stock`
   - Fixed Decimal: `Gross Product Price, Cost per Unit, Profit`
   - Text: `Product Category, Sales Rep`

---

### 🟢 **Exercise 2: Load & Configure Data in Power BI**
1. **Load Data into Power BI**
   - Import `Tailwind Traders Sales.xlsx`
   - Click **Transform Data** (opens Power Query Editor).

2. **Set Data Types & Validate Data**
   - `OrderID` → Whole Number
   - Check `Column Quality, Column Distribution, Column Profile`
   - Verify **100% Valid Rate** for `OrderID`
   - Find distinct values & min/max for `Gross Product Price` & `Quantity Purchased`

3. **Load Purchases Data**
   - Download & load `Purchases.xlsx`
   - Assign proper data types:
     - Whole Number: `PurchaseID, OrderID, Warranty (Months)`
     - Date: `Purchase Date, Last Visited`
     - Text: `Supplier, ReturnStatus`

---

## 📊 **Final Deliverable**
✅ **Power BI Dashboard:** 
![image](https://github.com/user-attachments/assets/2e0e9307-be82-4d34-9535-871e7a032b8c)
![image](https://github.com/user-attachments/assets/daf333fc-37ac-48e2-966c-b781bdee1866)



✅ **Data Model with Optimized Relationships**  
![image](https://github.com/user-attachments/assets/c6b00cb8-a21e-452a-942e-770272af9b89)
![image](https://github.com/user-attachments/assets/e980ea68-a6fe-45af-a4cd-aa9243d94c4a)


*****************************************************************************************************************************************************************
# Power BI Analysis - AdventureWorks Dataset

This is a detailed report of my data analysis process using Power BI.

## Step 1: Data Inspection
After loading the AdventureWorks dataset into Power BI, I inspected the data quality. Here is the screenshot of the Power Query Editor.

![image](https://github.com/user-attachments/assets/22a1c2f7-53ee-433f-92dc-eb7a6408c06d)


## Step 2: Data Profiling
I performed data profiling on the `StockLevel` column. Below is the column profile:
![image](https://github.com/user-attachments/assets/6c991d7c-a69e-4c50-b62e-74fa0c43ccc6)


***********************************_______________________________________________________________________________*************************************************************************


# Power BI - Common Date Table Creation  
This guide provides step-by-step instructions on creating a **common date table** in Power BI using **DAX**. A date table helps in performing **time intelligence calculations**, filtering, grouping, and improving the efficiency of a data model.

## 📌 Why Use a Date Table?  
- Enables **year-to-date (YTD)**, **month-to-date (MTD)**, and other time-based calculations.  
- Helps define **custom time periods** (e.g., Fiscal Year).  
- Improves performance and relationships in Power BI models.

## 🛠 Prerequisites  
Before creating a date table, ensure the following:  
✔ A date column with **Date/Time data type**.  
✔ No **blank values** in the date column.  
✔ Each date appears **only once** (unique values).  
✔ No **missing dates** in the date range.

---

## 📌 Creating a Date Table in Power BI  

### **Step 1: Create a Date Table using DAX**
Open Power BI and enter the following DAX formula to create a date table:  



```DAX
Date = CALENDAR ( DATE(2017, 1, 1), DATE(2021, 12, 31) )
![image](https://github.com/user-attachments/assets/8b8ca203-af62-4d8e-939a-224deaa0bda3)

![image](https://github.com/user-attachments/assets/46a19d62-d17b-4cfc-9986-b3bbd5416235)

![image](https://github.com/user-attachments/assets/0ce6bccc-42e1-4fcf-a9b8-1f762e588c88)

![image](https://github.com/user-attachments/assets/1067576c-628c-4247-9d54-c4a487eb0450)


📢 **Connect with Me**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/susan-augustus-778827109/)
