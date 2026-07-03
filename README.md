
# Student Performance Analysis

An exploratory data analysis project examining how demographic and preparatory factors relate to student exam performance across math, reading, and writing.

## Overview

This project analyzes exam scores of 1,000 students to identify which factors — gender, parental education, test preparation, and lunch type (a proxy for socio-economic status) — are associated with academic performance.

## Dataset

- **Source:** Student Performance dataset (1,000 records, 8 features)
- **Features used:** Gender, race/ethnicity, parental level of education, lunch type, test preparation course completion, math score, reading score, writing score

## Process

1. **Data Loading & Quality Check** — Verified there were no missing values across all columns
2. **Feature Engineering** — Created an `average_score` column combining math, reading, and writing scores
3. **Exploratory Analysis** — Visualized average scores across gender, parental education level, test preparation status, and lunch type
4. **Correlation Analysis** — Examined relationships between math, reading, and writing scores using a correlation heatmap

## Key Findings

- **Test preparation matters:** Students who completed a test preparation course scored noticeably higher on average than those who did not
- **Gender gap:** Female students had a higher average score (~72) than male students (~68)
- **Parental education correlates with performance:** Students whose parents held a master's degree had the highest average scores; students whose parents had only some high school education scored lowest
- **Socio-economic indicator:** Students with standard lunch (vs. free/reduced lunch) scored consistently higher, suggesting a socio-economic performance gap
- **Strong subject correlation:** Reading and writing scores were the most strongly correlated (0.95), followed by math–reading (0.82) and math–writing (0.80) — students strong in one subject tend to be strong across all three

## Tech Stack

- **Python**
- **pandas** — data manipulation and grouping
- **matplotlib / seaborn** — data visualization and correlation heatmap

## What I Learned

This project reinforced how to translate exploratory data analysis into clear, actionable insights — identifying not just *what* the data shows, but *why* it matters (e.g., the link between test preparation and outcomes suggests a concrete, actionable intervention for improving student performance).
