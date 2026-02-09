**# Solar Energy Performance & Financial Impact Analysis (Excel)**

**## Overview**

This project analyzes large-scale solar and energy storage production data to identify underperforming sites, validate data quality, and quantify financial impact due to energy shortfalls. 
The analysis is designed to mirror real-world operational analytics workflows used in energy operations teams.

**## Objectives**

- Validate solar production data across multiple sites
- Distinguish data quality issues from true equipment underperformance
- Calculate performance metrics such as Performance Ratio (PR)
- Reconcile actual energy production against expected generation
- Quantify financial impact due to underperformance
- Summarize results at a portfolio level using Excel pivot tables and charts


**## Tools Used**

- Microsoft Excel (advanced formulas, pivot tables, charts)
- Structured tables and GETPIVOTDATA
- Conditional logic for validation checks


**## Data Description**

- **Actual Data**: Hourly site-level solar production metrics (AC power, DC power, energy, battery SOC)
- **Expected Data**: Modeled or forecasted expected energy generation per site and timestamp


**## Key Validation Checks**

- AC vs DC power consistency checks
- Zero-energy detection
- Missing and anomalous data identification
- Underperformance classification using Performance Ratio thresholds


**## Analysis Workflow**

1. Cleaned and structured raw actual and expected datasets
2. Applied validation rules to flag data quality issues
3. Calculated Performance Ratio (PR) and performance deviation
4. Classified records as outperforming or underperforming
5. Calculated financial impact from energy shortfalls
6. Built pivot-table summaries to analyze site-level and portfolio-level performance
7. Created charts to visualize financial impact by site



**## Key Outputs**

- Site-level performance summaries
- Underperformance frequency analysis
- Financial impact per site
- Executive-ready charts for decision support



**## Sample Insights**

- All analyzed sites showed periods of underperformance
- Certain sites contributed disproportionately to portfolio-level financial losses
- Pivot-based summaries enabled rapid identification of priority sites for corrective action

**## Folder Structure**

data/ - Raw and processed datasets
excel/ - Excel analysis files
output/ - Charts and summary outputs
scripts/ - (Optional) Python scripts for future automation
notes/ - Documentation and assumptions

## Future Enhancements

- Automate validation using Python
- Integrate weather-adjusted expected generation
- Build a dashboard for real-time monitoring

## Author

Aravind





