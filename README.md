# IPL Franchise Efficiency Analysis (2018–2025)
### A Data Envelopment Analysis of Resource Allocation and Performance Efficiency in IPL Franchises: The Role of Home Pitch Conditions

**Author:** Ujjwal Aditya Birenji
**Programme:** MSc Business Analytics, Aston University
**Status:** 🚧 In Progress — Expected completion October 2026

---

## Project Overview

This project uses **Data Envelopment Analysis (DEA)** to evaluate how efficiently Indian Premier League (IPL) franchises allocate resources — auction spend across batting, bowling, and all-rounder departments — relative to their on-field performance outcomes.

A second research question examines whether franchises that build squads suited to their **home pitch conditions** (e.g. spin-friendly vs pace-friendly surfaces) achieve greater efficiency and performance than those that don't.

## Objectives

- Evaluate the relative resource-allocation efficiency of IPL franchises using DEA.
- Determine whether squad construction aligned with home pitch conditions correlates with higher efficiency scores.
- Identify which franchises consistently operate on or near the efficiency frontier, and what drives that performance.

## Data

All data used is **secondary and publicly available** — no human participants are involved.

| Category | Details |
|---|---|
| Sources | Official IPL website, ESPN Cricinfo, Cricbuzz, Kaggle datasets |
| Seasons covered | 2018–2025 |
| Franchise-level data | Auction expenditure (batters/bowlers/all-rounders), league points, net run rate, home/away win %, playoff qualification |
| Player-level data | Batting/bowling performance under different pitch conditions (spin- vs pace-friendly) |

## Methodology

1. **Data collection & cleaning** — consolidating multi-season franchise and player statistics from public sources into a structured dataset (Python, pandas).
2. **DEA modelling** — computing efficiency scores per franchise per season, treating auction spend across departments as inputs and league performance metrics as outputs.
3. **Home-conditions analysis** — comparing efficiency scores against how well each franchise's squad composition matches its home pitch profile.
4. **Visualization & reporting** — efficiency frontiers, franchise rankings, and trend analysis over the 2018–2025 period.

## Tools

- **Python** (pandas, numpy) — data cleaning and preparation
- **DEA modelling** — Python-based linear programming approach
- **Power BI / matplotlib** — visualization of efficiency scores and trends

## Repository Structure

```
├── data/           # Raw and cleaned datasets
├── notebooks/      # Exploratory analysis and DEA modelling notebooks
├── scripts/        # Data collection and cleaning scripts
├── outputs/        # Charts, efficiency tables, final results
└── README.md
```

## Status & Roadmap

- [x] Topic defined, ethics approval obtained (secondary data only — no participant risk)
- [ ] Data collection from public sources
- [ ] Data cleaning and consolidation
- [ ] DEA model implementation
- [ ] Home-conditions comparative analysis
- [ ] Final write-up and visualization

## Ethics

This project relies exclusively on publicly available secondary data and does not involve human participants, so it carries minimal ethical risk. Ethical approval was granted by Aston Business School under the standard secondary-data pathway.

## Contact

Ujjwal Aditya Birenji — ujjwaladitya.b@gmail.com
