# Pandas Fundamentals

This repository documents my learning process while studying pandas.

## Notebooks

### Creating a DataFrame from Python Objects
- Created from Python dictionary
- Random seed used for reproducibility
- Explored dtypes and DataFrame structure
- Demonstrates how multiple Series share a common index

### Project: Sensor Temperature Analysis
Dataset

Temperature data exported from a CSV (Sensor: av8_temp).

- ~405k rows
- Time range: Oct 2024 – Aug 2025
- Unit: °C

Data Preparation

1. Converted timestamp to datetime
2. Set timestamp as index
3. Renamed columns for clarity
4. Removed invalid extreme values (2 outliers at 382.35°C)
5. Ensured chronological sorting

Notes on Data Quality

- Original dataset contained redundant column (value_num)
- Two extreme anomalies likely caused by sensor malfunction
- Cleaned dataset constrained to realistic temperature range (-40°C to 50°C)