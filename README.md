# Econometrics

My notebooks for the *Introduction to Econometrics* course (ESSEC / CentraleSupélec AIDAMS, Prof. Roberto Renò, 2026). They follow case studies from Békés and Kézdi, *Data Analysis for Business, Economics, and Policy* (Cambridge University Press, 2021), with my own extensions.

| Notebook | Topic |
|---|---|
| `01 - histograms and scatter` | exploring Vienna hotel prices: distributions, outliers, price vs distance |
| `02 - risk management_2026` | daily stock returns from yfinance treated as a sample: sampling distribution, standard errors, confidence intervals |
| `03 - offline price test` | hypothesis test: are online and offline prices the same? |
| `04 - hotels - simple - regression` | simple linear regression of hotel price on distance |
| `04 - hotels - regression - objective function` | least squares vs least absolute deviation, sensitivity to outliers |
| `04 - regression Monte Carlo` | simulating the OLS estimator to see its bias and variance |
| `06 - earnings gender` | gender wage gap, wage vs age |
| `07 - earnings gender multi` | multiple regression: how much of the gap remains after controlling for education and age |

Datasets are in `Data/`. The two earnings notebooks also use the CPS extract `morg-2014-emp.csv`, too large for the repository; it can be downloaded from [gabors-data-analysis.com](https://gabors-data-analysis.com/) into `Data/`.

```bash
pip install pandas numpy statsmodels matplotlib seaborn yfinance
jupyter notebook
```
