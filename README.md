# Employee_Daily_Tracking_System
Real-Time Employee Attendance, Payroll and Productivity Analytics System built using KoboToolbox Mobile Data Collection, REST API Integration and Microsoft Power BI.
# Employee Daily Tracking System

A real-time employee attendance, payroll and productivity analytics solution built with **KoboToolbox**, **Power BI**, and **Power Query**.

This project demonstrates how mobile-collected workforce data can automatically flow into Power BI to produce interactive dashboards for HR managers and business executives.

---

## Project Overview

The Employee Daily Tracking System allows organizations to monitor:

- Employee attendance
- Shift schedules
- Hours worked
- Payroll
- Transport expenses
- Productivity
- Job categories
- Agency performance
- Efficiency KPIs

Data is collected on mobile devices using KoboCollect and synchronised automatically with KoboToolbox.

Power BI connects directly to the KoboToolbox API for near real-time reporting.

---

## System Architecture

Employee

↓

KoboCollect Mobile App

↓

KoboToolbox Cloud

↓

REST API

↓

Power Query

↓

Power BI Data Model

↓

Interactive Dashboard

---

## Technologies Used

- KoboToolbox
- KoboCollect
- REST API
- Power Query (M)
- Power BI
- DAX
- Excel
- Data Modelling

---

## Dashboard Features

### Attendance Monitoring

- Daily attendance
- Monthly attendance
- Shift attendance
- Attendance trend

### Payroll

- Hours Worked
- Hours Paid
- Average Pay per Hour
- Estimated Net Pay

### HR Analytics

- Shift Category
- Job Type
- Shift Period
- Agency Performance
- Company Performance

### Financial Analytics

- Transport Expenses
- Average Transport Cost
- Cost per Shift

### Productivity

- Productivity Index
- Efficiency Classification
- High vs Medium Performance

---

## KPIs

✔ Shift Attended

✔ Hours Worked

✔ Hours Paid

✔ Average Pay

✔ Average Hours

✔ Transport %

✔ Overtime %

✔ Full Shift %

✔ Estimated Salary

✔ Productivity Score

---

## Data Collection

Field workers complete attendance using KoboCollect.

Captured information includes:

- Employee Name
- Date
- Start Time
- End Time
- Shift
- Job Type
- Company
- Agency
- Route
- Transport Cost
- Productivity
- Pay Rate

---

## Power BI Components

### Data Model

- Fact Table
- Date Table
- Measures Table

### DAX Measures

Examples:

Total Hours Worked

Total Hours Paid

Shift Count

Average Pay

Average Hours

Transport %

Full Shift %

Overtime %

Productivity Score

Efficiency %

Estimated Salary

---

## Dashboard Pages

Executive Dashboard

Attendance Analysis

Payroll Analysis

Agency Performance

Company Performance

Employee Performance

Transport Analysis

Monthly Trends

---

## Repository Structure

Employee-Daily-Tracking-System/

│

├── README.md

├── Dashboard/

│ ├── Employee_Daily_Tracking.pbix

│ ├── Dashboard_Screenshot.png

│

├── Data/

│ ├── Sample_Data.xlsx

│ ├── Data_Dictionary.xlsx

│

├── KoboToolbox/

│ ├── XLSForm.xlsx

│ ├── API_Connection.md

│

├── PowerQuery/

│ ├── API_Query.m

│ ├── Transformations.md

│

├── DAX/

│ ├── Measures.md

│ ├── KPIs.md

│

├── Documentation/

│ ├── Architecture.png

│ ├── ERD.png

│ ├── Dashboard_Guide.pdf

│

└── Images/

Dashboard.png

Kobo_Data.png

Architecture.png
