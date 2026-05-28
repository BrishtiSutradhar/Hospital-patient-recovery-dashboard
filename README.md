# Hospital Patient Recovery Dashboard

An interactive, data-driven Excel dashboard designed to track, analyze, and visualize patient treatment outcomes, hospital stay efficiencies, and medical expenses across multiple clinical domains. 

This project transforms raw clinical datasets into high-level business intelligence insights to help hospital administrators and senior medical staff optimize patient care and resource allocation.

## 📊 Project Overview & Core Metrics
The analysis is built on a dataset of **200 patient records** spanning various age cohorts, treatment modes, and departments. The core institutional Key Performance Indicators (KPIs) calculated within this workbook include:
* **Average Recovery Score:** $\approx 70.38 / 100$
* **Average Treatment Cost:** $\approx \$79,698.51$
* **Average Length of Stay:** $\approx 16.02 \text{ days}$
* **Average Patient Age:** $\approx 41.71 \text{ years}$

---

## 🔍 Key Insights & Analytical Breakdown

The dashboard utilizes advanced Excel functions and pivot table modeling to break down patient outcomes across several critical dimensions:

### 1. Departmental Efficacy & Variance
* **Pediatrics** ($73.13$) and **Oncology** ($72.42$) maintain the highest average patient recovery scores.
* **Neurology** presents the lowest average recovery score ($66.39$), identifying a key clinical area for performance review and resource support.

### 2. Treatment Type Performance
* **Surgical Interventions** yield the highest recovery index ($\approx 73.29$), followed closely by **Therapy** ($70.98$).
* **Medication-only pathways** average the lowest recovery velocity ($67.58$).

### 3. Cohort & Demographic Distribution
* **Age Groups Analyzed:** Patients are segmented into 9 distinct lifespans (from *Infants* to *Oldest Seniors*). The **Old** age cohort ($65\text{--}74\text{ years}$) achieved the highest recovery velocity average of $74.13$.
* **Financial Impact:** Treatment costs are classified into categorical tiers (*High Cost* vs. *Low Cost*), demonstrating how operational expenses correlate directly with the recovery metric variance ($72.25$ recovery score for high-cost tracks vs. $68.26$ for low-cost tracks).

### 4. Practitioner Evaluation
* Tracks clinical outputs across 5 attending physicians (including *Dr. M. Patel*, *Dr. L. Khan*, etc.) to monitor case volumes, average recovery success rates, and medical stay trends per doctor.

---

## 🛠️ Excel Features Implemented
* **Advanced Pivot Tables & Data Modeling:** Structured multi-level fields to map metrics smoothly across complex categorical groups.
* **Data Segmentation:** Implementation of interactive Slicers and Timelines for responsive dashboard filtering (by Department, Doctor, Gender, and Age Group).
* **Descriptive Statistics:** Calculated statistical variance utilizing `AVERAGE`, `MIN`, and `STDEV` across sample medical outcomes.

---
Hospital_Patient_Recovery_Dashboard.xlsx
https://github.com/BrishtiSutradhar/Hospital-Patient-Recovery-Dashboard/blob/main/Hospital_Patient_Recovery_Dashboard.xlsx

hospital_patient_treatment_dataset.csv
https://github.com/BrishtiSutradhar/Hospital-Patient-Recovery-Dashboard/blob/main/hospital_patient_treatment_dataset.csv

Hospital_Patient_Recovery_Overview_Dashboard.PNG
https://github.com/BrishtiSutradhar/Hospital-Patient-Recovery-Dashboard/blob/main/Hospital_Patient_Recovery_Overview_Dashboard.PNG

## 📂  Files Included
```text
├── Excel file with complete Hospital Patient Recovery Dashboard(original, with data)

└── README.md                                 # Project documentation and summary

## 📁  Files Included

- **`Excel file with complete Bank Loan Report(original, with data)`**
-  <a href='https://github.com/BrishtiSutradhar/Financial-Loan-Data-Analysis-Excel-Dashboard/blob/main/Finance_Loan_Deshboard.xlsx'>Financial Loan Data Analysis Excel Dashboard.xlsx</a>

- **`Data source used for the analysis `**
-  <a href='https://github.com/BrishtiSutradhar/Hospital-Patient-Recovery-Dashboard/blob/main/hospital_patient_treatment_dataset.csv'>hospital_patient_treatment_dataset.csv</a>


## 📝 Screenshots / Samples

Show what the dashboard looks like. - ![Alt text](https://github.com/username/repo/assets/image.png)
Preview visuals available in [`Export/Bank Loan Report Summary Dashboard.png`]! & [`Export/Bank Loan Report Overview Dashboard.png`]

<img width="1131" height="576" alt="Screenshot 2026-02-13 212813" src="https://github.com/user-attachments/assets/e8f17731-46db-416d-9bdf-e79197323967" />
<img width="1144" height="591" alt="Screenshot 2026-02-13 212500" src="https://github.com/user-attachments/assets/6d02eacf-9c77-4220-b97b-a14e85d0461a" />

