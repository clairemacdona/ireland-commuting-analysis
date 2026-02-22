# 36-Year Analysis of Commuting Patterns in Ireland (1986–2022)

## Project Overview
This project analyses Irish Census commuting data (1986–2022) to examine long-term changes in transport behaviour, with a focus on modal share, car dependency, gender differences and lifecycle travel patterns.
The analysis focuses on proportional metrics over absolute counts to identify structural behavioural shifts rather than population-driven growth.

## Key Findings
- Private motor transport for workers increased from **~64% in 1986 to nearly 80% by 2011.**
- Sustainable transport declined significantly and has not returned to 1986 levels.
- Gender differences exist but are modest compared to differences across activity types.
- Travel behaviour shows clear lifecycle patterns with car dependency strengthening into adulthood.

## Visualisations

### Modal Share Shift (1986–2022)
![Modal Share Shift](./figures/modal_share_shift_1986_2022.png)

### Travel Volume by Mode
![Travel Volume by Mode](./figures/travel_volume_by_mode.png)

### Mode Share by Gender & Activity
![Mode Share by Gender & Activity](./figures/mode_share_gender_activity.png)

### Education Cohort Travel Patterns
![Education Cohort Travel Patterns](./figures/education_cohort_travel_patterns.png)

## Tools Used
- R
- dplyr
- ggplot2
- tidyr
- purrr
- Quarto

## What This Project Demonstrates
- Data cleaning and transformation of government datasets
- Longitudinal trend analysis
- Proportional modal share calculation
- Segmentation by gender and activity
- Clear visual communication of insights

## Files Included
- `commuting_analysis.qmd` – Full Quarto analysis document
- `commuting_patterns.pdf` – Rendered project report
- `figures/` – Exported visualisation

# Repository Structure
```text
ireland-commuting-analysis/
│
├── commuting_analysis.qmd
├── commuting_patterns.pdf
├── figures/
│   ├── modal_share_shift_1986_2022.png
│   ├── travel_volume_by_mode.png
│   ├── mode_share_gender_activity.png
│   ├── education_cohort_travel_patterns.png
└── README.md
```

## Data Source
Irish Census of Population, 1986–2022. Available at [Central Statistics Office](https://www.cso.ie/).
