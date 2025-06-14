# CLINICAL-REPORT
## Clinical Provider Cost and Service Analysis Report 

# 🏥 Healthcare Cost & Service Analysis Dashboard

This Power BI project analyzes healthcare service costs, treatment types, patient demographics, and departmental billing performance. It helps stakeholders understand the distribution of healthcare services, regional cost variation, and areas for financial optimization.

---

## 📌 Project Objective
To analyze healthcare service costs, patient treatment types, and departmental billing across locations using interactive visualizations, DAX measures, and geospatial mapping.

---

## ⚙️ Tools & Technologies Used
- **Power BI** – Dashboard building, Data Modeling  
- **DAX (Data Analysis Expressions)** – Custom KPIs and Measures  
- **Microsoft Bing Maps** – Geo Visuals  
- **Synthetic Healthcare Dataset** – Patient visits, departments, diagnoses, insurance, etc.

---

## 🧱 Data Model (Star Schema)
The data model follows a clean star schema design:
- Central **Fact Table**: `visits`
- **Dimension Tables**: `patients`, `providers`, `procedures`, `departments`, `insurance`, `diagnoses`, `cities`, `Date_Table`, `Patient Location Switch`

📷 **Data Model Image**  
![Data Model](./Data%20Model%20of%20Healthacre.PNG)

---

## 📊 Report Pages and Visuals
- KPI Tiles (Billing, Medication, Treatment, Insurance, Room Charges)
- Bar Charts: By Procedure, By Department
- Stacked Bars: Billing by Diagnosis & Service Type
- Bing Maps: Billing by City & State
- Year/Quarter/Month & Race slicers
- **Light/Dark Mode Switch**

🌙 **Dark Theme**  
![Dark Mode](./Healthcare%20dashboard%20dark.PNG)

🌞 **Light Theme**  
![Light Mode](./Healthcare%20DAshboard%20Light.PNG)

---

## 📐 Important DAX Measures
- `Total_Billing_Cost`
- `Total_Insurance`
- `Total_Medication`
- `Total_Treatment`
- `Out_Of_Pocket`
- `Average Room Charge`
- `% Department`, `% Procedure`
- `Total_patient`

---

## 📈 Key Insights
- **X-Ray** has the highest billing among procedures  
- **Orthopedics & Cardiology** are top departments  
- **Asthma, Fracture** are high in emergency/outpatient  
- **London & Glasgow** have highest regional billing  

---

## 🎯 Business Value Delivered
- Helps budget medications and treatments efficiently  
- Optimizes department-wise service performance  
- Supports geographic planning for expansion  
- Aids strategic decisions in hospital operations

---

## 🌟 Project Highlights
- Dynamic Dark/Light Mode toggle  
- Clean, efficient star schema  
- Central DAX Measure Table  
- Slicers for advanced filtering  
- Interactive and modern UI layout  
