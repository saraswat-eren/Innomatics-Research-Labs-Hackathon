# Innomatics-Research-Labs-Hackathon

# Property Data Analysis Hackathon

## Overview
This repository contains code and resources for a hackathon project focused on property data analysis. The goal is to clean, analyze, and engineer features from three datasets related to properties listed on a platform. The datasets include property details, photos, and user interactions. The project aims to answer key questions about property characteristics, rent distribution, and relationships between various features.

## Datasets
1. **Property Data 🏠**: Detailed information about properties listed on the platform, including rent, size, location, number of bathrooms, and more.
2. **Property Photos Data 📸**: Information about photos uploaded for each property. The column contains corrupted JSON-like strings which need cleaning to extract the number of photos.
3. **Property Interactions Data 🔄**: Captures user interactions with properties, including timestamps and request dates.

## Tasks Overview 🛠️
- **Task 1: Data Merging**: Merging multiple CSV files containing location-wise property data into a single DataFrame.
- **Task 2: Data Cleaning**: Cleaning the photo URLs column and handling missing values in the dataset.
- **Task 3: Feature Engineering**: Creating new features, such as photo count, price per square foot, and property age normalized by rent.
- **Task 4: Exploratory Data Analysis (EDA)**: Analyzing the data to answer key questions about the properties, such as rent distribution, relationships between features, and outlier detection.
- **Task 5: Predictive Modeling**: Building a simple linear regression model to predict rent based on features like property size, number of bathrooms, and interactions.

## Requirements
The following libraries are required to run the code:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `json`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
