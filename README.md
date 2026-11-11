# SpaceX Falcon 9 Launch Analysis & Interactive Dashboard

**IBM Data Science Professional Certificate — Capstone Project**

An end-to-end data science project exploring SpaceX Falcon 9 launch outcomes, examining factors associated with first-stage landing success and developing an interactive dashboard for exploring launch records.

## Project Overview

This project analyzes historical SpaceX launch data to investigate relationships between launch characteristics and first-stage landing outcomes.

The work combines data collection, data preparation, exploratory data analysis, SQL queries, machine learning, geospatial visualization, and interactive dashboard development.

The project includes a Python-based Dash application that allows users to explore launch records by launch site, booster version, and payload mass.

## Technologies & Tools

- **Programming:** Python, SQL
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Plotly, Plotly Express, Folium
- **Interactive Applications:** Plotly Dash
- **Machine Learning:** Scikit-learn
- **Data Collection:** APIs and web scraping
- **Development:** Jupyter Notebooks

## Project Components

### 1. Data Collection and Preparation

Collected and prepared SpaceX launch data using API requests and web scraping. Applied data cleaning and transformation techniques to prepare datasets for analysis.

### 2. Exploratory Data Analysis

Investigated launch outcomes and relationships between variables, including:

- Launch site and launch success
- Payload mass and landing outcomes
- Booster version and launch performance
- Orbit type and mission characteristics
- Launch trends over time

### 3. SQL Analysis

Used SQL queries to examine launch records, compare launch characteristics, and explore patterns in historical mission data.

### 4. Interactive Data Visualization

Developed an interactive dashboard using Plotly Dash.

Dashboard functionality includes:

- Filtering launch records by launch site
- Comparing successful and unsuccessful launch outcomes
- Exploring outcomes by booster version
- Filtering launches by payload mass using a range slider
- Visualizing payload mass against launch outcomes

### 5. Machine Learning

Developed and evaluated classification models to predict first-stage landing outcomes.

Models explored included:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- K-Nearest Neighbors

Used model evaluation and hyperparameter tuning with scikit-learn.

### 6. Geospatial Analysis

Used Folium to visualize launch locations and explore geographic relationships between launch sites and mission outcomes.

## Repository Contents

The repository includes Python application files, Jupyter notebooks, SQL analysis, data collection exercises, machine-learning experiments, and geospatial visualizations.

The interactive dashboard is implemented in `spacex_dash_app_formatted.py`.

## Project Background

Completed as part of the IBM Data Science Professional Certificate capstone program.

This project provided practical experience applying data science techniques to an aerospace dataset, from data acquisition and analysis through machine learning and interactive application development.
