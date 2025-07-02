# PV
A dataset for photovoltaic power generation forecasting tasks.
# Photovoltaic Power Forecasting Dataset (Processed & De-identified)

## Data Description

This dataset contains processed and de-identified data used for photovoltaic (PV) power forecasting research.  
All values have been perturbed and normalized to protect data privacy.

### Columns:

| Column Name     | Description                                |
|-----------------|--------------------------------------------|
| time            | Relative day index (starting from 0)       |

| ir10            | Real power                         |
| irradiance      | Normalized irradiance               |
| temperature     | Normalized temperature             |
| wind_speed      | Normalized wind speed                  |
| wind_direction  | Normalized wind diection      |
| humidity        | Normalized humidity          |
| pressure        | Normalized pressure          |
## Data Processing Steps

1. Original time series smoothed to reduce noise  
2. Random multiplicative perturbation applied to numeric features  
3. Secondary smoothing to preserve continuity  
4. Min–Max normalization applied to each column  
5. Sensitive fields removed or anonymized

## Usage Notes

- This dataset is **for academic research only**.  
- Redistribution or commercial use is not permitted.  
- Please cite the original paper if using this dataset in publications.

