# Analysis-of-A1C-Results-Across-Patient-Populations

### Overview
This repository contains an R-based analysis comparing Hemoglobin A1C (HbA1c) test results across two patient populations: Direct-to-Consumer (DTC) and Gaps-in-Care (GIC). The analysis combines descriptive statistics, distributional analysis, and a nonparametric Wilcoxon rank-sum test to evaluate whether A1C values differ significantly between groups. Results indicate that GIC patients exhibit both higher median A1C levels and a substantially higher prevalence of diabetes-range results, suggesting meaningful differences in clinical risk profiles and downstream care needs.

### Business Impact
This project evaluates whether patient populations differ in ways that materially affect:
- Risk stratification
- Pricing models
- Care coordination staffing and outreach planning

The findings support the hypothesis that GIC populations represent a higher-risk, higher-intensity cohort, implying:
- Greater expected outreach volume
- Increased care management complexity
- Potential need for differentiated pricing and operational support models


### Key Results
- Sample size: 36,000+ A1C test results
- Median A1C difference: ~1.0% higher in GIC vs DTC (95% CI)
- Diabetes prevalence (A1C ≥ 7.0): GIC: ~40%, DTC: ~7.5%
- Distribution shape: Both groups are right-skewed


### Methods
- Exploratory data analysis using histograms and summary statistics
- Assessment of distributional assumptions (non-normal, right-skewed)
- Selection of Wilcoxon rank-sum test due to violation of normality assumptions
- One-sided hypothesis test based on expected higher risk in GIC population


### Limitations
- Age and other demographic variables were not available
- Analysis is observational and does not imply causality
- Results are specific to A1C testing and does not generalize to other diagnostic tests


### Privacy
This project was conducted using de-identified patient data.
