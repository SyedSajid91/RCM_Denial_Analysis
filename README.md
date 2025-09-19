<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/1f42522e-176f-4f06-be75-1c82d7fd5081" />
# 📊 Case Study: RCM Claim Denial & AR Days Analysis  

![Excel](https://img.shields.io/badge/Tool-Excel-blue?logo=microsoft-excel)
![Case Study](https://img.shields.io/badge/Type-RCM%20Case%20Study-green)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Dataset](https://img.shields.io/badge/Dataset-Synthetic-orange)
![Open%20to%20Collab](https://img.shields.io/badge/Open%20to-Collaboration-yellow)


## 🔹 Case Study Overview  
This case study analyzes **claim denial patterns and AR (Accounts Receivable) days** for a healthcare provider.  
The goal is to identify **revenue leakage, high denial categories, payer inefficiencies, and AR delays** using Excel.  

---

## 🔹 Business Problems Addressed  
1. Rising denial rates across departments  
2. Increase in AR aging (delayed payments)  
3. High-dollar denials impacting cash flow  
4. Seasonal/monthly spikes in denials  
5. Payer performance comparison (denial %, AR Days, paid vs denied)  

---

## 🔹 Dataset Description  
- **ClaimID** – Unique claim identifier  
- **Department** – Radiology, Surgery, OPD, Cardiology, Orthopedics  
- **ClaimType** – Inpatient, Outpatient, Emergency  
- **Payer** – Aetna, BCBS, Cigna, Commercials, Tricare, WorkersComp  
- **SubmissionDate** – Date claim submitted  
- **PaymentDate** – Date claim processed/paid (blank if denied)  
- **Status** – Paid / Denied  
- **DenialReason** – Reason for denial (if applicable)  
- **Amount** – Claim value in USD  

📂 [Dataset Excel File](CaseStudy_RCM.xlsx)  

---

## 🔹 Approach & Methods  
- **Excel Calculations**:  
  - AR Days = Payment Date – Submission Date  
  - Denial % = (Denied Claims ÷ Total Claims) × 100  
- **Pivot Tables** for Denial Reason, Department, Claim Type, Payer  
- **Charts**:  
  - Line chart – Denial trends over months  
  - Bar chart – Top 5 denial reasons  
  - Heatmap – AR Days by Department vs Payer  
- **Dynamic Insight Box** linked to slicers for automated text insights  

---

## 🔹 Dashboard Screenshots  
👉<img width="564" height="270" alt="image" src="https://github.com/user-attachments/assets/0b4b69f4-489c-4faa-bacc-ee6db0fe18f1" />
  


- **Denial Reasons Breakdown**  
 👉 <img width="287" height="192" alt="image" src="https://github.com/user-attachments/assets/20c11054-cbd2-45a5-9962-54ba9f7f1922" />
     <img width="254" height="357" alt="image" src="https://github.com/user-attachments/assets/80048b26-9c13-48f0-8eab-0903db08b29e" />

  
- **Payer Performance Comparison**  
 <img width="381" height="140" alt="image" src="https://github.com/user-attachments/assets/43a3aca6-2549-4b69-a269-88d5b559c0a1" />
 <img width="558" height="269" alt="image" src="https://github.com/user-attachments/assets/ff3556de-b4d0-4683-81e4-fbccbb224a13" />


---

## 🔹 Key Insights  
- Overall **denial rate: 27%**  
- **Top 3 denial reasons**:  
  - Incomplete Documentation – $125,885  
  - Late Submission – $204,672  
  - Policy Exclusion – $208,693  
- **Surgery Department** had the **highest denial %**  
- **Aetna & Commercials** = **55%+ of total denied amount**  
- Seasonal denial spikes observed → process lapses  

---

## 🔹 Outcome  
The analysis helped the hospital to:  
- Identify **root causes of denials** (documentation, policy compliance, submission delays)  
- Pinpoint **slow-paying payers** and **high-dollar denials**  
- Build a **data-driven dashboard** for RCM leadership to monitor KPIs and take corrective actions  

---

## 🔹 Tools Used  
- **Excel** – Pivot Tables, Charts, Slicers, Conditional Formatting  
- **Data Size** – 100 claims (synthetic dataset for analysis)  
- **Visualization Techniques** – Line, Bar, Heatmap, KPI Cards  

---

## 🔹 How to Use This Project  
1. Download the dataset: [CaseStudy_RCM.xlsx](./CaseStudy_RCM.xlsx)  
2. Open in Excel  
3. Explore the Pivot Tables and Dashboard  
4. Adjust slicers to view dynamic insights  

---

## 🔹 Author  
👤 *Syed Sajid Hussain*  
- 💼 Data Analyst | RCM Knowledge | Excel & BI Solutions  
- 🔗 [LinkedIn Profile](https://linkedin.com/in/yourprofile)  
- 📂 [Portfolio Repository](https://github.com/SyedSajid91)  

---
