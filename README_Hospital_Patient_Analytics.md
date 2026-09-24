# Hospital Patient Analytics Dashboard

## 📊 Project Overview

The **Hospital Patient Analytics Dashboard** is an interactive Power BI project designed to analyze hospital patient data and provide a clear view of patient volume, billing, stay duration, recovery outcomes, demographics, departments, diagnoses, and other operational indicators.

The dashboard is built to help hospital management and analysts explore patient trends and compare performance across departments, outcomes, age groups, and admission periods.

---

## 🎯 Project Objectives

- Monitor the total number of patients.
- Analyze total hospital billing.
- Measure average patient stay duration.
- Track patient recovery/outcome percentages.
- Analyze patients by department.
- Understand patient outcome distribution.
- Analyze patient trends over admission months and years.
- Compare patient volume across age groups.
- Analyze billing by department.
- Study patient demographics such as gender and age.
- Analyze diagnoses and length-of-stay categories.
- Provide detailed patient-level information for deeper investigation.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard development and visualization
- **Power Query** – Data preparation and transformation
- **DAX** – Measures and KPI calculations
- **Data Modeling** – Analytical model for patient data
- **Excel/CSV-style tabular data** – Source data structure

---

## 📁 Data Model

The Power BI report uses a patient dataset represented by the **Patients** table.

### Main Fields

| Category | Fields |
|---|---|
| Patient | Patient_ID |
| Demographics | Age, Gender, Age_Group |
| Hospital | Department, Doctor |
| Medical | Diagnosis, Outcome |
| Admission | Admitted Month, Admitted Year |
| Stay | Stay_Days, Stay_Category |
| Financial | Bill_Amount |

---

## 📌 Key KPIs

The dashboard contains the following major KPIs/measures:

- **Total Patients**
- **Total Billing**
- **Average Stay**
- **Recovered %**
- **Average Age**
- **Maximum Stay**
- **Average Bill**

These KPIs provide a high-level summary before users move into detailed analysis.

---

# 📄 Dashboard Pages

## 1. Hospital Overview

The **Hospital Overview** page provides a high-level summary of hospital operations.

### KPI Cards
- Total Patients
- Total Billing
- Average Stay
- Recovered %

### Visual Analysis
- Patient count by Department
- Patient outcomes distribution
- Patient trend by Admitted Month
- Patient count by Age Group
- Billing by Department

### Filters / Slicers
- Gender
- Department
- Admitted Year

### Purpose

This page is designed as the main management overview, allowing users to quickly understand patient volume, billing, stay patterns, department-level activity, and outcomes.

---

## 2. Patient Detailed Analysis

The **Patient Detailed Analysis** page focuses on demographic, medical, and stay-related analysis.

### KPI Cards
- Average Age
- Maximum Stay
- Average Bill

### Visual Analysis
- Patients by Age Group
- Patients by Department and Outcome
- Patients by Diagnosis
- Patients by Stay Category

### Filters / Slicers
- Department
- Outcome

### Purpose

This page allows analysts to investigate the characteristics of patients and understand how departments, diagnoses, outcomes, and length of stay are distributed.

---

## 3. Patients Details

The **Patients Details** page provides a more detailed patient-level view.

### Summary Cards
- Average Age
- Average Stay Days
- Average Bill Amount

### Detailed Table

The table provides patient-level information including:

- Patient ID
- Age
- Gender
- Department
- Diagnosis
- Doctor
- Stay Days
- Bill Amount
- Outcome

### Additional Analysis

A department-based patient summary is also provided to support further comparison.

### Purpose

This page is useful when a user needs to move from aggregated dashboard insights to individual patient records and detailed analysis.

---

# 📈 Dashboard Insights

The report supports analysis of several important hospital questions:

### Patient Volume
- How many patients are being handled?
- Which departments have higher patient volumes?
- How does patient volume change across age groups?

### Financial Analysis
- What is the total billing amount?
- Which departments generate higher billing?
- What is the average bill per patient?

