# RollerCoaster-EDA-Project


## Overview
This project performs comprehensive Exploratory Data Analysis on a dataset of roller coasters. The objective is to understand the distribution, relationships, and patterns across various attributes such as location, manufacturer, year of introduction, physical dimensions, and performance characteristics.

The analysis was conducted in a Jupyter Notebook environment and includes data cleaning, preprocessing, visualizations, and summary statistics.

## Dataset Description
The dataset contains the following key columns:
- Coaster_Name
- Location
- Status
- Manufacturer
- Year_Introduced
- latitude
- longitude
- Type_Main
- Opening_Date
- Speed_mph
- Height_ft
- Inversions
- Gforce

These attributes allow for a wide range of analytical questions including manufacturer analysis, geospatial patterns, temporal trends, and correlations across physical features.

## Key Analyses Included
- Handling missing values and data cleaning
- Descriptive statistics
- Correlation analysis using heatmaps
- Location based segmentation
- Distribution plots for continuous features
- Grouped aggregations such as top manufacturers by location

## Example Analytical Questions Addressed
- Which manufacturers dominate specific locations
- How speed, height, inversions, and gforce relate to each other
- Trends over the years in coaster introductions
- Distribution of coaster types
- Identification of outliers and extreme values

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Use
1. Open the EDA.ipynb notebook.
2. Run the cells sequentially to reproduce the analysis.
3. Modify or extend the analysis as per your requirements.

## Project Structure
- EDA.ipynb: Notebook containing the complete analysis
- coaster_db.csv: Dataset downloaded from kaggle
- README.md: Project documentation

## Future Enhancements
- Build predictive models for coaster performance
- Add geospatial visualizations for better location insights
- Automate reporting with dashboards

