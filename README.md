# RIHA — Global Women's Safety & Equality Analytics

**Tagline: Freedom Without Fear.**

## Overview

RIHA is a real-world data analysis project exploring women's safety through data on intimate partner violence across countries. Using Python, the project examines modeled lifetime prevalence estimates for ever-partnered women aged 15–49 in 2023.

The project uses data cleaning, statistical analysis, exploratory data analysis (EDA), and visualization to explore global patterns and differences in the estimates.

## Key Findings

The analysis covered 162 countries using 2023 estimates.

| Statistic | Result |
|---|---:|
| Countries analyzed | 162 |
| Mean prevalence | 25.59% |
| Median prevalence | 23.90% |
| Minimum estimate | 4.70% |
| Maximum estimate | 60.70% |
| Range | 56.00 percentage points |

Fiji had the highest estimate in the analyzed dataset (60.7%), while Kosovo had the lowest (4.7%).

These are modeled prevalence estimates, not counts of police reports or individual incidents.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

- `riha_analysis.ipynb` — Main analysis notebook
- `data/raw/` — Original datasets
- `data/processed/` — Cleaned datasets
- `outputs/figures/` — Charts and summary results

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter