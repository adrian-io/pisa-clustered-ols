# pisa-clustered-ols
Prediction of all countries’ PISA scores with macroeconomic indicators using pooled OLS with clustered standard errors.

## Out-of-sample prediction scores:
| Metric          | PISA Math Scores  | PISA Reading Scores| PISA Science Scores|
| -------------   |:-------------:| :----------:             | :------------------:|
| $R^2$           |  0.7815       | 0.7007                 | 0.7185             |
| $R^2_{adjusted}$|  0.7772       |   0.6954               | 0.7119             |
| RMSE            | 18.9328       |    23.9736             | 15.1846            |
| Predictors      |'GINI', 'log(PCT_EDU_TRY)', 'ALC_PC', 'HOMICIDES' | 'CPI', 'GINI', 'log(PCT_EDU_TRY)', 'ALC_PC'| 'log(PCT_EDU_TRY)', 'GINI', 'ALC_PC', 'CPI'|



Data from [OECD](https://data.oecd.org/ "OECD Data") and [Worldbank](https://data.worldbank.org/ "Worldbank Data").
