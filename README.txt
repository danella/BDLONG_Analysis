This repository includes code for the primary analysis of the Bipolar Disorder Longitudinal Imaging Study (BDLONG), as of submission of Revision 1 (12/26/2024). 

This code: 
(1) imports functional connectivity matrices (extracted using nilearn); 
(2) outputs scan-scan similarity metrics (Pearson correlation coefficients) for all scans in the dataset, both within- and between-person;
(3) integrates these values with scan-pair and subject-level covariate dataframes; 
(4) conducts scan-pair-level (Bayesian Mixed Models, stan_lmer) analyses
(5) returns primary Figures (in main text)
(6) conducts subject-level similarity analyses (non-parametric tests due to small numbers)

This code does not include:
(1) Code to create Table 1
(2) Analysis of raw covariate data to construct the .rds object with relevant covariate dataframes
(3) Supplemental and sensitivity analyses. For relevant code, please contact the authors.
