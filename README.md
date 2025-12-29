# Mortality Risk Analysis in Indonesia

This repository analyzes adult mortality dynamics in Indonesia using time-series methods,
with a focus on forecasting, shock analysis, and mortality improvement relevant to longevity risk.

The project is designed as a portfolio-level study combining statistical rigor with actuarial intuition,
using publicly available mortality data.

---

## Data

- **Source**: Indonesian adult mortality data (BPS / WHO-based compilation)
- **Period**: Annual observations
- **Variables**:
  - Adult mortality rate (male)
  - Adult mortality rate (female)

---

## Methodology Overview

- Log-transformation of mortality rates
- ARIMA-based time-series modeling
- Shock decomposition using counterfactual baselines
- The mortality improvement index is defined as:

$$
I_t = \ln\left(\frac{m_t}{m_{t-1}}\right)
$$

where negative values indicate mortality improvement.

---

## Key Insights

- Adult mortality exhibits long-term declining trends with persistent gender differences
- Mortality shocks are temporary deviations rather than structural breaks
- Mortality improvement rates show volatility patterns relevant to longevity risk modeling

---

## Limitations

- Short time series limits model complexity
- Results are illustrative rather than predictive for policy use
- Mortality data is aggregated and not age-specific

---

## Tools

- Python
- pandas, numpy
- statsmodels
- matplotlib

---


