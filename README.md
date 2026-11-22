# Age-at-death-comparison-by-handedness

An Excel analysis project comparing age at death between right-handed and left-handed people.

##  Important Note
This project uses a synthetic practice dataset with 1,000 records. It is not the original Maven Analytics source dataset and should not be presented as real source data.

## Project Overview
The goal is to compare longevity across handedness groups using descriptive statistics and a dashboard.

## Workbook Structure
| Sheet | Purpose |
|-------|---------|
| Row_Data | Source records (1,000 rows) |
| Dashboard | Visual presentation of results |
| Summary | Statistical summary table |
| README | Project notes |

## Key Results

| Handedness | People | Avg Age | Median | Min | Max | Std Dev |
|------------|--------|---------|--------|-----|-----|---------|
| Right      |    875 |  71.71  |   72   | 38  | 100 |   10.08 |
| Left       |    125 |  71.19  |   72   | 42  | 89  |    9.35 |

## Findings
- Right-handed people averaged **71.71** years vs **71.19** for left-handed, a difference of about 0.5 years.
- Both groups have the same median age at death (**72**).
- Right-handed people show slightly more variation (std dev 10.08 vs 9.35).

## Interpretation
Differences in this dataset should **not** be interpreted as proof that handedness causes differences in longevity. The data is synthetic, and the gap is very small.

## Tools Used
- Microsoft Excel (formulas, summary statistics, dashboard)

## Files
- `Age_at_Death_Comparison_by_Handedness.xlsx` – the full workbook

