# Project Summary

## Project Title
Body Measurement Dataset Exploratory Data Analysis

---

# Overview

This project involved an AI-assisted exploratory data analysis (EDA) of a body measurement dataset containing 2,018 records and 14 numeric biometric measurement variables.

The analysis was completed using AWS PartyRock as part of the AWS AI & ML Scholars Program by Amazon Web Services and Udacity.

The project focused on reviewing AI-generated insights, validating findings against the dataset, and summarizing analytical observations in a structured report format.

No predictive modeling or advanced statistical modeling was performed.

---

# Objectives

The analysis aimed to answer the following questions:

- What patterns exist across body measurements?
- Which variables show the highest variation?
- Which measurements correlate most strongly?
- Which variables contain the most outliers?
- How do body measurements change across height groups?
- What does the waist-to-height ratio distribution look like?

---

# Dataset Information

| Metric | Value |
|---|---|
| Records | 2,018 |
| Variables | 15 |
| Numeric Variables | 14 |
| Missing Values | 0 |
| Duplicate Rows | 0 |

All measurements were recorded in centimeters.

---

# Analysis Performed

The project included:
- Data quality checks
- Descriptive statistics review
- Correlation analysis
- Outlier analysis using the IQR method
- Waist circumference distribution analysis
- Height-based segmentation
- Waist-to-height ratio analysis

The analysis remained descriptive and based only on the uploaded dataset.

---

# Key Findings

## Data Quality
- The dataset contained 0 missing values.
- The dataset contained 0 duplicate rows.
- All records represented unique subject identifiers.

---

## Variability
- Waist circumference showed the highest variability among girth measurements.
- Height showed a near-normal distribution with minimal outliers.

---

## Correlation Analysis

Strongest observed relationships:
- Arm Length vs Leg Length → r = 0.929
- Chest vs Waist → r = 0.927
- Height vs Leg Length → r = 0.910

Weakest observed relationships:
- Leg Length vs Thigh → r = 0.160
- Arm Length vs Thigh → r = 0.164

---

## Outlier Analysis
- Hip circumference produced the highest outlier count.
- Thigh and waist circumference also showed elevated outlier frequencies.
- Outliers were retained because the dataset did not provide evidence to classify them as errors.

---

## Waist Distribution
- 60.3% of subjects had waist measurements between 75 cm and 95 cm.
- The waist distribution showed right skew due to higher upper-range values.

---

## Waist-to-Height Ratio
- Mean waist-to-height ratio: 0.522
- 56.6% of subjects had a ratio above 0.5

The analysis described distribution patterns only and did not make medical conclusions.

---

# Skills Demonstrated

This project helped strengthen skills in:
- Exploratory data analysis
- Data interpretation
- Analytical reporting
- Identifying correlations and outliers
- Reviewing AI-generated insights critically
- Structuring findings clearly

---

# Limitations

The dataset did not include:
- Age
- Sex
- Weight
- Geographic information
- Collection methodology

Because of these limitations:
- No subgroup analysis was possible
- No BMI calculations were possible
- No population-level conclusions were made

---

# Reflection

This project demonstrated how AI-assisted tools can support exploratory analysis while still requiring human review and validation.

The experience reinforced the importance of:
- Verifying AI-generated outputs
- Understanding dataset limitations
- Communicating findings accurately
- Avoiding unsupported assumptions

---

# Conclusion

This project provided practical experience working with structured data, reviewing analytical outputs, and communicating findings in a professional reporting format.

The analysis remained descriptive and limited to the information available in the dataset.
