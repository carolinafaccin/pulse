![Status](https://img.shields.io/badge/status-planned-yellow.svg)

**PULSE** - _Public Urban Line Systems Explorer_ - is a project for exploring, processing, and analyzing public transit data using the **GTFS (General Transit Feed Specification)** format.

The project provides an open-source framework to transform static GTFS data into meaningful insights and visualizations, with an initial focus on the public transport network of Porto Alegre, Brazil. The goal is to make public transit data more accessible for urban researchers, planners, and the public.

## Overview

- **Data Processing**: The tool is designed to read and process GTFS static data from a compressed file.

- **Key Insights**: It generates valuable information about the transit network, such as the total number of stops, route lengths, and distribution of stops across different city neighborhoods.

- **Interactive Maps**: A key feature is the ability to create interactive maps that visualize transit stops and the geometry of bus lines using the **Folium** library.

- **Replicable Framework**: The project is designed to be easily adapted for any city that provides data in the GTFS standard format.


## Repository structure

```
PULSE/
├── data/
│   ├── raw/                 # Raw GTFS data (e.g., .zip files)
│   └── processed/           # Processed data (e.g., .csv, .geojson)
├── src/
│   ├── gtfs_parser.py       # Source code for data processing and analysis
│   └── visualization.py     # Source code for creating maps and charts
├── notebooks/               # Jupyter notebooks for exploratory analysis and visualization
├── docs/                    # Documentation and literature
├── .gitignore               # List of files to be ignored by Git
└── README.md                # This file
```
