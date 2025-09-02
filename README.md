# SpaceX Project – IBM Data Science Capstone

## Overview
This project replicates the IBM Data Science Capstone, focusing on **SpaceX Falcon 9 launch success prediction**.  
It combines **data collection, preprocessing, exploratory data analysis, machine learning, and interactive dashboards**.

## Key Features
- **Data Collection**  
  - Web scraping of launch records from Wikipedia with BeautifulSoup.  
  - SpaceX REST API integration to retrieve structured launch data.

- **Exploratory Data Analysis**  
  - Pandas/Matplotlib/Seaborn used for cleaning and visualization.  
  - Interactive geospatial visualizations with **Folium** mapping launch sites and distances.

- **Machine Learning Models**  
  - Logistic Regression, Decision Trees, Support Vector Machines, and K-Nearest Neighbors.  
  - Model comparison with metrics including accuracy, precision, recall, and F1 score.  
  - Final prediction: whether a Falcon 9 first stage will land successfully.

- **Interactive Dashboard**  
  - Built with **Plotly Dash** (`spacex-dash-app.py`).  
  - Provides launch success statistics, payload/booster correlation, and filtering by launch site.

- **Additional Analysis**  
  - `TSLA_Stock_Analysis.ipynb` – exploratory data analysis of Tesla’s stock.  
  - Capstone notebooks documenting each step.

## Tech Stack
- Python, Jupyter Notebooks  
- Pandas, NumPy, Matplotlib, Seaborn  
- BeautifulSoup, Requests  
- Scikit-learn, Plotly, Folium, Dash

