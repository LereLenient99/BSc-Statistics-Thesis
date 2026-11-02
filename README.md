# Modeling Road Traffic Crashes in Kwara State (2015-2021)[cite: 1]

**Author:** Abdhamid, Mubarak Alao[cite: 1]  
**Institution:** University of Ilorin, Department of Statistics[cite: 1]  
**Degree:** Bachelor of Science (Honours) Degree in Statistics[cite: 1]  

## Overview
This repository contains the analysis and findings for the modeling of road traffic crashes data in Kwara state, Nigeria, utilizing data collected from the policy and research department of the Federal Road Safety Commission of Kwara state between January 2015 and June 2021[cite: 1]. The study aims to assess factors contributing to the high rate of crashes and fit an appropriate mathematical model to understand and manage this data[cite: 1]. 

## Methodology
To account for count data and the presence of over-dispersion, the research evaluates and compares three statistical models[cite: 1]:
* **Poisson Regression Model:** Used as the initial baseline model for count data[cite: 1]. The data exhibited over-dispersion, as indicated by a deviance value of 405.020 (which is greater than 1), making this model inadequate on its own[cite: 1].
* **Negative Binomial Regression (NBR):** Applied to address the issue of over-dispersion by including a dispersion parameter to accommodate unobserved heterogeneity[cite: 1].
* **Generalized Negative Binomial Regression (GNBR):** Developed by compounding the negative binomial distribution with another parameter to account for variations in both the mean and the variance[cite: 1]. 

## Key Findings
* **Optimal Model:** The Generalized Negative Binomial Regression (GNBR) model is the ideal model for fitting the rate of road traffic crashes in Kwara state[cite: 1]. It yielded the minimum Akaike Information Criterion (AIC) of 510.6621, Bayesian Information Criterion (BIC) of 550.7261, and Residual Deviance of 87.0556[cite: 1].
* **Significant Timeframes:** There is a high rate of road traffic accidents in the first quarter (Q1) and the second quarter (Q2) of the year[cite: 1]. The least cases of road accidents were recorded in the months of September and December[cite: 1]. The months of October, February, May, and August are statistically significant in the model[cite: 1].
* **Accident Determinants:** The number of causes, number of people killed, and the number of injured people have a significant effect on the rate of road traffic crashes[cite: 1]. 
* **Rule Violations:** The violation of one or more traffic rules by motorists and pedestrians increases the rate of road traffic accidents by approximately 3.3%[cite: 1].

## Recommendations
Based on the modeling results, the study recommends that more attention be paid to the first and second quarters of the year to minimize road accidents[cite: 1]. It also suggests making traffic rules stricter with serious penalties for failures to abide, and appointing traffic inspectors at every junction to maintain proper traffic flow[cite: 1].
