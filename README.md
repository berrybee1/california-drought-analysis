# California Drought Analysis (1895-2024)
A deep dive into 130 years of climate data to identify long-term drought trends.
## Data Source
The data used in this project is provided by the **NOAA National Centers for Environmental Information (NCEI)**.
* **Dataset:** nClimDiv (National Climate Divisional Dataset)
* **Parameter:** PDSI (Palmer Drought Severity Index)
* **Link:** [NOAA NCEI Climate Monitoring](https://www.ncei.noaa.gov/pub/data/cirs/climdiv/climdiv-pdsidv-v1.0.0-20251204)
##  Key Insights
* **Aridification Trend:** California has seen a systemic drop of **0.25 points** (overall shift) in the PDSI index over the last 60 years.
* **Seasonal Vulnerability:** July is the most affected month, showing the sharpest decline in moisture levels compared to the historical baseline.

##  Project Workflow
1. **ETL:** Automated parsing of fixed-width data from NOAA NCEI servers.
2. **Analysis:** Comparative study of two epochs (1895-1960 vs. 1961-2024).
3. **Visualization:** Time-series with rolling averages, comparative seasonal bar charts, and record-high drought annotations.

##  How to Use
Run the `California_drought.ipynb` in Google Colab or locally.
