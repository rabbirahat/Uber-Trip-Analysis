# Uber Trip Analysis

This repository contains a Jupyter Notebook that performs an analysis of Uber trip data. The analysis includes loading the dataset, performing various data manipulations, and generating summaries and visualizations.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Summary](#analysis-summary)
- [Contributing](#contributing)

## Introduction

The goal of this project is to analyze Uber trip data to gain insights into trip patterns, peak hours, and other relevant metrics. The analysis includes identifying the date with the most completed trips, the hour with the most requests, and other key metrics.

## Dataset

The dataset used for this analysis is 'dataset_1.csv', which contains Uber trip data.


## Installation

To run the notebook, you need to have Python and the following libraries installed:

- pandas
- matplotlib
- seaborn

You can install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn
```

## Usage

To run the analysis, open the Uber_Trip_Analysis.ipynb notebook in Jupyter Notebook or JupyterLab and execute the cells. The notebook will load the dataset, perform the analysis, and generate the summaries and visualizations.

## Analysis Summary
- The analysis generates several key summaries, including:
- Date with most completed trips
- Highest number of completed trips in 24 hours
- Hour with most requests
- Percentage of zeroes on weekends
- Weighted average ratio of completed trips per driver
- Busiest 8-hour period
- Correlation between requests and unique drivers
- 72-hour period with the highest ratio of zeroes to eyeballs
- The best hour to add 5 drivers
- Total days
- The best end time

The results are saved to a summary text file named analysis_summary.txt.


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

