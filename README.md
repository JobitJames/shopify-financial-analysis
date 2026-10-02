# Shopify Inc. (SHOP) — Financial Analysis & Forecast Validation

A complete equity research project on Shopify Inc. (NASDAQ: SHOP), built April 2026 and validated against real market outcomes in October 2026.

## What's Inside

| File | Description |
|------|-------------|
| `Shopify_Technical_Analysis.ipynb` | Python: Monte Carlo simulation + FB Prophet 90-day forecast |
| `Shopify_FCF_WACC_Analysis.xlsx` | Excel: FCF analysis, WACC calculation, DCF valuation |
| `Shopify_Presentation.pptx` | Full 22-slide equity research presentation |

## Key Results

- **WACC:** 11.9% | **Intrinsic Value:** $51.71/share | **Market Price:** $114.84
- **Monte Carlo (30-day):** Mean forecast $126.25 — *Actual May 2026: ~$122* 
- **FB Prophet (90-day):** Forecast $132.27 — *Actual Aug 2026: $145+* 
- **Investment Signal:** BUY — both models confirmed bullish


## ⚠️ Note on Output Numbers

The original analysis was completed in **April 2026** as part of a Financial Analytics project.

The Python notebook (`Shopify_Technical_Analysis.ipynb`) pulls **live data from yfinance** each time it is run, so output numbers (Monte Carlo forecast, Prophet forecast, current price) will differ from the original results depending on when you run it.

**Original results (April 2026):**
- Monte Carlo Mean Forecast: $126.25
- FB Prophet 90-Day Forecast: $132.27

**Recent rerun (October 2026):**
- Monte Carlo Mean Forecast: $116.54
- FB Prophet 90-Day Forecast: $152.46

This is expected behavior — the models use the most recent 1 year of price data available at runtime. The methodology and code remain unchanged.

## Tools Used

Python (yfinance, Prophet, Plotly, pandas, numpy, matplotlib) | Excel | Financial Modeling | DCF Valuation | CAPM | Beta Analysis
