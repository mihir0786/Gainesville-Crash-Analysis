# Data

The analysis uses the **Traffic Crashes** dataset published through Gainesville's Open Data Portal and maintained by the Gainesville Police Department.

Source page: https://data.cityofgainesville.org/Public-Safety/Traffic-Crashes/iecn-3sxx/about_data

## Expected local file

1. Download/export the dataset as CSV.
2. Use the project snapshot filename: `Traffic_Crashes_20260412.csv`.
3. Place the file in this `data/` directory.
4. Run `notebooks/gainesville_traffic_crash_analysis.ipynb`.

The repository excludes the CSV by default through `.gitignore` because the portal is the authoritative source and the dataset may be updated. For exact replication, use the April 12, 2026 snapshot analyzed in the notebook.
