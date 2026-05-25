# Netflix Dataset - Exploratory Data Analysis (EDA)

## Problem Statement

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Netflix Dataset to identify useful trends, patterns, and insights from the data.

The analysis focuses on:
- Understanding the distribution of Movies and TV Shows
- Identifying top countries producing Netflix content
- Finding the most popular genres
- Analyzing content growth over the years
- Understanding content ratings and trends
- Performing correlation analysis on numerical data

The project also includes visualizations to better understand the dataset.

---

# Dataset Details

- **Dataset Name:** Netflix Titles Dataset
- **File Name:** `netflix_titles.csv`
- **Source:** Netflix Dataset
- **Format:** CSV File

## Dataset Columns

| Column Name | Description |
|---|---|
| show_id | Unique ID of content |
| type | Movie or TV Show |
| title | Name of content |
| director | Director name |
| cast | Actors/Actresses |
| country | Country of origin |
| date_added | Date added on Netflix |
| release_year | Release year |
| rating | Content rating |
| duration | Duration of movie/show |
| listed_in | Genre/category |
| description | Short description |

---

# Approach

The following steps were performed during the EDA process:

## 1. Import Libraries
Used:
- Pandas
- NumPy
- Matplotlib

## 2. Load Dataset
Loaded the CSV dataset using Pandas.

## 3. Data Understanding
- Checked dataset shape
- Viewed column names
- Checked missing values
- Displayed summary statistics

## 4. Handle Missing Values
- Filled missing categorical values
- Removed rows with important missing values

## 5. Exploratory Data Analysis
Performed:
- Movies vs TV Shows analysis
- Top countries analysis
- Genre analysis
- Ratings distribution analysis
- Content added over years analysis

## 6. Correlation Analysis
Generated correlation matrix and heatmap for numerical columns.

## 7. Data Visualization
Created graphs using Matplotlib:
- Pie Chart
- Bar Charts
- Line Graph
- Heatmap

---

# Results

The following insights were identified from the dataset:

- Netflix contains more Movies than TV Shows.
- The United States has the highest amount of Netflix content.
- Content growth increased rapidly after 2015.
- Drama and International genres are highly popular.
- TV-MA is one of the most common ratings.
- Netflix continuously increased content production over time.
- Numerical columns showed low correlation.

---

# Visualizations Included

- Movies vs TV Shows Pie Chart
- Top Countries Bar Chart
- Content Added Over Years Line Graph
- Top Genres Bar Chart
- Ratings Distribution Graph
- Correlation Heatmap

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
