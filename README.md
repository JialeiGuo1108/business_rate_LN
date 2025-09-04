# Impact of Rates Revaluations Bracket Creep on Business Life Expectancy in London’s Four Boroughs
This repository contains the complete data analysis and code supporting the dissertation "Impact of Rates Revaluations Bracket Creep on Business Life Expectancy in London's Four Boroughs" (CASA0010, UCL Bartlett Faculty).

## Research Overview
This research analyzes bracket creep as a systematic feature exhibiting 25-30% distortions around the £15,000 threshold across four London boroughs: City of London, Camden, Hackney, and Westminster. The study reveals that mid-sized enterprises face greatest vulnerability, with significant borough-level disparities—Hackney shows the most pronounced distortions while City of London demonstrates enhanced resilience.
## Methodology
- Dynamic clustering analysis for bracket creep identification
- Survival modeling with temporal validation (2017-2023)
- Panel data regression incorporating firm size, sector, and geographical factors
- Machine learning prediction framework using Random Forest and Logistic Regression

## Findings
- Threshold Effects: Bracket creep exacerbates vulnerability rather than causing immediate business exits
- Sectoral Patterns: Offices pursue appeals while retail firms rely on operational downsizing
- Temporal Dynamics: Threshold enterprise resilience declined from 2017 to 2023 due to macroeconomic pressures
- Predictive Outlook: 2026 modeling indicates elevated survival odds overall, with concentrated risks in specific borough-sector clusters

## Repository Structure
- `data_source/`: Contains all raw datasets used in the analysis
- `essay_picture/`: Contains all figures and visualizations for academic paper
- `1_descriptive_analysis.ipynb`: Exploratory data analysis and descriptive statistics
- `2_Panel_Regression_Predictive_Model.ipynb`: Panel data regression models and business survival prediction framework
