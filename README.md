# Data Science Project – Electricity and Solar Power Analysis in Germany

## Overview

This project analyzes electricity generation and photovoltaic energy in Germany using historical electricity, weather, and solar installation data.

The analysis explores the development and distribution of different electricity generation sources, investigates the relationship between weather conditions and solar power generation, examines the expansion of photovoltaic installations in Germany, and uses machine learning to predict solar electricity generation.

This project was originally developed as part of the **Data Engineering & Data Analytics** module at Ostbayerische Technische Hochschule Amberg-Weiden (OTH Amberg-Weiden).

## Main Topics

The project covers several areas of data analysis:

- Data cleaning and preprocessing
- Exploratory data analysis
- Analysis of electricity generation by energy source
- Temporal analysis of electricity generation
- Solar and wind power analysis
- Analysis of photovoltaic expansion in Germany
- Investigation of weather influences on solar power generation
- Geographic visualization of photovoltaic installations
- Machine learning for solar power prediction

## Data

The project combines multiple data sources, including:

- Electricity generation data from 2018–2023
- Photovoltaic installation data
- Weather and solar radiation data
- Geographic data for the German federal states

The photovoltaic installation data is distributed across multiple CSV files and processed as part of the analysis.

## Data Analysis

The exploratory analysis investigates questions such as:

- How electricity generation developed over time
- How different energy sources contribute to electricity production
- How solar and wind generation vary over time
- Which periods have particularly high or low electricity generation
- How solar generation relates to weather conditions
- How photovoltaic capacity has expanded in Germany

Several statistical and graphical methods are used to explore and visualize these relationships.

## Photovoltaic Analysis

A major part of the project focuses on photovoltaic energy.

The analysis examines photovoltaic installations in Germany and their development over time. Geographic information is also used to visualize the distribution of solar installations.

An interactive solar power map is included in:

```text
solar_power_map.html
```

## Solar Power Prediction

The project includes a machine learning model for predicting daily solar electricity generation.

A linear regression model is trained using features such as:

- Installed photovoltaic capacity
- Daylight duration
- Sunshine duration
- Solar radiation

Historical data is divided into training and testing data to evaluate the model before it is used to generate solar power predictions.

## Technologies

The project was developed in Python using Jupyter Notebook.

Main technologies and libraries include:

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Plotly
- Folium
- Scikit-learn

## Project Files

- `Lyoteva_Maria_Stanchev_Tsvetan.ipynb` – complete data analysis and machine learning notebook
- `DataScience_Project_Report.pdf` – exported version of the notebook for convenient viewing
- `solar_power_map.html` – interactive geographic visualization
- CSV files – electricity, photovoltaic, and model datasets
- `bundeslaender_geo.json` – geographic data used for visualization

## Viewing the Project

For a quick overview of the complete analysis, open:

```text
DataScience_Project_Report.html
```

The HTML contains the notebook's analysis, visualizations, results, and code without requiring Jupyter Notebook to be installed.

The interactive geographic visualization can be viewed by opening:

```text
solar_power_map.html
```

in a web browser.

## Running the Notebook

### Requirements

Python and Jupyter Notebook are required to execute the analysis.

Install Jupyter if necessary:

```bash
pip install jupyter
```

Additional Python libraries used by the project may also need to be installed.

### Run

Open a terminal in the project directory and start Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
Lyoteva_Maria_Stanchev_Tsvetan.ipynb
```

and execute the cells from top to bottom.

The supplied data files should remain in the project directory so that the notebook can access them.
