# excel_project_p2
Interactive Insurance Claims Analysis Dashboard built in Excel using 500 sample records. It covers data cleaning, calculation of key metrics like Claim Approval Ratio, Policy Duration, and High-Value Flags, and visualization through PivotTables and dynamic charts for actionable business insights.

#  Insurance Claims Analysis Dashboard (Excel Project)

##  Overview
This project presents an interactive **Insurance Claims Analysis Dashboard** created entirely in Microsoft Excel.  
It demonstrates how raw insurance data can be cleaned, structured, and analyzed to uncover trends and insights related to claim performance and policy behavior.

---

## Dataset Description
The dataset consists of **500 sample insurance policy records**, including:
- **Policy_ID** — Unique identifier for each policy  
- **Customer_Name** — Policyholder name  
- **Policy_Type** — Health, Motor, Life, or Travel  
- **Region** — Location of the policy  
- **Claim_Amount** and **Approved_Amount**  
- **Claim_Status** — Approved, Pending, or Rejected  
- **Claim_Date**, **Policy_Start_Date**, **Policy_End_Date**  
- **Gender**, **Age**, and **Premium_Amount**

---

## Steps & Process
1. **Data Cleaning**
   - Removed duplicates and corrected data formats  
   - Handled missing or zero values  
   - Ensured date and currency consistency  

2. **Data Preparation**
   - Added calculated columns such as:  
     - Claim Approval Ratio  
     - Policy Duration (in days)  
     - Claim Age (days since claim)  
     - High-Value Claim Flag (for claims above ₹50,000)

3. **Data Analysis**
   - Used **PivotTables** to summarize claim trends by region, policy type, and status  
   - Created dynamic **charts and graphs** for visual comparison  

4. **Dashboard Creation**
   - Designed an interactive Excel dashboard integrating multiple visuals  

---

## Tools & Techniques Used
- **Microsoft Excel**  
- PivotTables & Charts  
- Formulas: `IF`, `DATEDIF`, `ROUND`, etc.  

---

## Learning Outcome
This project demonstrates practical Excel-based data analysis, transforming raw insurance data into an insightful and visually interpretable dashboard — a valuable skill for **Data Analysts, Business Analysts, and Insurance Professionals**.

---

## 📂 File Information
- `Insurance_Claims_Analysis_Project.xlsx` → Main Excel dashboard and dataset  
- `README.md` → Project description and documentation  

