# Analysis-of-A1C-Results-Across-Patient-Populations

#### Overview
This repository contains a reproducible R-based analysis comparing A1C test results across Direct-to-Consumer (DTC) and Gaps-in-Care (GIC) patient populations. The project uses descriptive statistics, distributional analysis, and a Wilcoxon rank-sum test to assess whether A1C values differ significantly between the two groups. Results show that GIC patients have a higher median A1C and a substantially higher share of diabetes-range results, suggesting greater downstream outreach and care-coordination needs.

#### Business Impact
The purpose of this project was to identify if differences between two patient populations exist, and if so, provide support for alternative risk and price modeling as well as inform care coordination staffing. 


#### Key Results
- sample size after exclusions: 36k+
- median A1C is approximately 1.00% higher for GIC patients than DTC patients (95% CI)
- clinical definition of diabetes (>=7.0) varied greatly by group (40% vs 7.5%)


#### Methods
Histograms of A1C results for both gorups were heavily skewed right. Any efforts at transformations did not approximate  a normal distribution thus a nonparametric method was selected. Wilcoxon rank-sum test compares group medians.


#### Privacy
This project was an extension of my graduate studies and contains deidentified patient data. Raw data cannot be made available.
