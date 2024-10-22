# Turkey-Geographical-Data

This repository contains three CSV files with data on provinces, districts, and neighborhoods/villages in Turkey. These datasets can be used for geographic analysis or software projects requiring access to Turkey's local-level data.

## Usage Guide

1. **Download Datasets**: You can download the relevant CSV files from this repository.
2. **Open CSV Files**: You can open the CSV files with your preferred data analysis or programming tool.
3. **Explore the Datasets**: Review the column headers and contents in the CSV files to perform your desired analysis.
4. **Perform Data Analysis or Project Development**: You can use the datasets for geographic analysis or integrate local data of Turkey into your software projects.

## Example Code

Examples of loading the datasets and performing basic analysis using Python are as follows:

```python
import pandas as pd

# Load CSV files
il_data = pd.read_csv("iller.csv")
ilce_data = pd.read_csv("ilceler.csv")
mahalle_koy_data = pd.read_csv("mahalleler_ve_koyler.csv")

# Explore the datasets
print("Province Dataset Example:")
print(il_data.head())

print("District Dataset Example:")
print(ilce_data.head())

print("Neighborhood/Village Dataset Example:")
print(mahalle_koy_data.head())
