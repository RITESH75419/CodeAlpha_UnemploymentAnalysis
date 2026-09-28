# Unemployment Analysis in India (COVID-19 Impact)

CodeAlpha Data Science Internship - Task 2

## Objective
Analyse the trend of unemployment in India and measure the impact of the COVID-19 lockdown.

## Dataset
Kaggle: Unemployment in India (gokulrajkmv). State-wise monthly data
(May 2019 - June 2020) with Urban/Rural split.

## Approach
1. Cleaned column names, parsed dates, removed nulls and duplicates.
2. Split data into Pre-COVID and COVID (Apr 2020 onwards).
3. Analysed national trend, Urban vs Rural, state-wise impact and labour participation.

## Key Findings
- Mean unemployment rose from 9.61% to 20.19% after lockdown.
- National average peaked in May 2020 at 24.88%.
- Highest state peaks: Puducherry (76.74%), Jharkhand (70.17%), Bihar (58.77%).
- Urban areas were hit harder (10.91% to 22.08%) than Rural (8.23% to 18.26%).
- Labour participation fell most in Tamil Nadu (-14.97 points).

## Limitations
- COVID period has only 3 months (Apr-Jun 2020) vs 11 months pre-COVID.
- 7 state-month values are missing in the data.
- Data ends in June 2020, so recovery is not covered.

## Project Structure
- `Notebooks/Unemployment_Analysis.ipynb` - full analysis
- `data/` - raw and cleaned CSV files
- `visualizations/` - charts

## Tools
Python, pandas, numpy, matplotlib, seaborn
