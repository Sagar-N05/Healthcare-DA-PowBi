# Hospital Patient Insights Dashboard

This Power BI dashboard provides a detailed overview of hospital operations, focusing on patient admissions, billing, and demographic insights. It is designed for healthcare administrators, analysts, and stakeholders to make data-driven decisions.

---

## Page 1: Admissions and Length of Stay (LOS) Overview

This page highlights trends and statistics related to patient admissions and their average length of stay.

### Filters
- Gender
- Admission Type
- Insurance Provider

### Visuals

| Area         | Visual Type  | Description |
|--------------|--------------|-------------|
| Top Left     | Slicer       | Filter data by Gender |
| Top Middle   | Slicer       | Filter data by Admission Type |
| Top Right    | Slicer       | Filter data by Insurance Provider |
| Left Panel   | KPI Card     | Displays the Average Length of Stay (LOS) |
| Middle       | Bar Chart    | Average LOS per Medical Condition |
| Right        | Line Chart   | Monthly trend of Average LOS |
| Bottom       | Matrix       | Average LOS by Doctor and Month of Admission |

---

## Page 2: Cost and Billing Insights

This section presents billing metrics to evaluate financial aspects of hospital services.

### Filters
- Hospital
- Doctor

### Visuals

| Area         | Visual Type   | Description |
|--------------|---------------|-------------|
| Top Left     | Slicer        | Filter data by Hospital |
| Top Right    | Slicer        | Filter data by Doctor |
| Left         | Card Visual   | Shows the Total Billing Amount |
| Middle       | Bar Chart     | Average Billing Amount by Insurance Provider |
| Right        | Scatter Plot  | Billing Amount by Age, color-coded by Gender |
| Bottom       | Matrix        | Billing Amount by Medical Condition and Insurance Provider |

---

## Page 3: Patient Demographics and Conditions

This page provides insights into the demographic profiles and medical conditions of patients.

### Filters
- Medical Condition
- Blood Type

### Visuals

| Area         | Visual Type   | Description |
|--------------|---------------|-------------|
| Top          | Slicers       | Filter data by Medical Condition and Blood Type |
| Left         | Donut Chart   | Patient distribution by Gender |
| Middle       | Bar Chart     | Number of Patients per Medical Condition |
| Right        | Stacked Bar   | Patient counts by Admission Type and Gender |

---

## Notes

- All visuals are interactive and update based on slicer selections.
- The dashboard is optimized for use in Power BI Desktop and Power BI Service.
- Ideal for understanding patient flow, healthcare costs, and demographic patterns in a hospital setting.
