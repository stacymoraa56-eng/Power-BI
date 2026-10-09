<img width="2068" height="1166" alt="Hospital  Pharmacy Data Analysis Dashboard " src="https://github.com/user-attachments/assets/3e7c4603-b555-4cc2-b5ee-fca8e06c6ef3" />

# Hospital Pharmacy Data Analysis
![Hospital Pharmacy Data Analysis]()
# Hospital & Pharmacy Data Analysis | Power BI

## Project Overview

Healthcare institutions generate large volumes of data across patient services, diagnoses, hospital admissions, and pharmacy operations. Analyzing this information can help management understand disease patterns, monitor service utilization, and identify opportunities to improve operational efficiency.

This project uses Microsoft Power BI to clean, model, analyze, and visualize hospital and pharmacy data for a county referral hospital in Kenya.

The objective is to transform raw, inconsistent departmental data into an interactive dashboard that supports data-driven decision-making across patient services and pharmacy operations.

## Business Problem

Hospital management needs a clearer understanding of patient visits, common diagnoses, pharmacy revenue, medication consumption, and the relationship between hospital stays and pharmacy expenditure.

The analysis addresses five key business questions:

1. Which diseases are most common across counties?
2. Does a higher number of patient visits always lead to higher pharmacy revenue?
3. Which hospital departments account for the highest pharmacy costs?
4. Which patient age groups consume the most medication?
5. Are some diagnoses associated with longer hospital stays but lower pharmacy spending?

## Tools & Technologies

* **Microsoft Power BI:** Data visualization, dashboard development, and reporting.
* **Power Query:** Data cleaning and transformation.
* **DAX:** Calculated measures and analytical KPIs, where applicable.
* **Data Modeling:** Organizing data and relationships to support reliable analysis.

## Dashboard Preview

![Hospital and Pharmacy Executive Dashboard](screenshots/executive_dashboard.png)

*The executive dashboard provides an overview of hospital visits, pharmacy revenue, average length of stay, disease patterns, and operational performance.*

## Analytical Approach

### 1. Data Cleaning and Preparation

Prepared the source data for analysis by addressing data quality issues and standardizing relevant fields. The objective was to establish a consistent dataset for comparisons across counties, departments, diagnoses, and patient age groups.

### 2. Data Modeling

Organized the data and established the relationships and analytical measures needed to support dashboard reporting.

### 3. Exploratory Data Analysis

Investigated patient visits, disease frequency, pharmacy revenue, departmental costs, medication consumption, and hospital length of stay.

### 4. Dashboard Development

Designed interactive Power BI visualizations to communicate key performance indicators and enable users to explore the results using county, diagnosis, and date filters.

## Key Findings

### 1. Common Diseases Across Counties

The analysis identified flu, typhoid, and diabetes among the most frequently observed diagnoses in the dataset.

These findings can help hospital management understand the distribution of recorded diagnoses and investigate differences in healthcare demand across counties.

### 2. Patient Visits and Pharmacy Revenue

Uasin Gishu recorded the highest patient visits and pharmacy revenue during the analyzed period. The county with the fewest patient visits also recorded the lowest pharmacy revenue.

This pattern suggests a positive relationship between patient visits and pharmacy revenue within the observed data. However, further analysis would be required to determine whether this relationship holds consistently across counties and time periods.

### 3. Pharmacy Costs by Department

The reported pharmacy cost totals were:

* **Inpatient:** 95K
* **Emergency:** 94K
* **Outpatient:** 87K

Inpatient recorded the highest pharmacy cost, followed closely by Emergency. Outpatient had the lowest cost among the three departments.

These results can help management identify the departments that contribute most to pharmacy expenditure and investigate the factors driving their costs.

### 4. Medication Consumption by Age Group

The age-group analysis indicated that elderly patients accounted for the highest medication consumption, with consumption generally decreasing among younger groups.

This pattern highlights the importance of understanding medication demand across patient demographics. The findings should be interpreted in the context of the available patient population, medication quantities, and the consumption metric used.

### 5. Diagnosis, Hospital Stay, and Pharmacy Spending

The analysis revealed different patterns in average hospital length of stay and pharmacy spending across diagnoses.

Typhoid was associated with the highest average spending and a high average length of stay. Malaria had comparatively lower hospital stays and average spending, while flu was associated with a longer average stay and average spending.

These findings suggest that the relationship between diagnosis, length of stay, and pharmacy expenditure varies by diagnosis rather than following one consistent pattern.

## Dashboard Features

The Power BI report includes:

* KPI cards for total patient visits, total pharmacy revenue, and average length of stay.
* Disease analysis across counties and over time.
* Pharmacy cost breakdowns by drug category.
* County and department comparisons.
* Medication consumption analysis by patient age group.
* Diagnosis comparisons involving hospital length of stay and pharmacy spending.
* Interactive slicers for county, diagnosis, and date.

## Business Value

The analysis provides hospital management with a consolidated view of patient activity, disease patterns, and pharmacy operations.

Potential applications include:

* Identifying counties with high patient demand.
* Monitoring pharmacy revenue alongside patient visits.
* Understanding departmental contributions to pharmacy expenditure.
* Investigating medication demand across patient age groups.
* Identifying diagnoses that warrant further investigation into hospital stays and pharmacy spending.

The findings provide a starting point for operational review and further analysis. They do not, on their own, establish the causes of differences in healthcare costs or patient outcomes.

## Project Deliverables

* Interactive Power BI report (`.pbix`).
* One-page executive dashboard.
* Supporting dashboard screenshots.
* Written executive insights.

## Limitations

The findings reflect the data and period included in this analysis. Differences in patient volumes, disease frequency, medication quantities, and expenditure may be influenced by factors not captured in the available dataset.

Further validation and statistical analysis would be needed before using these observations to make clinical or resource-allocation decisions.

## Conclusion

This project demonstrates the application of Power BI to healthcare data analysis, covering data preparation, modeling, KPI reporting, comparative analysis, and interactive dashboard development.

It illustrates how structured data analysis can help healthcare organizations investigate patient demand, disease patterns, and pharmacy expenditure to support more informed operational decisions.

