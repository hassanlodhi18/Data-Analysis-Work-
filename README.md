# Data-Analysis-Work-
# Data Analytics Solutions

Excel solutions to 19 business-analytics scenarios spanning four difficulty levels — 
basic aggregation, conditional logic & ranking, advanced nested logic, and expert-level 
interactive BI formulas.

## Datasets
- **Superstore** (9,994 orders) — sales, profit, region, segment, shipping data
- **Sales Dataset** (50,000 records) — category-level revenue and pricing
- **IMDb Top 1000** — movie ratings, gross revenue, runtime

## What's inside
Each answer is a **live Excel formula** (not a hardcoded value), so results update 
automatically if the underlying data changes. Row-level tasks (tiering, ranking, 
region coding, audit sampling) are implemented as helper columns directly on the 
relevant data sheet; single-value tasks (totals, medians, percentiles, rank thresholds) 
live on a dedicated **Answers** summary sheet.

Covers: SUM, COUNT, MAX/MIN, MODE, MEDIAN, SUMIFS/COUNTIFS/AVERAGEIFS, RANK, 
STDEV.S, QUARTILE.INC/PERCENTILE.INC, nested IF, XOR logic, SUBTOTAL + IFERROR 
for filter-safe dashboards, and more.

## Structure
- `Answers` — summary of all 19 questions with method, formula, and result
- `Superstore` — raw data + helper columns (audit flag, profit tier, gift-eligibility flag, region code, sales rank)
- `SalesDataset` — raw data
- `IMDB` — raw data + rating-tier helper column
