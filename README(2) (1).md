# Netflix Exploratory Data Analysis

## 1. Problem Statement

The objective of this project is to analyze Netflix movies and TV shows and identify trends and patterns in content types, release years, countries, ratings, genres, and Netflix content additions.

The project transforms the raw Netflix dataset into meaningful insights using Python, Pandas, and Matplotlib.

## 2. Dataset Details

- **Dataset:** Netflix Titles Dataset
- **Records:** 8,807
- **Columns:** 12
- **Time period:** 1925–2021 based on content release year
- **Main data fields:** Show ID, Type, Title, Director, Cast, Country, Date Added, Release Year, Rating, Duration, Genre, and Description.

## 3. Approach

### Data Cleaning and Validation

- Loaded the dataset using Python/Pandas.
- Checked dataset structure and data types.
- Identified missing values.
- Converted `date_added` into datetime format.
- Identified and corrected three incorrect duration values stored in the `rating` column.
- Separated multiple country entries for individual country analysis.
- Separated multiple genre entries for individual genre analysis.

### Exploratory Data Analysis

Analyzed:

- Movies vs TV Shows
- Netflix titles added by year
- Top countries
- Content ratings
- Top genres
- Content release-year trends
- TV show seasons
- Correlation between release year and number of seasons

### Data Visualization

Created visualizations for:

- Movies vs TV Shows
- Netflix titles added by year
- Top 10 countries
- Top 10 ratings
- Top 10 genres
- Netflix titles by release year
- Release year vs number of TV seasons

### Correlation Analysis

Calculated the correlation between TV show `release_year` and `seasons`.

The correlation value was **-0.090**, indicating a very weak negative linear relationship.

### Project Workflow

```text
Raw Netflix CSV
      ↓
Python / Pandas
      ↓
Data Cleaning & Validation
      ↓
Exploratory Data Analysis
      ↓
Feature Extraction
      ↓
Trend & Correlation Analysis
      ↓
Matplotlib Visualizations
      ↓
Key Insights
```

## 4. Results

- **Total Titles:** 8,807
- **Movies:** 6,131
- **TV Shows:** 2,676
- **Movies Percentage:** approximately 69.6%
- **TV Shows Percentage:** approximately 30.4%
- **Highest Titles Added in a Year:** 2019 — 1,999
- **Highest Release Year in the analyzed recent-year range:** 2018 — 1,147 titles
- **Top Country:** United States — 3,689 titles
- **Second Top Country:** India — 1,046 titles
- **Most Common Rating:** TV-MA — 3,207 titles
- **Most Common Genre/Category:** International Movies — 2,752 titles
- **Release Year vs Seasons Correlation:** -0.090

## Technologies Used

- Python
- Pandas
- Matplotlib
- Google Colab
