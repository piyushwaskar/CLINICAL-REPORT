# CLINICAL-REPORT

## Clinical Provider Cost and Service Analysis Report 

This Power BI project provides a detailed analysis of healthcare service costs, treatment types, patient demographics, and departmental billing performance. It helps stakeholders understand the distribution of healthcare services across regions, identify high-cost areas, and make data-driven decisions for financial and operational improvements. The report includes interactive visuals like KPIs, bar charts, maps, and filters for year, quarter, month, race, and region. Built on a clean star schema with centralized DAX measures, it also features a dark/light mode toggle to enhance user experience and accessibility.

---

## Project Objective
To analyze healthcare service costs, patient treatment types, and departmental billing across locations using interactive visualizations, DAX measures, and geospatial mapping.

---

## Tools & Technologies Used
- **Power BI** – Dashboard building, Data Modeling  
- **DAX (Data Analysis Expressions)** – Custom KPIs and Measures  
- **Microsoft Bing Maps** – Geo Visuals  
- **Synthetic Healthcare Dataset** – Patient visits, departments, diagnoses, insurance, etc.

---

## Report Pages and Visuals
- KPI Tiles (Billing, Medication, Treatment, Insurance, Room Charges)
- Bar Charts: By Procedure, By Department
- Stacked Bars: Billing by Diagnosis & Service Type
- Bing Maps: Billing by City & State
- Year/Quarter/Month & Race slicers
  
- **Light/Dark Mode Switch**

**Light Theme**  
![![Healthcare DAshboard Light](https://github.com/user-attachments/assets/be9bb386-5439-44e6-b727-4f455ec25283)
]


**Dark Theme**  
![![Healthcare dashboard dark](https://github.com/user-attachments/assets/cbcbcdaf-31a9-434e-82ab-5a11d30a3049)


## Data Model (Star Schema)
The data model follows a clean star schema design:
- Central **Fact Table**: Visits
- **Dimension Tables**: patients, providers, procedures, departments, insurance, diagnoses, cities, Date_Table, Patient Location Switch

 **Data Model Image**  
![Data Model](![Data Model of Healthacre](https://github.com/user-attachments/assets/adfc2694-f7bc-49f7-9477-20b21f7b44c2)
]

---

## Important DAX Measures
- Total_Billing_Cost
- Total_Insurance
- Total_Medication
- Total_Treatment
- Out_Of_Pocket
- Average Room Charge
- % Department, % Procedure
- Total_patient

---

## Key Insights
- **X-Ray** has the highest billing among procedures  
- **Orthopedics & Cardiology** are top departments  
- **Asthma, Fracture** are high in emergency/outpatient  
- **London & Glasgow** have highest regional billing  

---

## Business Value Delivered
- Helps budget medications and treatments efficiently  
- Optimizes department-wise service performance  
- Supports geographic planning for expansion  
- Aids strategic decisions in hospital operations

---

## Project Highlights
- Dynamic Dark/Light Mode toggle  
- Clean, efficient star schema  
- Central DAX Measure Table  
- Slicers for advanced filtering  
- Interactive and modern UI layout  
