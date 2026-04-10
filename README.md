# 🏬 Abu Dhabi Retail Sector Analysis (2010–2016) 🚀

## Problem Statement
Abu Dhabi's economy is oil-dependent. This analysis tests whether the retail 
sector shows independent growth from oil price movements — a key indicator 
of successful economic diversification.

## 🎯 Executive Summary

**3 Key Insights:**
| Insight | Finding | Implication |
|---------|---------|-------------|
| **Labor Surge** | +965M AED/yr comp growth (R²=0.99) | Cost pressure despite oil crash |
| **GDP Resilience** | GDP share +0.25%/yr stable | Sector held vs macro shock |
| **Independent KPIs** | Correlations <0.1 | Diverse drivers |

## 📊 Analysis Stack
Statistical: scipy.stats (correlation + linregress)
Macro: Brent oil (FRED POILBREUSDM)
Comparative: Indexed trends + ratios
Predictive: Linear extrapolation + scenarios
Dashboard: Plotly + Tableau exports


## 📈 Results (2010→2016)
Employee Comp: 8.2B → 14B AED [+70%]
GDP Share: 4.2% → 5.5% [+31%]
Non-Oil GDP: 8.2% → 8.1% [stable]


## 🛠️ Tech
pandas | scipy.stats | seaborn | plotly | Jupyter
CSV exports (Tableau/PowerBI ready)


## 📂 Structure
├── data/uae_retail_trade_2010_2016.xlsx
├── eda_uae_retail_detailed.ipynb
├── retail_kpis_long_dashboard.csv
├── retail_kpi_summary.csv
└── retail_complete_with_oil.csv


## 🚀 Run
```bash
pip install pandas scipy seaborn matplotlib plotly
jupyter notebook eda_uae_retail_detailed.ipynb
```

## 📊 Exports Ready
- `retail_kpis_long_dashboard.csv` → Tableau selector
- `retail_kpi_summary.csv` → Executive table
- `retail_complete_with_oil.csv` → Full analysis

## 🎓 Skills
Data wrangling → Stats → Macro → Forecasting → Dashboards