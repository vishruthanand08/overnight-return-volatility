# Overnight Return Magnitude as a Predictor of Next-Day Realized Volatility (SPY)

This project investigates whether the magnitude of overnight returns (close→open price gaps) contains predictive information about next-day realized volatility in SPY.

Using 20 years of daily data (2005–2025), I compute:

- Overnight returns
- Intraday returns
- Range-based volatility
- Parkinson realized volatility
- Rolling correlations
- OLS regressions
- GARCH(1,1) models

### Key Findings
- Overnight return magnitude is a strong predictor of next-day realized volatility.
- OLS coefficient: **β = 0.0242**, highly significant (t ≈ 43.6)
- R² = 0.266 — very high for a single volatility factor
- Rolling correlation spikes during crisis regimes (2008, 2020, 2022)
- Market microstructure intuition: overnight information → order imbalance → elevated volatility

### Files
- `OvernightVolatilityProject.ipynb` — full analysis + code  
- `OvernightVolatilityReport.pdf` — formatted final paper  

---

### Author
Vishruth Anand  
November 2025
