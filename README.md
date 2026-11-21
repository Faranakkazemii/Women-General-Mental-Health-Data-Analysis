# Women's General & Mental Health Analysis

## Project Overview

This project explores associations between women's self-reported general health, mental health, demographic characteristics, socioeconomic factors, and lifestyle behaviors using data from the **2023 Behavioral Risk Factor Surveillance System (BRFSS)**.

The analysis combines exploratory data analysis, statistical testing, data visualization, and multivariable logistic regression to investigate patterns relevant to public health.

## Dataset

- **Source:** CDC Behavioral Risk Factor Surveillance System (BRFSS), 2023
- **Study population:** Female respondents
- **Initial analytical dataset:** 229,523 records
- **Variables:** 16 selected variables covering health outcomes, demographic characteristics, socioeconomic factors, and lifestyle behaviors

## Project Objectives

- Explore patterns in women's general and mental health.
- Examine associations between health outcomes and demographic, socioeconomic, and lifestyle characteristics.
- Apply statistical methods to evaluate relationships between variables.
- Identify factors associated with frequent mental distress.
- Visualize and interpret findings from a public health perspective.

## Methodology

The analysis includes:

1. **Data preparation:** Variable selection, missing-value handling, duplicate checks, and data validation.
2. **Exploratory data analysis:** Descriptive statistics and visualizations of health outcomes and participant characteristics.
3. **Statistical analysis:** Spearman correlation, chi-square tests, Mann–Whitney U tests, and Kruskal–Wallis tests.
4. **Multivariable logistic regression:** Examination of adjusted associations with frequent mental distress, defined as 14 or more poor mental-health days.
5. **Model assessment:** ROC curve analysis and training ROC-AUC calculation.

## Key Findings

- **Income:** Higher income was associated with better self-reported general health.
- **Age:** Older women tended to report poorer general health but fewer poor mental-health days.
- **Exercise:** Women reporting no exercise had approximately 77.4% higher adjusted odds of frequent mental distress.
- **Smoking:** Daily smokers had approximately 2.10 times the adjusted odds of frequent mental distress compared with never smokers.
- **Predictive model:** The logistic regression model achieved a training ROC-AUC of 0.727.

These findings describe statistical associations, not causal relationships.

## Limitations

This was an exploratory, cross-sectional analysis. The analysis was unweighted and did not account for the BRFSS complex survey design.

Missing data reduced the regression sample to 153,742 observations. Health measures were self-reported, and model performance was evaluated on training data only.

The results should therefore be interpreted cautiously and should not be considered validated population-level estimates or evidence of causation.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Statistical analysis and data visualization

## Project Files

- [`Project_01.ipynb`](Project_01.ipynb) — Jupyter notebook containing the analysis, visualizations, statistical tests, and model results.

## Conclusion

Socioeconomic and lifestyle characteristics showed measurable associations with women's health. General health and mental health displayed different patterns across age groups, highlighting the importance of examining these outcomes separately in public health research.
