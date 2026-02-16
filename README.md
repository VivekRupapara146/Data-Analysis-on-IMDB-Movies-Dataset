# IMDB Movies Dataset Analysis

## Overview

A comprehensive exploratory data analysis (EDA) of the IMDB movies dataset. This project involves data cleaning, preprocessing, and creating insightful visualizations to uncover trends and patterns in movie data including ratings, revenue, voting patterns, and director performance.

## Project Objective

The goal is to explore and understand the IMDB movies dataset through data cleaning and visualization. By analyzing various aspects of the data—from temporal trends to director performance—we derive meaningful insights that can inform decisions about movie production, marketing, and audience engagement.

## Dataset

**File:** IMDB movies dataset

**G-Drive** <https://drive.google.com/file/d/16dK1kDcbkpCOPlTAf1tekIgz8lE01m0O/view?usp=sharing>

**Key Features:**
- Movie title, release year, genre
- Ratings and voting information
- Revenue data
- Director information
- Duration, cast, and other metadata

## Technologies & Libraries

- **NumPy** – Numerical computations and array operations
- **Pandas** – Data manipulation, cleaning, and analysis
- **Matplotlib** – Static visualizations and plots
- **Seaborn** – Statistical data visualization
- **Excel** – Data inspection and supplementary analysis

## Data Preprocessing

- **Handling Missing Values** – Identified and managed null/missing entries
- **Data Type Conversion** – Ensured appropriate data types for analysis
- **Outlier Detection** – Identified and handled extreme values
- **Data Cleaning** – Removed duplicates and standardized formats
- **Feature Engineering** – Created derived features for deeper insights

## Visualizations & Insights

### 1. **Correlation Between Numeric Features**
Heatmap showing relationships between numerical variables (ratings, revenue, votes, duration, etc.)

### 2. **Voting Per Year**
Time-series analysis of voting trends across years, showing how audience engagement has evolved

### 3. **Revenue Per Year**
Year-wise revenue trends, identifying peak and declining periods in the movie industry

### 4. **Average Rating of Directors**
Director performance analysis showing average ratings and consistency of top directors

### 5. **Movies Per Year**
Production trends showing the number of movies released each year

### 6. **Most and Least Popular Movies**
Identification of highest and lowest-rated movies along with their directors and other metrics

### 7. **Rating Categories**
Distribution of movies across different rating categories (PG, R, PG-13, etc.)

### 8. **Additional Visualizations**
- Genre distribution
- Rating distribution
- Revenue vs. ratings correlation
- Top genres by count and revenue
- Audience engagement metrics

## Key Findings

Through this analysis, we discovered patterns in movie production, audience preferences, and financial performance across different time periods and director portfolios. These insights can guide content creation strategies and market analysis.

## Project Structure

```
├── IMDB_Movies_Analysis.ipynb     # Main analysis notebook
├── IMDB_dataset.csv               # Dataset file
├── README.md                      # This file
└── visualizations/                # Generated plots and charts
    ├── correlation_heatmap.png
    ├── voting_per_year.png
    ├── revenue_per_year.png
    ├── director_ratings.png
    ├── movies_per_year.png
    ├── popular_movies.png
    ├── rating_categories.png
    └── additional_insights.png
```

## How to Use

### Running the Analysis

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook IMDB_Movies_Analysis.ipynb
   ```

2. Execute cells sequentially to:
   - Load and explore the dataset
   - Clean and preprocess the data
   - Generate visualizations
   - Extract insights

### Dataset Access

The IMDB dataset is included in the repository. Ensure the CSV file is in the same directory as the notebook for proper data loading.

## Dependencies

```
numpy
pandas
matplotlib
seaborn
jupyter
```

### Installation

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

## Key Insights Summary

- **Production Trends:** Analysis of how movie production has changed over time
- **Rating Patterns:** Understanding audience preferences and rating distributions
- **Director Performance:** Identifying top-performing directors by average ratings
- **Revenue Trends:** Financial analysis showing profitable years and genres
- **Audience Engagement:** Voting patterns revealing audience interest over time

## Analysis Methodology

1. **Data Exploration** – Initial dataset overview and structure analysis
2. **Data Cleaning** – Handling missing values, duplicates, and inconsistencies
3. **Feature Analysis** – Understanding individual features and their distributions
4. **Relationship Analysis** – Examining correlations between variables
5. **Visualization** – Creating meaningful charts to communicate findings
6. **Interpretation** – Drawing actionable insights from visualizations

## Use Cases

This analysis can be valuable for:
- **Film Production Companies** – Understanding market trends and audience preferences
- **Investors** – Identifying profitable genres and time periods
- **Streaming Platforms** – Content curation and recommendation strategies
- **Marketing Teams** – Timing and positioning movie releases
- **Data Analysts** – Learning EDA best practices

## Future Enhancements

- Sentiment analysis on movie reviews and comments
- Predictive modeling for movie success
- Advanced statistical analysis (hypothesis testing)
- Network analysis of actors and directors
- Time-series forecasting for future trends
- Interactive dashboards using Tableau or Power BI

## Notes

- All visualizations are generated automatically from the notebook
- Data cleaning decisions are documented within the notebook cells
- Results may vary based on dataset version and preprocessing choices

## Contributing

Feel free to enhance this analysis by:
- Adding more visualizations
- Improving data cleaning techniques
- Deriving additional features
- Creating predictive models

## License

This project is open source and available for educational and research purposes.

---

**Created by:** Vivek Girdharbhai Rupapara

**Date:** 2026

**Dataset Source:** IMDB

**Note:** This is an exploratory data analysis project showcasing data preprocessing, cleaning, and visualization techniques using Python libraries.
