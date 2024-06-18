# Analyzing U.S. COVID-19 Data

## Overview
This repository contains a comprehensive analysis of COVID-19 data in the United States, leveraging publicly available datasets from the CDC and the US Census Bureau. The project aims to uncover patterns of COVID-19 spread, the impact on different demographics, and the effectiveness of management strategies across various regions and time periods.

## Datasets
1. **COVID-19 Case Surveillance Data**: Provided by the CDC.
2. **Household Pulse Survey Data**: Provided by the US Census Bureau.

---

## Part 1: Exploratory Analysis
1. **Hospitalizations vs. Deaths**: Analysis of the total number of COVID-19-related hospitalizations and deaths in the US, segmented by month and year.
2. **Demographic Death Rates**: Examining the average rates of COVID-related deaths relative to patient demographics.
3. **Age Group Analysis**: Examining hospitalization and death rates across different age groups.
4. **State-wise Analysis**: Average rate of COVID-related hospitalization and death per state over the entire study period.
5. **ICU Admittance**: Exploring the relationship between age, pre-existing medical conditions and/or risk behaviors, and rate of admittance to the ICU.
6. **Employment Impact**: Investigating the rate of expected employment loss due to COVID-19 and sector of employment.
7. **Demographic Employment Impact**: Examining the rate of expected employment loss due to COVID-19 relative to responders' demographics.
8. **Top States Employment Impact**: Investigating the rate of expected employment loss due to COVID-19 for the top 10 states with the highest hospitalization rates.
9. **Income and Medical Treatment**: Exploring the relationship between household income and the rate of delayed or unobtained medical treatment due to COVID-19.
10. **Symptom Manifestation**: Analyzing the relationship between COVID-19 symptom manifestation and age group.

## Part 2: Statistical Insights and Relationships
1. **Underlying Conditions and Mortality**: Analyzing if hospitalized patients with underlying medical conditions or risk behaviors are more likely to die from COVID-19.
2. **Demographic Risk Assessment**: Identifying the demographic segments most and least at risk of death due to COVID-19.
3. **Exposure and Hospitalization**: Determining the percentage of patients who reported travel or congregation exposure within 14 days prior to illness onset and their subsequent hospitalization rates.
4. **Asymptomatic Patients**: Investigating the likelihood of hospitalization and death for asymptomatic COVID-19 patients.
5. **Economic Impact Payments**: Identifying the state associated with the highest percentage of Economic Impact (stimulus) payments among survey respondents.
6. **Industry Employment Loss**: Analyzing how the rate of COVID-related employment loss varies across different industries.
7. **Symptom Severity and Medical Treatment**: Exploring the correlation between COVID-19 symptom severity and delayed medical treatment.
8. **Household Size and Food Spending**: Investigating the correlation between household size and food spending during the pandemic.
9. **Household Composition and Education Spending**: Exploring the correlation between household composition and education spending during the pandemic.
10. **ICU Admission and Mortality**: Analyzing the correlation between admission to the ICU and the death rate among COVID-19 patients.

## Part 3: Hypothesis Testing
- **Claim 1**: “There is a strong association between the probability of death due to COVID-19 and patient demographics.”
- **Claim 2**: “There is a significant association between the combined demographic features and the probability of ICU admission due to COVID-19.”

## Part 4: Regression Analysis
Developed a regression model to predict the proportion of COVID-19 deaths out of all cases in a given month based on:
- Gender distribution of cases.
- Age distribution of cases.
- Proportion of cases that result in ICU admission.
- Proportion of cases that result in hospitalization.

## Part 5: Machine Learning Classification
Implemented a machine learning classifier to predict the likelihood of death due to COVID-19 using relevant attributes from the COVID case surveillance dataset.

## Part 6: Documentation
- **Business Report**: A detailed report presenting the key findings and their implications.
- **Technical Documentation**: Markdown documentation embedded within the notebook to explain methodologies, code, and results.

## Part 7: Presentation
Prepared a final presentation with slides summarizing all findings, supported by visualizations and brief explanatory comments.

---

Explore the project to gain insights into the spread and management of COVID-19 in the US. The repository includes all code, data, and documentation necessary to replicate the analysis and extend it further.

[Link to GitHub Repository](https://github.com/Adham-Saad163/Analyzing-U.S.-COVID-19-Data)
