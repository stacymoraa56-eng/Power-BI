# Hospital & Pharmacy Data Analysis — Dashboard Gallery

This gallery presents the Power BI visualizations developed to investigate patient visits, disease patterns, pharmacy revenue, departmental costs, medication consumption, and hospital length of stay.

Each section highlights the purpose of the visualization, the key observation from the analysis, and its potential relevance to hospital management.

## 1. Disease Analysis Across Counties

<img width="408" height="213" alt="Disease_Across_Countries" src="https://github.com/user-attachments/assets/71481eee-e305-4f93-bba9-f6836b6f7f7e" />

### Objective

Identify the most frequently recorded diagnoses across counties and examine patterns in disease occurrence within the available dataset.

### Key Insight

The analysis identified flu, typhoid, and diabetes among the most frequently recorded diagnoses.

### Business Implication

Understanding the distribution of recorded diagnoses can help hospital management investigate differences in healthcare demand across counties and identify areas requiring further assessment.

These results describe the available records and should not be interpreted as estimates of disease prevalence in the wider population.

---

## 2. Patient Visits vs. Pharmacy Revenue

<img width="286" height="256" alt="Pharmacy_Revenue_Analysis" src="https://github.com/user-attachments/assets/631ba4b2-17c2-40fb-ac78-3456b3a7216b" />


### Objective

Investigate whether counties with higher patient visits also record higher pharmacy revenue.

### Key Insight

Uasin Gishu recorded the highest patient visits and pharmacy revenue during the analyzed period. The county with the fewest patient visits also recorded the lowest pharmacy revenue.

This pattern suggests a positive association between patient visits and pharmacy revenue within the observed data.

However, the comparison does not establish that higher patient visits always lead to higher revenue. Medication prices, prescription patterns, patient demographics, and the types of conditions treated may also influence revenue.

### Business Implication

Management can monitor pharmacy revenue alongside patient visits to understand how pharmacy performance varies with patient demand.

Further analysis of revenue per visit and medication utilization could help explain differences between counties.

---

## 3. Pharmacy Costs by Department

<img width="351" height="226" alt="Pharmacy_Revenue_per_Department" src="https://github.com/user-attachments/assets/fc8a4f5b-1381-4b70-a797-ad50b5772646" />


### Objective

Compare pharmacy costs across the inpatient, emergency, and outpatient departments to identify the largest contributors to expenditure.

### Key Insight

The reported pharmacy costs were:

* **Inpatient:** 95K
* **Emergency:** 94K
* **Outpatient:** 87K

Inpatient recorded the highest pharmacy cost, followed closely by Emergency. Outpatient recorded the lowest cost among the three departments.

### Business Implication

Hospital management can investigate the factors driving pharmacy expenditure in each department.

Comparing costs alongside patient volumes, medication utilization, and treatment requirements could provide a clearer understanding of departmental spending patterns.

**Note:** These figures are described as costs, not revenue. Confirm the underlying measure and currency before presenting the figures as financial totals.

---

## 4. Medication Consumption by Age Group

<img width="392" height="260" alt="Meedication_Consumption_per_age_group" src="https://github.com/user-attachments/assets/b1f1a7ea-085d-4830-b13f-5923ad7920c7" />


### Objective

Examine how medication consumption differs across patient age groups.

The intended age categories are:

* Child: 0–12 years
* Teen: 13–19 years
* Youth: 20–34 years
* Adult: 35–65 years
* Elderly: 66 years and above

### Key Insight

The analysis indicated that elderly patients accounted for the highest total medication consumption, with consumption generally decreasing among younger groups.

### Business Implication

Understanding medication demand across age groups can help management investigate patient needs and medication utilization patterns.

However, higher total consumption in an age group does not necessarily mean that each patient in that group consumes more medication. The number of patients in each group and the definition of medication consumption should also be considered.

---

## 5. Diagnosis, Pharmacy Spending, and Length of Stay
<img width="315" height="265" alt="Pharmacy_Spending_by_Diagnosi_and_Stay" src="https://github.com/user-attachments/assets/9a8a08ce-15fc-4018-a728-4bea1f56734d" />


### Objective

Investigate whether diagnoses associated with longer hospital stays also have lower pharmacy spending.

### Key Insight

The analysis revealed different patterns across diagnoses:

* **Typhoid:** Associated with the highest pharmacy spending and a high average hospital length of stay.
* **Malaria:** Associated with comparatively lower spending and shorter hospital stays.
* **Flu:** Associated with a longer hospital stay and average spending.

The results suggest that the relationship between pharmacy spending and hospital length of stay varies across diagnoses rather than following one consistent pattern.

### Business Implication

Management can investigate the factors associated with differences in pharmacy spending and hospital stays across diagnoses.

Additional analysis incorporating patient characteristics, medication requirements, and other relevant factors could help explain the observed differences.

These findings indicate associations within the available data and do not establish that a diagnosis directly causes higher spending or longer hospital stays.

---

## Summary

The dashboard gallery demonstrates how Power BI can be used to explore healthcare data from several operational perspectives.

The visualizations address five key questions involving disease patterns, patient visits, pharmacy revenue, departmental expenditure, medication consumption, and hospital length of stay.

Together, they provide a foundation for further analysis and support evidence-based discussions about hospital operations.

## Related Project Documentation

* [Project Overview — README](README.md)
* [Written Insights and Recommendations](Insights.md)
