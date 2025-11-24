# UPI Transactions Dataset Analysis – Power BI Dashboard (2024)

### **🔗 Dashboard Link:** *Add your Power BI Service link here*

---

## 📌 Problem Statement

This dashboard provides a detailed analysis of **UPI transactions across Indian cities for the year 2024**.  
It enables stakeholders to explore:

- Monthly transaction volumes  
- Month-wise remaining balance  
- City-wise currency performance  
- High and low activity periods  
- User-based segmentation (Age Group, Bank, Merchant, Purpose, etc.)

Using slicers, synced filters, bookmarks, and conditional formatting, the dashboard helps users identify key behavioral and financial trends across UPI usage patterns.

---

## 🛠️ Steps Followed

### **Step 1 — Data Loading**
- Loaded the UPI Transactions Dataset (2024) into Power BI Desktop, containing:  
  Transaction Amount, Remaining Balance, City, Month, Banks, Merchant, Purpose, Payment Method, Age Group, Device Type, Gender & more.

---

### **Step 2 — Data Profiling**
- Opened Power Query Editor → Enabled:  
  ✔ Column Quality  
  ✔ Column Distribution  
  ✔ Column Profile  
- Profiled dataset *based on entire data*, not just top 1000 rows.

---

### **Step 3 — Data Cleaning**
- Ensured correct data types.
- Checked nulls and inconsistencies.
- Standardized month names, currency formats, and numeric formatting (K/M).

---

### **Step 4 — Data Modelling & Formatting**
- Verified relationships and data formats.
- Created additional measures for:
  - Monthly totals  
  - Balance tracking  
  - Trend evaluations  

---

### **Step 5 — Slicers (Filters) Added**
Interactive slicers included:

- BankNameSent  
- BankNameReceived  
- City  
- Device Type  
- Gender  
- Age Group  
- Merchant Name  
- Payment Method  
- Purpose  
- Transaction Type  

➡️ **All slicers synced across views using "Sync Slicer"**.

---

### **Step 6 — Dashboard Visuals Created**

#### **📍 A. City-Wise Table View (Multi-Currency)**
Displays:
- Monthly Transaction Amount  
- Remaining Balance  
- For Bangalore (EUR), Delhi (USD), Hyderabad (GBP), Mumbai (INR)  
- Includes conditional formatting  
- Screenshot:  
`/mnt/data/Table View.png`

---

#### **📍 B. Balance by Month — Column Chart**  
- Clean, modern layout  
- Values in Millions  
- Screenshot:  
`/mnt/data/Balance by Month (Column).png`

---

#### **📍 C. Balance by Month — Line Chart**  
- Smooth trend line  
- Shows high/low balance periods  
- Screenshot:  
`/mnt/data/Balance by Month (Line).png`

---

#### **📍 D. Transactions by Month — Column Chart**
- Shows overall transaction distribution  
- Screenshot:  
`/mnt/data/Transactions by Month (Column).png`

---

#### **📍 E. Transactions by Month — Line Chart**
- Month-over-month transaction trend  
- Screenshot:  
`/mnt/data/Transactions by Month (Line).png`

---

### **Step 7 — Conditional Formatting**
Applied to highlight:
- Higher values  
- Monthly spikes  
- City variances  

---

### **Step 8 — Bookmarks & Navigation**
Created interactive bookmarks for:
- **Transaction Trends**
- **Remaining Balance Trends**

Added bookmark buttons to toggle:
- Column charts  
- Line charts  

---

### **Step 9 — Theme & Layout**
- Purple theme  
- Aligned visuals  
- Added titles, borders & consistent typography

---

### **Step 10 — Publishing**
- Final dashboard published to Power BI Service for sharing & accessibility.

---

# 📸 Dashboard Snapshots
*(Add these screenshot paths after uploading)*

- Table View  
- Balance by Month (Column)  
- Balance by Month (Line)  
- Transactions by Month (Column)  
- Transactions by Month (Line)  

---

# 📊 Key Insights

### **1. Monthly Balance Trends**
- Peak: **June (~8.5M)**  
- Lower dips: **March & May (~8.2M)**  
- Overall stable around 8.3M–8.4M  

---

### **2. Monthly Transactions**
- High months: **May, February, October**  
- Lower activity: **August, July**

---

### **3. City Insights**
- **Mumbai (INR)** shows highest values.  
- **Hyderabad (GBP)** peaks in April & September.  
- **Delhi (USD)** stays moderate.  
- **Bangalore (EUR)** shows stable patterns.

---

### **4. User-Based Insights**
Filters reveal trends by:
- Bank  
- Merchant  
- Age Group  
- Device Type  
- Purpose  
- Payment Method  

---

## 🏁 Conclusion

This Power BI report provides an interactive and deep analysis of UPI transactions across various cities in India.  
With synced slicers, bookmarks, conditional formatting, and detailed visuals, it offers clear insights for strategic financial decision-making.

---

## ⭐ Technologies Used
- Power BI  
- DAX  
- Power Query  
- Data Modelling  
- Data Visualization  

---

## 📂 Future Scope
- Add YOY comparison  
- Predictive trends  
- Merchant performance deep-dive  

