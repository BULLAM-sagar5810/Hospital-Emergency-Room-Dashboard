# 🏥 Hospital Emergency Room Analysis Dashboard – Power BI
<img width="1309" height="467" alt="స్క్రీన్‌షాట్ 2026-06-18 095540" src="https://github.com/user-attachments/assets/eef87e92-cdd5-406e-81da-955aac3214c3" />

End-to-End Healthcare Analytics Dashboard | Power BI | Power Query | DAX | Data Modeling

![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Data%20Source-green?logo=microsoftexcel)
![DAX](https://img.shields.io/badge/DAX-Analytics-blue)
![Power Query](https://img.shields.io/badge/PowerQuery-ETL-orange)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 📌 Project Overview

This project focuses on developing a Hospital Emergency Room Analysis Dashboard in Power BI to improve operational efficiency and support better decision-making.

The dashboard provides stakeholders with a centralized view of emergency room performance and helps monitor patient flow, waiting time, department referrals, and patient satisfaction.

The objective is to transform raw hospital data into meaningful insights for improving hospital operations and patient management.

---

# 🎯 Business Objective

The purpose of this project is to create a Hotspot Emergency Room Analysis Dashboard to:

- Monitor emergency room performance
- Improve patient management efficiency
- Track patient admissions
- Reduce waiting time
- Improve patient satisfaction
- Support data-driven decisions

---

# 📊 Dashboard KPIs

| KPI | Description |
|------|------------|
| Total Patients | Number of ER visits |
| Average Wait Time | Average patient waiting duration |
| Patient Satisfaction Score | Patient experience measurement |
| Admission Rate | Admitted vs Non-admitted |
| Gender Analysis | Patient demographic insights |
| Department Referrals | Referral tracking |

---

# 📈 Dashboard Visualizations

### 1. Patient Admission Chart
Admission vs Non-admission analysis

### 2. Patient Age Distribution
Age segmentation analysis

### 3. Timeline Analysis
Patient trend analysis over time

### 4. Gender Analysis
Male and female patient comparison

### 5. Department Referrals
Department-wise referral analysis

---

# 🛠️ Project Workflow

## Phase 1 – Business Requirement Gathering
- Gather stakeholder requirements
- Define KPIs

## Phase 2 – Understanding Data
- Review dataset
- Understand data relationships

## Phase 3 – Data Connection
- Import data into Power BI

## Phase 4 – Data Preparation
- Power Query transformations
- Data cleaning
- Data quality validation

## Phase 5 – Data Modeling
- Build relationships
- Create data model

## Phase 6 – DAX Calculations
- Calculated columns
- Measures

## Phase 7 – Dashboard Development
- Dashboard layout
- Visual formatting

## Phase 8 – Insights Creation
- Business insights
- Recommendations

## Phase 9 – Documentation & Presentation
- Project documentation
- PPT creation

---

# 📂 Repository Structure

Hospital-Emergency-Room-Analysis/

├── README.md

├── Dashboard/
│   ├── Hospital_ER_Dashboard.pbix
│   └── Dashboard_Screenshots/
│       ├── Dashboard_Overview.png
│       ├── Patient_Admission.png
│       ├── Age_Distribution.png
│       ├── Timeline_Analysis.png
│       ├── Gender_Analysis.png
│       └── Department_Referrals.png

├── Dataset/
│   └── Hospital Emergency Room Data.xlsx

├── Documentation/
│   ├── Hospital_ER_Project_Documentation.docx
│   └── Presentation.pptx

├── DAX/
│   ├── Measures.md
│   └── Calculated_Columns.md

├── Images/
│   ├── Dashboard_Cover.png
│   └── Architecture.png

└── LICENSE

---

# 🖼️ Screenshots

## Dashboard Overview

![Dashboard](./Images/Dashboard_Cover.png)

---

## Patient Admission

![Admission](./Dashboard/Dashboard_Screenshots/Patient_Admission.png)

---

## Age Distribution

![Age Distribution](./Dashboard/Dashboard_Screenshots/Age_Distribution.png)

---

## Timeline Analysis

![Timeline](./Dashboard/Dashboard_Screenshots/Timeline_Analysis.png)

---

## Gender Analysis

![Gender](./Dashboard/Dashboard_Screenshots/Gender_Analysis.png)

---

## Department Referrals

![Department Referrals](./Dashboard/Dashboard_Screenshots/Department_Referrals.png)

---

# 📌 Sample DAX Measures

### Total Patients

```DAX
Total Patients =
COUNT(Patients[Patient_ID])
```

### Average Wait Time

```DAX
Average Wait Time =
AVERAGE(Patients[Wait_Time])
```

### Patient Satisfaction Score

```DAX
Patient Satisfaction =
AVERAGE(Patients[Satisfaction_Score])
```

---

# 📊 Key Insights

- Identified patient admission trends
- Reduced visibility gaps in wait time
- Improved department referral analysis
- Supported operational decisions
- Enhanced patient management

---

# 🚀 How to Run

1. Clone Repository

```bash
git clone https://github.com/yourusername/Hospital-Emergency-Room-Analysis.git
```

2. Open Power BI Desktop

3. Open `.pbix` file

4. Refresh Dataset

5. Explore Dashboard

---

# 🧰 Tools & Technologies

- Power BI
- Power Query
- DAX
- Excel
- Data Modeling
- Dashboard Design

---

# 👨‍💻 Author

Bullam Sagar

GitHub: Add Your GitHub Profile

LinkedIn: Add Your LinkedIn Profile

---

# ⭐ Support

If you found this project useful, give it a star ⭐
