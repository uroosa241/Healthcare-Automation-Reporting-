#  Healthcare Report Automation

A professional healthcare reporting automation project built using PostgreSQL, SQL, Python, and Power BI. This project automatically executes multiple SQL reports, exports the results into CSV files, and provides ready-to-use datasets for interactive Power BI dashboards.

---

#  Project Overview

This project simulates a real-world healthcare reporting environment where business reports are generated automatically from a PostgreSQL database.

The automation performs the following tasks:

- Connects to PostgreSQL
- Reads multiple SQL files automatically
- Executes healthcare business reports
- Exports each report into CSV format
- Creates execution logs
- Supports Power BI dashboards
- Can be scheduled using Windows Task Scheduler

---

#  Technologies Used

- PostgreSQL
- SQL
- Python
- Pandas
- psycopg2
- Power BI
- Windows Task Scheduler
- Git & GitHub

---

#  Project Structure

```
HealthcareReportAutomation/

│
├── sql/
│   ├── patient_analysis.sql
│   ├── doctor_analysis.sql
│   ├── appointment_analysis.sql
│
├── output/
│
├── logs/
│
├── report.py
├── config.py
├── requirements.txt
├── .gitignore
├── run_report.bat
└── README.md
```

---

#  Automated Reports

##  Patient Analysis

- Total Patients
- Male vs Female Patients
- Patients by Age Group
- Monthly Registrations
- Average Patient Age
- Repeat Patients
- Treatment Type Analysis
- Insurance Analysis
- Blood Group Analysis
- Senior Citizens
- Child Patients
- Patient Growth %
- Top Frequent Patients
- New vs Returning Patients

---

##  Doctor Analysis

- Total Doctors
- Doctors by Specialization
- Doctors by Hospital Branch
- Patients per Doctor
- Top Doctors
- Least Busy Doctors
- Average Patients per Doctor
- Appointments per Doctor
- Completed Appointments
- Cancelled Appointments
- No-show Appointments
- Doctor Experience
- Average Patient Age by Doctor
- Treatment Count per Doctor

---

##  Appointment Analysis

- Total Appointments
- Appointment Status Summary
- Completed Appointments
- Cancelled Appointments
- Pending Appointments
- No-show Appointments
- Daily Appointments
- Weekly Appointments
- Monthly Appointments
- Yearly Appointments
- Peak Appointment Day
- Peak Appointment Month
- Peak Appointment Hour
- Appointment Growth %
- Appointments by Branch
- Appointments by Specialization
- Weekend vs Weekday Appointments
- Appointment Completion Rate

---

#  Automation Workflow

```
PostgreSQL Database
        │
        ▼
Python Automation
(report.py)
        │
        ▼
Read SQL Files
        │
        ▼
Execute SQL Queries
        │
        ▼
Export CSV Reports
        │
        ▼
Generate Logs
        │
        ▼
Power BI Dashboard
        │
        ▼
Windows Task Scheduler
```

---

#  How to Run

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/HealthcareReportAutomation.git
```

---

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3. Configure Database

Update `config.py` with your PostgreSQL credentials.

```python
DB_CONFIG = {
    "host": "localhost",
    "port": 5432,
    "database": "HealthcareDB",
    "user": "postgres",
    "password": "your_password"
}
```

---

## 4. Run the Automation

```bash
python report.py
```

or

```bash
run_report.bat
```

---

#  Power BI Dashboard

The generated CSV reports are directly connected to Power BI.

After running the automation:

1. Open the Power BI report.
2. Click **Refresh**.
3. The dashboard updates with the latest data.

---

#  Output

CSV reports are automatically created inside:

```
output/
```

Example:

```
output/

patient_analysis/
doctor_analysis/
appointment_analysis/
```

Each SQL query generates a separate CSV file for reporting and visualization.

---

#  Logging

Execution logs are stored in:

```
logs/automation.log
```

Logs include:

- Execution time
- Successful reports
- Failed reports
- Error messages

---

#  Key Features

- Automated SQL report execution
- Dynamic CSV generation
- Professional folder structure
- Error handling and logging
- PostgreSQL integration
- Power BI integration
- Windows Task Scheduler support
- Reusable automation framework

---

#  Skills Demonstrated

- SQL Query Development
- PostgreSQL Database Management
- Python Automation
- Data Extraction and Reporting
- CSV Report Generation
- Power BI Dashboard Development
- Report Scheduling
- Business Intelligence Reporting

---

# Author

Uroosa khan

**Data Analyst | SQL | Python | Power BI | Reporting Automation**

---
