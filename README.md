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



📢 **Connect with Me**  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/susan-augustus-778827109/)
