## Longitudinal Analysis of Hemoglobin Trajectories under Enhanced Seasonal Malaria Chemoprevention (eSMC)

This project applies linear mixed-effects modelling to longitudinal data from a randomized controlled trial of 300 children (aged 12–59 months) to evaluate the impact of Enhanced Seasonal Malaria Chemoprevention (eSMC) on hemoglobin levels over a 6-month malaria transmission period .

Hemoglobin was measured at four time points (baseline, months 2, 4, and 6). A Linear Mixed Model (LMM) with random intercepts and slopes was fitted to account for within-child correlation and individual variability in trajectories.

Fixed effects included time (month), treatment group, age, and ITN use, with a key treatment and time interaction to assess differential trends between groups. Model selection was based on likelihood ratio tests and AIC, with the random intercept and random slope model with interaction identified as the best-fitting model.

Results showed that hemoglobin declined in the control group (0.162 g/dL per month), while remaining stable in the eSMC group. The significant interaction effect (β = 0.205, p < 0.001) indicates that the benefit of eSMC increases over time, resulting in an approximate 1.3 g/dL advantage by month 6.

Model diagnostics (residual plots and Q-Q plots) confirmed that assumptions of normality and homoscedasticity were reasonably satisfied. The analysis also identified positive effects of age and ITN use on hemoglobin levels, and substantial between-child variability (ICC = 0.70).

#### Packages used in R: `lme4`, `ggplot2`, `dplyr`, `survival`, `survminer`.
