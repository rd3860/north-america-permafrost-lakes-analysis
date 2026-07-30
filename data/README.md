# Data

This directory documents the datasets used in the North America Permafrost Lakes Analysis project.

Large raw datasets are not stored directly in this repository because of GitHub file-size limitations and third-party data licensing considerations.

## Dataset Overview

### Part 1: Spatial Distribution Analysis

| File | Description | Repository Status |
|---|---|---|
| `GLRSED_NA.csv` | North American subset of the Global Lake and Reservoir Surface Extent Dataset, containing lake and reservoir locations, surface area, shoreline length, country, and environmental classification attributes. | Not included due to file size |

### Part 2: Time-Series and Weather Analysis

| File | Description | Repository Status |
|---|---|---|
| `permafrost_timeseries.csv` | Monthly surface-area time series for lakes located in mapped permafrost-covered areas. | Not publicly included |
| `lake_timeseries.csv` | Monthly surface-area time series for comparison lakes. | Not publicly included |
| `sample_permafrost.csv` | Attribute and location information for selected permafrost-zone lakes. | Not publicly included |
| `sample_lake.csv` | Attribute and location information for selected comparison lakes. | Not publicly included |
| `weather_permafrost.csv` | Daily weather observations associated with selected lake locations and weather stations. | Not publicly included |

## Data Access

The primary spatial dataset is derived from the Global Lake and Reservoir Surface Extent Dataset (GLRSED).

Users who wish to reproduce the analysis should obtain the original datasets from their authorized sources and place them in:

```text
data/raw/

data/
├── README.md
└── raw/
    ├── GLRSED_NA.csv
    ├── lake_timeseries.csv
    ├── permafrost_timeseries.csv
    ├── sample_lake.csv
    ├── sample_permafrost.csv
    └── weather_permafrost.csv
