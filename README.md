# Executive Summary

## What the Project Does
This project conducts an exploratory data analysis of Jersey City Citi Bike trips from February and September 2025 to understand how weather and seasonality affect bikeshare usage and its environmental impact.
By merging Citi Bike trip data with daily weather data from the Open-Meteo API, the analysis identifies key relationships between temperature, precipitation, and ridership behavior. It also estimates the CO₂ emissions avoided when bike trips replace car travel.
The notebook uses Python (pandas, seaborn, matplotlib, statsmodels, and folium) to perform descriptive statistics, regression analysis, and spatial mapping, producing visualizations and metrics that quantify bikeshare’s contribution to sustainable urban transport.

## Why the Project Is Useful
Understanding how external conditions influence bikeshare demand helps both operators and policymakers make data-driven decisions.
* **For operators:** The results highlight peak hours, seasonal shifts, and station-level hotspots that inform fleet management, battery swapping, and infrastructure planning.
* **For sustainability analysts and policymakers:** The project provides a transparent, reproducible framework to estimate **emissions avoided** and evaluate the role of active mobility in reducing urban transport emissions.
* **For researchers:** The code demonstrates how to combine publicly available APIs and datasets to build a clean, interpretable analysis pipeline using real-world transportation data.

## How Users Can Get Started
1. Copy or download this repository from GitHub.
2. Open the Jupyter notebook in Google Colab or JupyterLab.
3. Run all cells sequentially to reproduce the full analysis.
   * The notebook automatically loads trip data (from Citi Bike’s public portal) and weather data (from the Open-Meteo API).
   * All results, including plots and the interactive station hotspot map (jc_hotspots.html), will generate automatically.
4. Review the outputs to explore:
   * Trip patterns by user type, bike type, and month
   * Hourly and daily ridership trends
   * CO₂ avoided estimates and their relationship to weather conditions

No additional setup is required beyond installing core Python libraries (`pandas`, `matplotlib`, `seaborn`, `requests`, `statsmodels`, and `folium`).

Would you like me to format this into a complete Markdown file (with code block formatting and headers) ready to upload to your GitHub repo as `README.md`?
