# South Australian Electricity Market Analysis

## Overview
This project analyses 5-minute dispatch and pricing data from the Australian 
National Electricity Market (NEM) to evaluate the commercial performance of 
15 generators across five technologies in South Australia over two financial 
years (FY2022/23 – FY2023/24).

## Dataset
AEMO NEM 5-minute dispatch data — 210,526 observations (after cleaning)
Raw file contained 315,632 rows across July 2022 to June 2024.

## Objectives
Advise a client considering investment into a renewable energy developer 
operating in South Australia by identifying which technologies offer the 
strongest revenue performance, lowest market risk and best long-term 
investment potential.

## Methodology
- Dispatch-weighted capture price analysis (DWP = Σ(Price × Dispatch) / Σ(Dispatch))
- Revenue variability measurement using Coefficient of Variation (CoV)
- Capacity factor calculation benchmarked against AEMO industry ranges
- Intra-daily dispatch and price pattern analysis
- Negative price exposure quantification by technology

## Key Results
- Solar recorded $10.84M in revenue losses from price cannibalisation
- Wind achieved the lowest revenue volatility (CoV 68.57%) among all technologies
- Wind capacity factor: 27.38% — within AEMO benchmark range of 25–40%
- Gas generated the highest absolute revenue but declined 40% from FY23 to FY24

## Key Insights
- Wind is the strongest renewable investment — highest renewable capture price, 
  lowest revenue risk and most predictable cash flows
- Solar cannibalisation is a structural problem that worsens as solar penetration 
  increases; 42.16% of solar dispatch occurred during negative-price periods
- Battery storage achieved a high capture price ($397.95/MWh) through peak-price 
  arbitrage and works best as a complement to renewable generation
- Gas and diesel face long-term stranded asset risk from rising renewable 
  penetration and carbon obligations

## Tools
Python | pandas | NumPy | Matplotlib | Seaborn | SciPy | Jupyter Notebook

## Disclaimer
Developed as part of a Master of Business Analytics program at Macquarie 
University. Raw dataset not included due to file size and data source 
restrictions. Data sourced from AEMO's publicly available NEM dispatch records.
