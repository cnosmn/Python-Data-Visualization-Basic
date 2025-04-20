# Data Visualization with Python

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11-red.svg)](https://seaborn.pydata.org/)
[![Pandas](https://img.shields.io/badge/Pandas-1.3-green.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4-orange.svg)](https://matplotlib.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains a collection of Python scripts demonstrating various data visualization techniques using popular libraries such as Seaborn, Pandas, and Matplotlib. The examples cover a wide range of visualization methods applied to different datasets, making it an excellent resource for learning data visualization in Python.

## Table of Contents

- [Data Visualization with Python](#data-visualization-with-python)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Datasets](#datasets)
  - [Visualization Techniques](#visualization-techniques)
    - [Basic Visualizations](#basic-visualizations)
    - [Statistical Visualizations](#statistical-visualizations)
    - [Categorical Visualizations](#categorical-visualizations)
    - [Relationship Visualizations](#relationship-visualizations)
    - [Time Series Visualizations](#time-series-visualizations)
  - [Installation](#installation)
  - [Usage](#usage)
  - [File Descriptions](#file-descriptions)
  - [Dependencies](#dependencies)

## Introduction

Data visualization is a critical component of data analysis, helping to uncover patterns, trends, and outliers in data. This repository serves as a practical guide to creating effective visualizations in Python, with step-by-step examples using real-world datasets.

## Datasets

The examples use several built-in datasets from the Seaborn library:

1. **Tips Dataset** - Contains information about restaurant bills and tips
2. **Flights Dataset** - Monthly airline passenger numbers from 1949 to 1960
3. **Titanic Dataset** - Passenger data from the Titanic disaster
4. **Financial Data** - Stock price data for Apple Inc. (AAPL) from Yahoo Finance

## Visualization Techniques

This repository demonstrates the following visualization techniques:

### Basic Visualizations
- Bar plots
- Line plots
- Scatter plots
- Histograms
- Density plots (KDE)

### Statistical Visualizations
- Box plots
- Violin plots
- Pair plots
- Distribution plots

### Categorical Visualizations
- Categorical scatter plots
- Grouped bar plots
- Count plots

### Relationship Visualizations
- Correlation plots
- Linear regression plots
- Faceted plots

### Time Series Visualizations
- Time series line plots
- Pivot tables with heatmaps

## Installation

1. Clone this repository
```bash
git clone "this project"
cd data-visualization-python
```

2. Install required packages
```bash
pip install pandas numpy seaborn matplotlib pandas-datareader
```

## Usage

You can run the example scripts in Jupyter Notebook or any Python IDE:

```bash
jupyter notebook
```

Or execute the scripts directly:

```bash
python data_visualization_v1.py  # or data_visualization_v2
```

## File Descriptions

- **data_visualization_v1.py** - Contains examples using flights and Titanic datasets, focusing on:
  - Basic data exploration
  - Categorical plots
  - Distribution plots
  - Violin and box plots

- **data_visualization_v2.py** - Contains examples using tips dataset and financial data, focusing on:
  - Relationship plots
  - Time series analysis
  - Advanced customization
  - Financial data visualization

## Dependencies

- Python 3.x
- Pandas: For data manipulation and analysis
- NumPy: For numerical operations
- Seaborn: For statistical data visualization
- Matplotlib: For creating static visualizations
- pandas-datareader: For accessing financial data from online sources

---

Feel free to contribute to this repository by adding more visualization examples or improving the existing ones. If you have any questions or suggestions, please open an issue or submit a pull request.