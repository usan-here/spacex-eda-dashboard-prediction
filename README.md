# SpaceX EDA Dashboard & Prediction

This repository contains a comprehensive set of Jupyter notebooks, datasets, and Python scripts for performing exploratory data analysis (EDA), interactive dashboard creation, and predictive analysis on SpaceX launch data.

The project covers the following key areas:

- Data Collection from APIs and Web Scraping
- Data Wrangling and Cleaning
- Exploratory Data Analysis (EDA) using SQL and Python visualizations
- Launch Site Mapping with Folium
- Interactive Dashboard creation with Plotly Dash
- Machine Learning Predictive Analysis for launch success

-------

## Repository Structure
```
Spacex-EDA-Dashboard-Prediction/
│
├── notebooks/
│ ├── 1.1-jupyter-labs-spacex-data-collection-api.ipynb
│ ├── 1.2-jupyter-labs-webscraping.ipynb
│ ├── 02-labs-jupyter-spacex-Data-wrangling.ipynb
│ ├── 3.1-jupyter-labs-eda-sql-coursera_sqllite.ipynb
│ ├── 3.2-jupyter_labs_eda_dataviz_v2.ipynb
│ ├── 4-lab_jupyter_launch_site_location_v2.ipynb
│ └── 5-SpaceX_Machine_Learning_Prediction_Part_5_v1.ipynb
│
├── data/
│ └── spacex_launch_dash.csv
│
├── python/
│ └── spacex-dash-app.py
│
├── requirements.txt
├── README.md
└── LICENSE
```

-------------


## Installation

### 1. Clone this repository:

```bash
git clone https://github.com/<your-username>/Spacex-EDA-Dashboard-Prediction.git
```

### 2. Navigate into the project directory:

```bash
cd Spacex-EDA-Dashboard-Prediction
```

### 3. Install required dependencies:

```bash
pip install -r requirements.txt
```

--------------


## Usage

**1. Jupyter Notebooks:** Open notebooks in the notebooks/ folder to explore EDA and ML experiments.

**2. Dash Dashboard:** Run python python/app.py and visit http://127.0.0.1:8050/ to explore the interactive dashboard.

**3. Folium Map:** Run python python/folium_map.py to generate interactive maps.

**4. Predictive Models:** Use python python/ml_models.py to train and test ML models on SpaceX launch data.


-----------------


## Contributing

Feel free to fork this repository and submit pull requests to improve notebooks, dashboards, or analyses.

### Author

### Umme Sanjeda


----------------------


## License

This project is licensed under the Apache License 2.0. See the LICENSE file for details.






