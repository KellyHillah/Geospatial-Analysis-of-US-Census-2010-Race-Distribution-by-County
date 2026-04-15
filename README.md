# Geospatial Analysis of US Census Data (2010)

Exploration of US county-level demographic data using the IPUMS NHGIS API, 
with static and interactive visualizations built in both Python and R.

## What this project does

- Pulls county shapefiles and race population data via the IPUMS NHGIS API
- Cleans and merges spatial and tabular data (Continental US only)
- Produces static choropleth maps and racial composition bar charts
- Builds an interactive Leaflet map with county-level tooltips and popups
- Includes a full Dash web dashboard with state/county filters

## Tools used

**Python:** geopandas, pandas, matplotlib, plotly, folium, dash  
**R:** sf, tidyverse, leaflet, ggplot2, ipumsr

## How to run

1. Register at https://www.nhgis.org/ to get a free API key
2. Clone the repo and install dependencies (see requirements below)
3. Add your API key where indicated in the script
4. Run `python main.py` or open the R script in RStudio

## Output

- Static bar charts of racial composition by county
- Choropleth map of total population across all US counties
- `interactive_county_map.html` — clickable Leaflet map
