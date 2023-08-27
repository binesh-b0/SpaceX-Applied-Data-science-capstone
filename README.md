# SpaceX Capstone Project

This repository contains all relevant materials, code, and data for the SpaceX Capstone Project which focuses on analyzing the launch success rate, and predicting future successes using machine learning algorithms.

## Table of Contents
- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Quickstart](#quickstart)
- [Key Findings](#key-findings)
- [Future Work](#future-work)
- [Contributors](#contributors)
- [License](#license)

## Introduction

The primary goal of this project is to derive actionable insights from SpaceX launch data, visualize the success rates, and build predictive models to estimate the outcome of future launches.

## Data Sources

All data utilized in this project is sourced from the official [SpaceX API](https://github.com/r-spacex/SpaceX-API).

## Technologies Used
- Python
- Jupyter Notebook
- SQL
- Machine Learning Libraries (Scikit-learn, etc.)
- Data Visualization Libraries (Matplotlib, Seaborn, etc.)

## Quickstart

1. Clone the repository:
    ```bash
    git clone https://github.com/binesh-b0/SpaceX-Applied-Data-science-capstone.git
    ```
    
2. Navigate to the directory:
    ```bash
    cd spacex-capstone
    ```

3. Open Jupyter Notebook to view the analysis:
    ```bash
    jupyter notebook
    ```

4. Explore datasets, notebooks, and visualizations!

## Key Findings

- Launch success rates have seen a consistent improvement from 2013 to 2020.
- Certain orbits, specifically ES-L1, GEO, HEO, SSO, and VLEO, showcase higher success rates.
- The KSC LC-39A launch site stands out with the most successful launches.
- Decision Tree Classifier emerged as the most effective model for this dataset, with an accuracy of approximately 88.89% on test data.

## Future Work

- Explore ensemble machine learning techniques to further improve prediction accuracy.
- Incorporate additional data sources, possibly including weather data, to provide a more holistic prediction model.
- Develop a real-time dashboard for on-the-fly predictions during launch preparations.


## License

This project is licensed under the MIT License. See [LICENSE.md](LICENSE.md) for more details.

