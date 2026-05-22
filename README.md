# Body Measurement Exploratory Data Analysis

## Project Overview

This project presents an exploratory data analysis (EDA) of a body measurement dataset containing 2,018 records and 14 biometric measurement variables.

The analysis focused on:
- Data quality assessment
- Descriptive statistics
- Outlier detection
- Correlation analysis
- Distribution analysis
- Height-based segmentation
- Waist-to-height ratio analysis

This project was completed as part of the AWS AI & ML Scholars Program by Amazon Web Services and Udacity using AWS PartyRock and Python-based exploratory data analysis techniques.

---

# Dataset Information

| Metric | Value |
|---|---|
| Records | 2,018 |
| Variables | 15 |
| Numeric Variables | 14 |
| Missing Values | 0 |
| Duplicate Rows | 0 |

All measurements are recorded in centimeters (cm).

## Variables Included

- Height
- Waist Circumference
- Chest Circumference
- Hip Circumference
- Thigh Circumference
- Arm Length
- Leg Length
- Wrist Circumference
- Forearm Circumference
- Bicep Circumference
- Shoulder Breadth
- Shoulder to Crotch
- Calf Circumference
- Ankle Circumference

---

# Project Objectives

The goal of this project was to answer the following analytical questions:

- What is the distribution of each body measurement?
- Which measurements contain the most outliers?
- Which variables are most strongly correlated?
- How do body measurements change across height groups?
- What patterns exist in waist measurements?
- What does the waist-to-height ratio distribution show?

---

# Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- AWS PartyRock
- Exploratory Data Analysis (EDA)

---

# Data Quality Checks

The dataset was validated before analysis.

| Check | Result |
|---|---|
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Unique Subject IDs | 2,018 |

No rows or columns were removed during cleaning.

---

# Key Findings

## Descriptive Statistics

- Average height: 172.15 cm
- Average waist circumference: 89.81 cm
- Waist circumference showed the highest variability among girth measurements
- Height distribution was approximately normal with only 1 detected outlier

---

## Correlation Analysis

### Strongest Correlations

| Variable Pair | Pearson Correlation |
|---|---|
| Arm Length vs Leg Length | 0.929 |
| Chest vs Waist | 0.927 |
| Height vs Leg Length | 0.910 |

### Weakest Correlations

| Variable Pair | Pearson Correlation |
|---|---|
| Leg Length vs Thigh | 0.160 |
| Arm Length vs Thigh | 0.164 |

---

## Outlier Analysis

Outliers were detected using the IQR method.

| Variable | Outlier Count |
|---|---|
| Hip Circumference | 63 |
| Thigh Circumference | 54 |
| Waist Circumference | 35 |

Hip circumference produced the most extreme upper values in the dataset.

---

## Waist Distribution

- 60.3% of subjects had waist measurements between 75 cm and 95 cm
- 11.2% of subjects had waist measurements above 105 cm

---

## Waist-to-Height Ratio

| Metric | Value |
|---|---|
| Mean WHR | 0.522 |
| Subjects Above 0.5 WHR | 56.6% |
| Subjects Below 0.5 WHR | 43.4% |

---

# Visualizations

The project includes:
- Correlation matrix heatmap
- Waist distribution chart
- Outlier analysis chart
- Height quintile comparison chart

---

# Project Limitations

- No demographic variables included
- No weight variable available
- No information about collection methodology
- No time-series component for trend analysis

---

# Skills Demonstrated

- Data cleaning
- Exploratory data analysis
- Statistical analysis
- Correlation analysis
- Outlier detection
- Data visualization
- Analytical reporting
- AI-assisted analytics validation

---

# Future Improvements

Potential next steps:
- Build predictive regression models
- Create Power BI dashboards
- Perform clustering analysis
- Add demographic segmentation
- Compare linear vs non-linear relationships

---

# Repository Structure

```bash
body-measurement-analysis/
│
├── data/
│   └── body-measurement-data-set.csv
│
├── notebooks/
│   └── exploratory-data-analysis.ipynb
│
├── reports/
│   └── EDA_Report.pdf
│
├── visuals/
│   ├── correlation-matrix.png
│   ├── waist-distribution.png
│   ├── outlier-analysis.png
│   └── height-quintiles.png
│
└── README.md
```

---
