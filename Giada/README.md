# My Work in the Berlin Data Explorer Project

This folder contains my contributions to the Berlin Data Explorer project, where I analyze rental and purchase price data for different neighborhoods in Berlin. The notebook uses machine learning techniques, including linear regression, for price prediction.

## Notebooks

- `Rent_Purchase_Prices_Berlin`: This notebook contains an analysis of rental and purchase prices in Berlin, focusing on various neighborhoods. The notebook includes:
  1. Data Preparation: Cleaning and organizing rental and purchase price data from CSV files.
  2. Visualizations: Creating various visualizations to analyze the distribution of prices and compare different neighborhoods.
  3. Machine Learning: Implementing linear regression for price prediction and performing evaluations of the model's performance (including residual analysis and metrics).
  
  The notebook also explores how different neighborhoods are affected by rent and purchase price trends over time.

## Instructions

### Setup
1. Install python
2. Navigate to this folder in your terminal, create a virtual environment and activate it
```bash
python -m venv venv
. venv/bin/activate
```
3. Install the python requirements
```bash
pip install -r requirements.txt
```

### Usage
1. If not activated yet, activate the venv in your terminal
``` bash
. venv/bin/activate
```
2. Open the project in Jupyter lab
``` bash
jupyter lab
```
3. Open the notebook `Rent_Purchase_Prices_Berlin`

4. Select `Run`->`Run all cells`

## Data Files

The following data files are used in this project:

- `data/BerlinPrices/AHS-Index-RENT-PLZ-2024-long.csv`: Contains rental price data for all Germany by Postal Codes.
- `data/BerlinPrices/AHS-Index-PURCH-PLZ-2024-long.csv`: Contains purchase price data for all Germany by Postal Codes.
- `data/plz.geojson`: GeoJSON file containing postal code boundaries for Berlin.
- `data/bezirksgrenzen.geojson`: GeoJSON file containing neighborhood boundaries for Berlin.
- `data/Postcode_BerlinDistricts.csv`: A CSV mapping postal codes to Berlin neighborhoods.
