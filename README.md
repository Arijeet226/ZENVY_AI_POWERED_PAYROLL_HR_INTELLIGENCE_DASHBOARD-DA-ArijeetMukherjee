# ZENVY_AI_POWERED_PAYROLL_HR_INTELLIGENCE_DASHBOARD-DA-ArijeetMukherjee
This is a sample project on AI Powered Payroll HR Intelligence Dashboard project for ZENVY build with POWERBI and Python

Situation
ZENVY is an enterprise-level AI-powered payroll and HR intelligence initiative tasked with
designing a comprehensive HR Intelligence Dashboard for an organization. The project operates
under requirements to: (1) define 15+ payroll KPIs aligned with financial and operational
metrics, (2) detect three critical fraud categories—salary leakage, ghost employees and
overtime abuse, (3) handle data quality issues including missing attendance records and
duplicate salary credits, and (4) deliver executive-level insights beyond static visualizations. The
underlying dataset (HR Analytics, 1,480 employees, 38 features) provided the raw material for
this enterprise-grade analytics solution.

Task
Clean and preprocess the HR dataset, handling missing values, duplicate records, and redundant
features to create a production-ready single source of truth.
Identify and quantify three fraud vectors
Ghost Employees: Detect duplicate EmpIDs representing non-existent workers on payroll
Salary Leakage: Calculate financial exposure from fraudulent payroll entries
Overtime Abuse: Flag employees doing unauthorized overtime despite low job involvement
Define 15+ payroll and HR KPIs spanning attrition, compensation, tenure, training, and fraud risk
dimensions. Conduct EDA to uncover attrition drivers across department, salary slab, overtime,
job role, salary hike %, gender, and commute distance.
Design a multi-page Power BI/Tableau dashboard with executive-level visualizations. Generate a
1-page executive summary with strategic recommendations based on discovered patterns.

Action
Cleaned and validated the HR dataset (removed nulls, dropped duplicate EmpIDs, removed noninformative columns) to create a reliable analytical base.
Detected ghost employees via duplicate EmpIDs, computed per-employee and total salary
leakage using Monthly Rate and Years at Company, and saved a detailed leakage table.
Flagged overtime abuse by tagging employees with low Job Involvement but doing Overtime,
and quantified this risk group for HR review.
Performed EDA on attrition, compensation, tenure, overtime, and demographics to uncover risk
patterns, then defined 15+ payroll/HR KPIs and designed a multi-page HR Intelligence
Dashboard with executive-ready insights.

Result
Produced a clean, de-duplicated HR dataset with zero missing values, ready for production
analytics and dashboarding.
Quantified around 9.49M in historical salary leakage from 10 ghost employees, giving finance a
clear fraud exposure figure and a list of cases to audit.
Identified 100+ suspected overtime abusers and linked overtime, low pay slabs, and certain
roles to higher attrition risk, enabling targeted interventions.
Delivered a structured KPI set, an HR Intelligence Dashboard, and an insight report that together
support data-driven decisions on fraud control, retention, and compensation strategy

**Screenshot of dashboard:**  
![Preview of Homepage](https://github.com/Arijeet226/ZENVY_AI_POWERED_PAYROLL_HR_INTELLIGENCE_DASHBOARD-DA-ArijeetMukherjee/blob/29ccad85ce92cbae2c862562bb1f73b8e76dd635/assets/Screenshot%202026-01-03%20113357.png)
**Screenshot of dashboard:**  
![Preview of Homepage](https://github.com/Arijeet226/ZENVY_AI_POWERED_PAYROLL_HR_INTELLIGENCE_DASHBOARD-DA-ArijeetMukherjee/blob/29ccad85ce92cbae2c862562bb1f73b8e76dd635/assets/Screenshot%202026-01-03%20113409.png)
**Screenshot of dashboard:**  
![Preview of Homepage](https://github.com/Arijeet226/ZENVY_AI_POWERED_PAYROLL_HR_INTELLIGENCE_DASHBOARD-DA-ArijeetMukherjee/blob/29ccad85ce92cbae2c862562bb1f73b8e76dd635/assets/Screenshot%202026-01-03%20113419.png)
**Screenshot of dashboard:**  
![Preview of Homepage](https://github.com/Arijeet226/ZENVY_AI_POWERED_PAYROLL_HR_INTELLIGENCE_DASHBOARD-DA-ArijeetMukherjee/blob/29ccad85ce92cbae2c862562bb1f73b8e76dd635/assets/Screenshot%202026-01-03%20113433.png)
