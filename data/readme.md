# Data Sources

This folder documents the data sources and expected file names used in the analysis.

The raw CSV files are not uploaded to this repository. The project uses publicly available market data, but the raw data files may be subject to the terms of the original data providers. For this reason, only the data sources and expected file names are documented here.

## Data used

1. Baltic Dry Index historical data  
   Source: Investing.com  
   Expected file name: `Baltic Dry Index Historical Data.csv`

2. Iron Ore 62% Fe CFR Futures historical data  
   Source: Investing.com  
   Expected file name: `Iron ore fines 62% Fe CFR Futures Historical Data.csv`

3. Brent crude oil daily data  
   Source: FRED  
   Expected file name: `DCOILBRENTEU.csv`

## Notes

The analysis uses approximately one recent year of daily data.

The data is cleaned and merged by date in the notebook. Missing values caused by different market calendars are forward-filled for this first diagnostic version.

Because the sample is short, the results should be interpreted as a short-term market diagnostic view rather than a long-run structural study.
