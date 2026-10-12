# HR-Attrition-Retention-Dashboard
Power BI HR analytics dashboard for exploring employee attrition by department, job satisfaction, salary band, and primary reason, supporting data-driven workforce planning and retention decisions.

## Dashboard Highlights

### Key Performance Indicators
- **Total Employees** — overall workforce represented in the report.
- **Attrition Count** — number of employees recorded as attrited.
- **Attrition Percentage** — attrition as a proportion of the workforce, as defined in the Power BI model.

### Visual Analysis
- **Attrition by Job Satisfaction** — compares attrition counts across job satisfaction levels.
- **Attrition by Department** — highlights how employee attrition is distributed across departments.
- **Attrition by Salary Band** — compares attrition counts across salary ranges.
- **Attrition by Primary Reason** — summarises the recorded reasons associated with employee attrition.

## Business Objectives
- Provide a concise overview of workforce attrition.
- Identify departments and salary bands with higher attrition counts.
- Explore how attrition varies by job satisfaction.
- Understand the primary reasons recorded for employee departures.
- Support HR discussions on workforce planning and employee retention.

## Data Model
The report uses a model structured around the following tables:

- `Fact_Attrition` — employee and attrition metrics used by the report.
- `Dim_Emp` — employee-related attributes, including primary reason.
- `Dim_Department` — department descriptions used for departmental analysis.

## Technology Stack
- **Microsoft Power BI** — dashboard design and data visualisation.
- **DAX** — KPI calculations and attrition measures.
- **Data modelling** — fact and dimension tables for HR analysis.

## Repository Contents
- `HR Attrition BI.pbix` — Power BI report and data model.
- `README.md` — project overview and dashboard documentation.

---

**Project:** HR Attrition & Retention Analytics  
**Repository:** `hr-attrition-retention-dashboard`
