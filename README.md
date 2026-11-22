# Plants vs. Zombies 2 – Data Wrangling and Analysis

## Project Overview

This project focuses on cleaning, preprocessing and analysing a dataset containing information about plants from *Plants vs. Zombies 2* using Python.

The objective was to transform the original dataset into a structured and usable format while exploring plant attributes, acquisition methods and other characteristics through data analysis and visualisation.

## Tools and Libraries Used

- **Python** – Data cleaning, preprocessing and analysis
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualisation
- **Jupyter Notebook** – Development and documentation

## Dataset

The project uses a dataset containing information about different plants in Plants vs. Zombies 2.

The repository includes:

- **PvZ2 Plants Analysis.csv:** The original dataset before preprocessing.
- **PvZ2 Cleaned CSV.csv:** The final processed dataset after data cleaning and transformation.

## Data Cleaning and Preprocessing

The preprocessing stage involved several operations to improve data quality and consistency:

- Examining the dataset's structure, dimensions and descriptive statistics.
- Identifying and handling missing values.
- Standardising text entries and categorical labels.
- Correcting inconsistent records.
- Removing a column with insufficient data for meaningful analysis.
- Categorising numerical variables using binning techniques.
- Identifying potential outliers using the Interquartile Range (IQR) method.
- Applying categorical encoding for further analysis.

## Exploratory Data Analysis and Visualisation

Exploratory analysis was conducted to understand patterns and relationships within the dataset.

The project includes visualisations exploring plant characteristics, numerical attributes and potential outliers.

### 1. Recharge Speed Outliers

![Recharge Speed Outliers](Visualizations/Recharge%20Speed%20Outliers.png)

### 2. Recharge Speed Outliers – Trimmed

![Recharge Speed Outliers Trimmed](Visualizations/Recharged%20Speed%20Outliers%20Trimmed.png)

### 3. Relationship Between Acquisition Cost and Damage

![Acquisition Cost and Damage](Visualizations/Relationship%20Between%20Acquisition%20Cost%20and%20Damage.png)

### 4. Sun Cost Outliers

![Sun Cost Outliers](Visualizations/Sun%20Cost%20Outliers.png)

### 5. Sun Cost Outliers – Trimmed

![Sun Cost Outliers Trimmed](Visualizations/Sun%20Cost%20Outliers%20Trimmed.png)

## Repository Structure

```text
pvz2-data-wrangling/
│
├── README.md
├── DWT Assignment.ipynb
├── PvZ2 Cleaned CSV.csv
├── PvZ2 Plants Analysis.csv
│
└── Visualizations/
    ├── Recharge Speed Outliers.png
    ├── Recharged Speed Outliers Trimmed.png
    ├── Relationship Between Acquisition Cost and Damage.png
    ├── Sun Cost Outliers Trimmed.png
    └── Sun Cost Outliers.png
