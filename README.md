# Meridian HR — Workforce Retention Analysis

An end-to-end HR analytics project: cleaning a 5,000-record employee dataset, analyzing turnover, absenteeism, and compensation patterns, and building an interactive Excel dashboard to support a workforce retention strategy.

## Business Question

Meridian Financial Services was losing staff and seeing inconsistent performance across departments. This project answers:

1. Which department has the highest turnover, and does it correlate with salary or tenure?
2. Is there a relationship between absenteeism and performance?
3. Which employee demographics are most associated with resignation?
4. How does compensation compare across departments, and does it align with performance?

## Key Findings

- **Sales has the highest turnover (49%)** — driven by below-average pay and the lowest performance score of any department.
- **Absenteeism and performance are linked** — Information Technology has the highest absenteeism (10.4 days/year) alongside below-average performance.
- **Employees aged 31–40 drive the largest share of resignations** (~35%), the group with the most external options and highest flight risk.
- **Human Resources is a hidden retention risk** — its best-in-company performance score is paired with below-average pay.

Full narrative: [`docs/written-summary.md`](docs/written-summary.md)

## Process

1. **Data cleaning** — removed 50 duplicate records, standardized missing values, documented data-quality issues.
2. **Descriptive statistics** — company-wide and department-level averages for salary, performance, and absenteeism.
3. **Pivot table analysis** — turnover rate, absenteeism vs. performance, demographic breakdowns, salary comparison.
4. **Written summary** — plain-language findings and recommendations for HR leadership.

## Repo Structure

```
├── README.md
├── analysis/
│   └── MeridianHR_Analysis_FINAL.xlsx    # full workbook: data, pivots, dashboard
├── docs/
│   └── written-summary.md                # board-ready narrative summary
└── data/
    └── clean_data.csv                    # cleaned dataset (anonymized)
```

## Tools Used

Excel (PivotTables, SUMPRODUCT/AVERAGEIFS formulas, native charts)

## Note on Data

This dataset is a fictional practice dataset. Employee names have been anonymized in the public version of this data (`data/clean_data.csv`) as standard practice for any HR dataset, real or simulated.
