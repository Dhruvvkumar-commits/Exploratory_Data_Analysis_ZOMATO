# Zomato EDA Analysis

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a Zomato
restaurant dataset using Python. The analysis explores restaurant
information, cuisines, ratings, cities, online delivery, table booking,
and relationships between numerical variables.

The notebook contains data loading, dataset inspection, data-quality
checks, and multiple visualizations to understand restaurant trends and
customer ratings.

## Objectives

-   Understand the structure and characteristics of the Zomato dataset.
-   Identify missing values and duplicate records.
-   Explore restaurant distribution across cities and countries.
-   Analyze the most common cuisines.
-   Study restaurant rating distribution.
-   Compare average restaurant ratings across cities.
-   Analyze online delivery and table-booking availability.
-   Examine correlations between numerical variables.
-   Explore the relationship between votes and aggregate ratings.

## Dataset

The analysis uses `zomato_.csv`.

The dataset contains **9,551 rows and 21 columns**. The main fields
include:

-   Restaurant ID
-   Restaurant Name
-   Country Code
-   City
-   Address
-   Locality
-   Locality Verbose
-   Longitude
-   Latitude
-   Cuisines
-   Average Cost for two
-   Currency
-   Has Table booking
-   Has Online delivery
-   Is delivering now
-   Switch to order menu
-   Price range
-   Aggregate rating
-   Rating color
-   Rating text
-   Votes

The notebook shows that the `Cuisines` column contains 9 missing values,
while no duplicate rows were found.

## Analysis Performed

### 1. Data Loading

The dataset is loaded using Pandas with `latin-1` encoding.

### 2. Dataset Inspection

The notebook checks: - Number of rows and columns - Data types - Summary
statistics - Unique country codes

### 3. Data Quality Checks

The analysis checks: - Missing values - Duplicate rows

### 4. Cuisine Analysis

A bar chart is used to identify the **top 10 most common cuisine
combinations** in the dataset.

### 5. Rating Distribution

A histogram with KDE is used to understand how restaurant aggregate
ratings are distributed.

### 6. City-wise Rating Analysis

The project calculates average restaurant ratings by city and visualizes
the top 10 cities by average rating.

### 7. Online Delivery Analysis

A pie chart is used to compare restaurants that provide online delivery
with those that do not.

### 8. Table Booking Analysis

A donut chart is intended to show the proportion of restaurants offering
table booking.

### 9. Correlation Analysis

A correlation heatmap is used to study relationships between numerical
variables such as: - Average Cost for two - Price range - Aggregate
rating - Votes - Geographic coordinates

### 10. Votes vs Rating

A scatter plot examines the relationship between the number of votes and
restaurant aggregate ratings.

## Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## Project Structure

``` text
Zomato-EDA-Analysis/
│
├── Zomato EDA _Analysis(1).ipynb
├── zomato_.csv
├── README.md
└── Requirement.md
```

## How to Run the Project

1.  Install Python or Anaconda.
2.  Install the required Python libraries listed in `Requirement.md`.
3.  Place `zomato_.csv` in the same directory as the notebook.
4.  Open `Zomato EDA _Analysis(1).ipynb` in Jupyter Notebook or
    JupyterLab.
5.  Run the notebook cells sequentially.

## Key Project Takeaways

This project demonstrates practical skills in:

-   Exploratory Data Analysis
-   Data cleaning and validation
-   Missing-value analysis
-   Duplicate detection
-   GroupBy analysis
-   Descriptive statistics
-   Data visualization
-   Correlation analysis
-   Basic business-oriented interpretation of restaurant data

## Important Note

The notebook contains a table-booking visualization cell that references
`tabel_booking` while the variable is created as `table_booking`. If
that cell raises a `NameError`, change `tabel_booking` to
`table_booking`.

The notebook also contains visualization code that uses explicit Seaborn
color/palette settings; these are presentation choices rather than
analytical requirements.

## Author

**Dhruv Kumar**

This project was created as a data analytics / Python EDA project for
portfolio and learning purposes.
