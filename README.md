# Risk Management: A Bayesian Analysis of Race, Insurance and Maternal Pregnancy Risk in the United States

A collaborative final project for SDS 390: Bayesian Statistics at Smith College.

Contributors: Isabel Gomez, Annabel Yim, Elisabeth Nesmith, Neamat Sabry

# Description
Despite advances in health care, multiple studies have shown that thousands of mothers — particularly women of color — experience maternal morbidity each year. Furthermore, the widening wealth gap in the U.S. limits access to the health care needed to reduce the risk of morbidity. Using the Center for Disease Control’s 2018 Natality Data, this study looks at the association between a mother’s race, insurance, and whether the mother exhibits increased risk during pregnancy. We used Bayesian multivariate logistic regression and posterior prediction to test the hypothesis that women of color and women who do not have health insurance are more likely to experience increased risk during pregnancy. It was found that mothers of color have higher probabilities of increased risk than their white counterparts, regardless of whether or not they have insurance. Moreover, not having insurance decreased the probability of risk, likely due to the size of our sample.

We used three Bayesian multivariate logistic regressions to model pregnancy risk factors. We chose the Bayesian approach for its posterior predictive functionality and the ease of building off of our study. The first model included binary race and binary health insurance as explanatory variables. The second model included an additional interaction term between race and health insurance. And the third model used the original race variable with 4 levels and the binary health insurance variable as explanatory variables. All three models adjusted for age and marital status. Finally, we constructed a log-odds prediction model and posterior predictive model for whether or not an individual experienced increased risk.

# Code
The two rmd files which are of most importance to the study are pregnancy_risk_exploration.Rmd, in which we wrangle the data and build our three separate models for pregnancy risk factors, and posterior_prediction.Rmd, in which we construct the posterior predictive model for increased risk and generate predictions. 