### Patient Stay Analysis
- What is the average length of stay?
- What is the maximum stay?
- How are patients distributed across stay categories?

### Outcome Analysis
- What proportion of patients recovered?
- How are outcomes distributed?
- How do outcomes vary by department?

### Demographic Analysis
- What is the average patient age?
- How are patients distributed by gender?
- Which age groups have higher patient volumes?

### Medical Analysis
- Which diagnoses are most common?
- How are diagnoses distributed across patients?
- How do departments and outcomes relate to patient volume?

---

# 🔄 User Interaction

The report is designed to be interactive. Users can select slicer values and explore how the charts and KPIs change based on the selected filters.

Typical analysis flow:

**Overview → Filter → Compare → Investigate → Patient Details**

For example:

1. Select a department.
2. Review the change in total patients and billing.
3. Compare outcomes and age groups.
4. Analyze diagnoses or stay categories.
5. Open the patient details page for record-level information.

---

# 🧮 DAX Measures

The report uses DAX measures for KPI calculations, including measures such as:

- Total Patients
- Total Billing
- Average Stay
- Recovered %
- Average Age
- Maximum Stay
- Average Bill

The measures are used throughout the report to keep KPI calculations consistent across different visualizations and filters.

> Note: The exact DAX expressions are maintained inside the Power BI model. This README documents the analytical purpose of the measures rather than duplicating the model code.

---

# 🎨 Dashboard Design

The report uses a multi-page dashboard structure:

1. **Hospital Overview** – Executive-level summary
2. **Patient Detailed Analysis** – Analytical exploration
3. **Patients Details** – Record-level investigation

The report also uses custom visual styling/background resources to provide a consistent dashboard presentation.

---

# 💼 Business Use Cases

This dashboard can be used by:

- Hospital Management
- Healthcare Operations Teams
- Data Analysts
- Department Managers
- Business Intelligence Teams

Potential business applications include:

- Monitoring patient volumes
- Department performance analysis
- Billing analysis
- Patient stay analysis
- Outcome monitoring
- Demographic analysis
- Operational reporting
- Data-driven hospital decision support

---

# 🧠 Skills Demonstrated

This project demonstrates practical skills in:

- Power BI Dashboard Development
- Data Visualization
- Power Query
- DAX Measures
- KPI Development
- Data Modeling
- Slicer and Filter Design
- Healthcare Data Analysis
- Exploratory Data Analysis
- Business Intelligence
- Interactive Reporting
- Patient-level Data Analysis

---

# 📂 Project Structure

```text
Hospital-Patient-Analytics/
│
├── README.md
├── power bi 15-09.pbix
└── Dataset/
    └── Patients data
```

> The dataset file is not included in this README package unless it is separately provided.

---

# 🚀 How to Open the Project

1. Install **Microsoft Power BI Desktop**.
2. Open the `.pbix` file.
3. Review the **Hospital Overview** page.
4. Explore **Patient Detailed Analysis**.
5. Use **Patients Details** for record-level analysis.
6. Interact with slicers and visuals to explore the data.

---

# 📌 Project Summary

**Project:** Hospital Patient Analytics Dashboard  
**Tool:** Microsoft Power BI  
**Domain:** Healthcare Analytics  
**Dataset:** Patients  
**Dashboard Pages:** 3  
**Primary Focus:** Patient volume, billing, demographics, stay duration, diagnoses, departments, and outcomes

This project demonstrates how Power BI can transform hospital patient data into an interactive business intelligence dashboard for operational and analytical decision-making.

---

## 👤 Portfolio Description

**Hospital Patient Analytics Dashboard | Power BI**

Developed an interactive Power BI dashboard to analyze hospital patient volume, billing, demographics, length of stay, diagnoses, departments, and patient outcomes. Created KPI cards, department and outcome analysis, admission trends, age-group analysis, billing analysis, slicers, and patient-level detail views using Power Query, DAX, and Power BI visualization techniques.
