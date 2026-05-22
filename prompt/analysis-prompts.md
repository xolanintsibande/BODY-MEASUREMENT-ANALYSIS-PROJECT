# Analysis Prompts

This file contains the prompts used during the AI-assisted exploratory data analysis process using AWS PartyRock.

The goal of these prompts was to generate descriptive insights, validate patterns in the dataset, and structure findings into a professional analytical report.

---

# Prompt 1: Dataset Overview and Data Quality

```text
Analyze the uploaded body measurement dataset.

Provide:
- Total rows and columns
- List of variables
- Missing values analysis
- Duplicate row analysis
- Data types
- Overall data quality assessment

Do not invent information that does not exist in the dataset.
```

---

# Prompt 2: Descriptive Statistics

```text
Generate descriptive statistics for all numeric variables in the dataset.

Include:
- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Q1
- Q3

Identify:
- Variables with the highest variability
- Variables with the lowest variability
- Any unusual ranges or distributions

Write observations clearly and professionally.
```

---

# Prompt 3: Correlation Analysis

```text
Calculate Pearson correlations for all numeric variables in the dataset.

Identify:
- Top 10 strongest correlations
- Weakest correlations
- Variables that scale together
- Relationships between limb measurements and girth measurements

Explain the findings using clear statistical reasoning.
```

---

# Prompt 4: Outlier Detection

```text
Perform outlier detection using the IQR method for all numeric variables.

For each variable:
- Count the number of outliers
- Rank variables by outlier frequency
- Identify extreme upper or lower values

Do not remove outliers automatically.

Explain what the outliers could indicate while avoiding unsupported assumptions.
```

---

# Prompt 5: Waist Circumference Distribution

```text
Analyze the waist circumference distribution.

Group the waist measurements into size bands and calculate:
- Counts
- Percentages
- Distribution concentration

Identify:
- Most common waist range
- Presence of skewness
- Spread of the data

Summarize findings professionally.
```

---

# Prompt 6: Height-Based Segmentation

```text
Split the dataset into five equal height groups using quintiles.

For each group calculate average:
- Chest circumference
- Waist circumference
- Hip circumference
- Thigh circumference
- Bicep circumference

Explain how body measurements change as height increases.
```

---

# Prompt 7: Waist-to-Height Ratio Analysis

```text
Calculate waist-to-height ratio for all subjects.

Provide:
- Mean
- Standard deviation
- Minimum
- Maximum
- Percentage above 0.5
- Percentage below 0.5

Describe the distribution clearly without making medical or clinical claims.
```

---

# Prompt 8: Full Exploratory Data Analysis Report

```text
You are a Junior Data Analyst performing a professional exploratory data analysis on a body measurement dataset.

Generate a structured EDA report using only the uploaded dataset.

The report must include:
1. Executive Summary
2. Dataset Overview
3. Data Quality Assessment
4. Descriptive Statistics
5. Distribution Analysis
6. Outlier Analysis
7. Correlation Analysis
8. Waist Distribution Analysis
9. Height-Based Segmentation
10. Waist-to-Height Ratio Analysis
11. Key Findings
12. Limitations
13. Recommendations

Requirements:
- Use exact figures from the dataset
- Avoid unsupported assumptions
- Do not invent demographic information
- Keep findings descriptive and evidence-based
- Use professional analytical language
- Clearly separate observations from interpretations
```

---

# Reflection

The prompts were designed to:
- Guide structured analysis
- Reduce hallucinated insights
- Keep outputs evidence-based
- Improve analytical consistency
- Validate AI-generated findings critically

The final report was reviewed manually and refined to improve accuracy and clarity.
