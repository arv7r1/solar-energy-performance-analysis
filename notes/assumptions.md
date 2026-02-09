# Assumptions

This project uses the following assumptions to simulate a real-world solar energy performance analysis workflow. These assumptions are documented to ensure transparency, auditability, and reproducibility of results.

## Data Assumptions
- Actual energy production data represents metered site-level telemetry collected at hourly intervals.
- Expected energy production represents modeled or forecasted generation based on irradiance and system design parameters.
- Expected energy is treated as a contractual or baseline reference and is not altered during analysis.

## Performance Metrics
- Performance Ratio (PR) is calculated as:
  PR = Actual Energy (kWh) / Expected Energy (kWh)
- A PR threshold of **0.85** is used to classify underperformance, allowing for normal environmental and operational variability while identifying material deviations.

## Validation Rules
- AC power values greater than DC power values are treated as data quality issues rather than physical equipment faults.
- Zero energy production during periods with non-zero expected energy is flagged for further investigation.
- Negative performance deviation values indicate underperformance relative to expectations.

## Financial Modeling
- A notional energy rate of **$50 per MWh** is used to estimate financial impact due to underperformance.
- Financial impact calculations are illustrative and intended to demonstrate analytical methodology rather than represent actual contract values.

## Scope Limitations
- Weather normalization beyond irradiance is not included.
- Capacity factor and availability metrics are represented via proxy indicators rather than full engineering models.
- The analysis is designed for portfolio-level operational insight rather than real-time system control.

These assumptions reflect common practices in operational energy analytics and are appropriate for exploratory and decision-support analysis.
