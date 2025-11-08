🏥 Hospital Management Dashboard Using PowerBI and MSSQL
A comprehensive Power BI solution designed to analyze hospital operations across multiple dimensions including patient care, doctor performance, departmental efficiency, and financial health. 
This dashboard integrates live data from MSSQL to deliver real-time insights that support strategic healthcare decisions.

# Description
The Hospital Management Insights Dashboard enables hospital administrators and analysts to monitor key operational metrics, streamline data reporting, and enhance decision-making.
It provides a 360° view of hospital performance through interactive visuals covering patients, doctors, departments, and revenue helping management identify trends, optimize resources, and improve service quality.

# Tech Stack
• 📊 Power BI Desktop – Main platform for report building and data visualization.
• 🔄 Power Query Editor – Used for transforming, cleaning, and merging hospital data.
• 🧠 DAX (Data Analysis Expressions) – Created calculated measures and columns for Bills, doctor commissions, ratings and sales quantity.
• 🧱 Data Modeling – Established relationships among fact and dimension tables (e.g., Patient, Doctor, Department, Billing).
• 🗄️ Microsoft SQL Server (MSSQL) – Primary database for storing and managing hospital data, SQL views were created for optimized data import.
• 🔗 Power BI–MSSQL Integration – Established a live connection between MSSQL and Power BI to ensure data consistency and automated refreshes.

# Data Source

Source: Microsoft SQL Server Database (MSSQL)
The dataset consists of multiple relational tables and SQL views representing hospital operations including Doctor, Patient, Appointment, Department, and Bills.
Raw data was adapted from a Power BI YouTube tutorial, where the sample dataset was AI-generated for educational purposes. The dataset was further cleaned, structured, and integrated into MSSQL before connecting to Power BI.
Data transformations were performed using both SQL (views, joins, and cleaning queries) and Power Query Editor for additional reshaping and conditional logic before loading into Power BI.


# Features / Highlights

Business Problem
Hospitals generate vast amounts of data from patient visits and doctor performance to revenue tracking but struggle to analyze it efficiently.
Manual reporting methods lead to delayed decisions, lack of performance visibility, and limited insight into departmental effectiveness.

-- Goal of the Dashboard --

To build an interactive and data-driven solution that:

1. Automates hospital reporting and analytics.
2. Monitors financial and operational KPIs in real time.
3. Identifies top-performing doctors and departments.
4. Provides actionable insights for improving hospital management and resource allocation.

-- Walkthrough of Key Visuals --

🏠 Overview Page:

KPIs: Total Patients, Active Doctors, Total Revenue, Average Commission.

Trend Chart: Monthly patient inflow and revenue.

Slicers: Department, Doctor, and Date filters for cross-page analysis.

🩺 Doctor Dashboard:

Table: Patient's all appointments

Card Visuals: Total appointments and average commission percentage.

Guage: Shows commision rate.

👩‍⚕️ Patient Dashboard:

Matrix: Medicine Tracking by day and month.

Bar Chart: Medicine sale quantity and patient charges type.

Cards: Patient personal details .

Interactive navigation buttons, bookmarks, and slicers allow seamless movement across pages and real-time drill-through analysis.

# Business Impact & Insights

Operational Efficiency: Centralized reporting reduced manual data aggregation time.

Data Transparency: Improved visibility into patient flow, doctor productivity, and financial health.

Decision Support: Enabled quick identification of high-performing doctors and underutilized departments.

Strategic Planning: Helped management make informed decisions regarding staffing, budgeting, and service improvements.

# Screenshots / Demos

Patient Dashboard: https://github.com/Sneha-Padi0017/Hospital-Dashboard/blob/main/Patient_Dashboard.png
Doctor Dashboard: https://github.com/Sneha-Padi0017/Hospital-Dashboard/blob/main/Doctor_Dashboard.png


