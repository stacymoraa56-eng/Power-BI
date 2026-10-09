# Hospital & Pharmacy Data Analysis | Power BI

## Project Overview

Healthcare institutions generate large volumes of data across patient visits, diagnoses, hospital departments, and pharmacy operations. Analyzing this information can help management understand disease patterns, monitor service utilization, and identify opportunities to improve operational efficiency.

This project uses **Microsoft Power BI** to clean, model, analyze, and visualize hospital and pharmacy data for a county referral hospital in Kenya.

The goal is to transform raw departmental data into an interactive dashboard that supports data-driven decision-making across patient services and pharmacy operations.

## Business Problem

Hospital management needs a clearer understanding of patient visits, common diseases, pharmacy revenue, medication consumption, and the relationship between hospital stays and pharmacy expenditure.

The analysis addresses five key business questions:

1. Which diseases are most common across counties?
2. Does a higher number of patient visits always lead to higher pharmacy revenue?
3. Which departments account for the highest pharmacy costs?
4. Are there age groups that consume more medication than others?
5. Are some diagnoses associated with longer hospital stays but lower pharmacy spending?

## Tools & Technologies

* **Microsoft Power BI:** Dashboard development, data visualization, and reporting.
* **Power Query:** Data cleaning and transformation.
* **DAX:** Analytical measures and calculated KPIs, where applicable.
* **Data Modeling:** Structuring data and relationships to support analysis.

## Executive Dashboard

<img width="2068" height="1166" alt="Hospital  Pharmacy Data Analysis Dashboard " src="https://github.com/user-attachments/assets/3e7c4603-b555-4cc2-b5ee-fca8e06c6ef3" />

*The executive dashboard provides an overview of patient visits, pharmacy revenue, average length of stay, disease patterns, and operational performance.*

## Key Findings

### 1. Disease Patterns Across Counties

The analysis identified flu, typhoid, and diabetes among the most frequently recorded diagnoses in the dataset.

### 2. Patient Visits and Pharmacy Revenue

Uasin Gishu recorded the highest patient visits and pharmacy revenue during the analyzed period. The county with the fewest visits also recorded the lowest pharmacy revenue.

This suggests a positive association between patient visits and pharmacy revenue within the observed data, although further analysis is required to determine the strength and consistency of the relationship.

### 3. Pharmacy Costs by Department

The reported pharmacy costs were:

* Inpatient: 95K
* Emergency: 94K
* Outpatient: 87K

Inpatient recorded the highest pharmacy cost, followed closely by Emergency.

### 4. Medication Consumption by Age Group

The analysis indicated that elderly patients accounted for the highest total medication consumption, with consumption generally decreasing among younger groups.

This finding should be interpreted alongside the number of patients in each age group and the medication consumption metric used.

### 5. Diagnosis, Pharmacy Spending, and Length of Stay

The analysis revealed different patterns in pharmacy spending and average hospital length of stay across diagnoses.

Typhoid was associated with the highest pharmacy spending and a high average length of stay. Malaria showed comparatively lower spending and shorter stays, while flu was associated with a longer hospital stay and average spending.

These observations suggest that the relationship between diagnosis, spending, and hospital length of stay varies by diagnosis.

## Dashboard Features

The Power BI report includes:

* KPI cards for total patient visits, total pharmacy revenue, and average length of stay.
* Disease analysis across counties and over time.
* Pharmacy cost breakdowns by drug category.
* County and department comparisons.
* Medication consumption analysis by patient age group.
* Diagnosis comparisons involving pharmacy spending and hospital length of stay.
* Interactive slicers for county, diagnosis, and date.

## Project Documentation

Explore the supporting project materials:

* [Dashboard Gallery](Dashboard_Gallery.md) — Dashboard screenshots, visual explanations, and detailed findings.
* [Written Insights and Recommendations](Insights.md) — The written analysis prepared for the assignment.

## Business Value

The analysis provides hospital management with a consolidated view of patient activity, disease patterns, and pharmacy operations.

Potential applications include:

* Monitoring patient demand across counties.
* Comparing patient visits with pharmacy revenue.
* Identifying departments that contribute most to pharmacy expenditure.
* Understanding medication demand across patient age groups.
* Investigating differences in hospital stays and pharmacy spending across diagnoses.

These findings provide a starting point for operational review and further investigation. They do not independently establish the causes of differences in healthcare costs or patient outcomes.

## Limitations

The findings reflect the data and period included in the analysis. Differences in patient volumes, disease frequency, medication quantities, and expenditure may be influenced by factors not captured in the available dataset.

Further validation and statistical analysis would be necessary before using these observations to make clinical or resource-allocation decisions.

## Conclusion

This project demonstrates the application of Power BI to healthcare data analysis, including data preparation, modeling, KPI reporting, comparative analysis, and interactive dashboard development.

It illustrates how data analytics can help healthcare organizations investigate patient demand, disease patterns, and pharmacy expenditure to support more informed operational decisions.
