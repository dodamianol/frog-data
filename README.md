# FrogID5 Data Analysis

This project was completed as an individual university assignment for a **Data Science** module. The project focused on working with a large real-world dataset, preparing the data for analysis, and visualizing the results.

## Dataset

The analysis uses data from **FrogID5**, a dataset documenting frog sightings across Australia (Raw data is not included in this repository due to its size).

The analysis focuses on relevant variables such as ([view metadata analysis](data/frogID5_data_info.md)):

* Species
* Date and time of observation
* Location (latitude and longitude)
* Australian state/territory
* Observer
* Coordinate uncertainty and geoprivacy

**Dataset metadata:**
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7040047/

## Data Preparation

The data was cleaned and prepared using **Python and pandas** [`view data preparation`](notebooks/Preparing_FrogID5_data.ipynb). This included:

* Selecting relevant variables from the original dataset
* Adding vernacular (common) species names
* Adding full Australian state and territory names
* Extracting year, month, and day from observation dates

## Analysis & Visualisation

The final analysis explores:

* Monthly frog occurrence patterns in Australia
* The most frequently recorded frog species
* Monthly occurrence patterns by state/territory
* The geographical distribution of frog observations across Australia

The complete analysis and visualisations can be found in:

[`notebooks/all_files_in_one.ipynb`](notebooks/all_files_in_one.ipynb)

## Technologies

**Python · Pandas · Matplotlib · Folium · Jupyter Notebook**
