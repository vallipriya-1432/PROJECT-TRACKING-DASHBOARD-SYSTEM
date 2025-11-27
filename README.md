# Project Tracking & Dashboard System 

## 📌 Overview
This project simulates a complete Project Portfolio Management (PMO) dashboard system, designed from the perspective of a Project Coordinator / PMO Analyst.  
It covers project portfolio health, milestone delivery performance, risk exposure, and issue management.

The dashboard is built using real PMO-style logic and provides insights used in governance meetings, steering committees, and weekly project reviews.

---

## 🎯 Key Objectives
- Track the status of multiple projects across a portfolio  
- Monitor milestone slippage and delivery performance  
- Identify and manage risks and issues  
- Provide clear portfolio-level KPIs to leadership  
- Centralize project health, RAG status, timelines, and blockers  
- Present insights in a clean and professional BI dashboard  

---

## 📂 Dataset Structure

The project uses a Power BI model built from four interconnected tables:

### **1. Projects**
Includes high-level portfolio information:
- Project_ID  
- Project_Name  
- Sponsor  
- Project_Manager  
- Start_Date & End_Date  
- Budget_kEUR  
- Status (On Track, At Risk, Delayed, Complete)  
- RAG_Status (Red, Amber, Green)  
- Portfolio group  

---

### **2. Milestones**
Milestones belonging to each project:
- Milestone_ID  
- Project_ID  
- Milestone_Name  
- Planned_Date  
- Actual_Date  
- Owner  
- Status  
- Slippage (calculated in DAX)  

---

### **3. Risks**
Risk log for each project:
- Risk_ID  
- Project_ID  
- Risk_Title  
- Severity  
- Impact  
- Status (Open, Mitigated, Closed)  
- Owner  
- Identified_Date  

---

### **4. Issues**
Issue log including severity and resolution:
- Issue_ID  
- Project_ID  
- Issue_Title  
- Severity (Low to Critical)  
- Status  
- Owner  
- Raised_Date  
- Resolved_Date  

---

## 🖥️ Dashboard Pages

### **Page 1 — Portfolio Overview**
Provides a high-level snapshot of project health:
- KPIs for Total Projects, On Track, At Risk, Delayed, Budget  
- RAG Status Breakdown (Donut)  
- Projects by Sponsor  
- Portfolio Timeline View  
- Project Health Table (PMO format)  

---

### **Page 2 — Milestone Tracking**
Tracks delivery progress and delays:
- Milestone KPIs (Completed, On-Time, Delayed)  
- Status Breakdown  
- Slippage Analysis  
- Milestone Timeline  
- Detailed Milestone Table with slippage days  

---

### **Page 3 — Risk & Issue Management**
Shows portfolio risk exposure and blockers:
- Risk KPIs (Open, Closed, High Severity)  
- Issue KPIs (Critical, Open, Resolved)  
- Severity Heatmap (Risks)  
- Issue Trend Over Time  
- Detailed Risk Register  
- Detailed Issue Register  

---

## 🛠️ Tools & Techniques
- **Microsoft Power BI Desktop**  
- **Power Query** (data cleaning & modeling)  
- **DAX Measures** for KPIs, slippage, risk severity  
- **Data Modeling** using one-to-many relationships  
- Professional PMO-style dashboard design  

---

## ✨ What This Project Demonstrates
- Real-world PMO reporting capabilities  
- Project portfolio monitoring  
- Risk & issue governance  
- Milestone delivery tracking  
- Capacity to build multi-page BI dashboards  
- Practical understanding of project coordination processes  

---



