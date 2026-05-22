
# Body Measurement Analysis

## Project Overview

This project presents an AI-assisted exploratory data analysis (EDA) of a body measurement dataset containing 2,018 records and 14 biometric measurement variables.

The analysis was completed using AWS PartyRock as part of the AWS AI & ML Scholars Program by Amazon Web Services and Udacity.

The project focused on:
- Reviewing AI-generated insights
- Validating analytical findings
- Identifying patterns and correlations
- Summarizing observations using structured reporting

The analysis remained descriptive and based only on the uploaded dataset.

---

# Dataset Information

| Metric | Value |
|---|---|
| Records | 2,018 |
| Variables | 15 |
| Numeric Variables | 14 |
| Missing Values | 0 |
| Duplicate Rows | 0 |

All measurements were recorded in centimeters (cm).

---

# Analysis Areas

The project included:
- Data quality checks
- Descriptive statistics review
- Correlation analysis
- Outlier analysis using the IQR method
- Waist circumference distribution analysis
- Height-based segmentation
- Waist-to-height ratio analysis

---

# Key Findings

## Data Quality
- The dataset contained 0 missing values.
- The dataset contained 0 duplicate rows.
- All records represented unique subject identifiers.

---

## Correlation Analysis

Strongest relationships identified:
- Arm Length vs Leg Length → r = 0.929
- Chest vs Waist → r = 0.927
- Height vs Leg Length → r = 0.910

Weakest relationships identified:
- Leg Length vs Thigh → r = 0.160
- Arm Length vs Thigh → r = 0.164

---

## Outlier Analysis
- Hip circumference produced the highest outlier count.
- Waist and thigh measurements also showed elevated outlier frequencies.
- Outliers were retained because the dataset did not provide evidence to classify them as errors.

---

## Waist Distribution
- 60.3% of subjects had waist measurements between 75 cm and 95 cm.
- The waist distribution showed right skew due to higher upper-range values.

---

## Waist-to-Height Ratio
- Mean waist-to-height ratio: 0.522
- 56.6% of subjects had a ratio above 0.5

This analysis described dataset patterns only and did not make medical conclusions.

---

# Tools Used

- AWS PartyRock
- AI-assisted data analysis
- Exploratory data analysis (EDA)
- Analytical reporting

---

# Repository Structure

```bash
body-measurement-analysis/
│
├── data/
│   └── body-measurement-data-set.csv
│
├── prompts/
│   └── analysis-prompts.md
│
├── reports/
│   └── project-summary.md
│
├── screenshots/
│   └── partyrock-analysis.png
│
└── README.md
```

---

# Skills Demonstrated

This project helped strengthen skills in:
- Exploratory data analysis
- Data interpretation
- Analytical reporting
- Reviewing AI-generated insights critically
- Identifying patterns and relationships in structured data
- Communicating findings clearly

---

# Project Limitations

The dataset did not include:
- Age
- Sex
- Weight
- Geographic information
- Collection methodology

Because of these limitations:
- No subgroup analysis was performed
- No BMI calculations were possible
- No population-level conclusions were made

---

# Reflection

This project demonstrated how AI-assisted tools can support exploratory analysis while still requiring human review and validation.

The experience reinforced the importance of:
- Verifying AI-generated outputs
- Understanding dataset limitations
- Avoiding unsupported assumptions
- Communicating findings accurately

---

# Screenshot

Example analysis interface from AWS PartyRock:

![PartyRock Analysis](screenshots/partyrock-analysis.png)

---
