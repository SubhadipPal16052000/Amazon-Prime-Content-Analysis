# 📊 Amazon Prime Video Content Performance & Strategy Analysis

![](amazon_cln.jpg)

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue)
![Pandas](https://img.shields.io/badge/Pandas-EDA-yellow)
![NumPy](https://img.shields.io/badge/NumPy-Analytics-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-purple)
![Status](https://img.shields.io/badge/Project-Business%20Case%20Study-success)

---

## 🏢 Introduction

Amazon Prime Video is a global subscription-based streaming platform operating in the highly competitive OTT (Over-the-Top) digital entertainment industry. The platform continuously expands its content library to attract and retain subscribers across different regions.

With increasing competition from platforms like Netflix and Disney+, data-driven decision-making has become critical for optimizing content acquisition and improving user engagement.

This project analyzes Amazon Prime’s TV shows and movies dataset to uncover insights related to:

- Content distribution
- Ratings performance
- Growth trends
- Regional production patterns
- Popularity behavior

The analysis supports strategic planning and data-backed content investment decisions.

---

## 🎯 Business Context

Amazon Prime Video is a global streaming platform operating in the digital entertainment industry.

This project focuses on analyzing Amazon Prime’s TV Shows and Movies dataset to help the business understand:

- Content performance
- Genre trends
- Audience engagement metrics
- Growth trajectory

---

## ❓ Problem Statement

Amazon Prime requires structured insights into its content library to optimize investment decisions and improve audience engagement.

Currently, there is limited clarity on:

- Which genres dominate the platform
- How content has evolved over time
- What factors influence content popularity
- Regional contribution to the content library

Without proper analysis, content strategy decisions may lack data-backed validation.

---

## 📌 Business Questions Answered

### 🔎 What decision does the business need help with?

- Which genres should receive higher investment?
- Which regions are contributing most effectively?
- What type of content drives popularity?
- How should future content acquisition be prioritized?

### 📉 What is not currently understood?

- Relationship between ratings and popularity
- Growth pattern trends over years
- Distribution of content types
- Concentration of high-performing titles

The business needs to understand content performance patterns in order to improve strategic content investment and user engagement.

---

## 📂 Data Sourcing

### 📊 Data Source
Publicly available streaming dataset (JustWatch / Kaggle platform)

### 📁 Files Used
- `titles.csv`
- `credits.csv`

### 🕒 Time Period
Content released across multiple decades up to recent years.

### 📈 Number of Records
- 9,000+ unique content titles
- 124,000+ cast and crew records

### 🔑 Key Fields
- Title
- Show Type (Movie / TV Show)
- Release Year
- Genres
- Production Countries
- IMDb Score
- IMDb Votes
- TMDB Popularity
- Runtime
- Seasons

---

## 🧹 Data Transformation & Cleaning

The raw dataset was cleaned and transformed through:

- Removing duplicate entries
- Handling missing values in IMDb score, TMDB score, and runtime
- Standardizing genre and country fields
- Converting release year into numeric format
- Separating Movies and TV Shows for comparison
- Detecting outliers in ratings and runtime
- Creating derived features (decade grouping, rating categories)

These steps ensured analytical accuracy and consistency.

---

## 🏗 Data Modelling (Python-Based Analytical Model)

Since the project was conducted using Python (Pandas), a structured analytical model was implemented.

### Data Structure:

- **Main Table:** Titles dataset
- **Supporting Table:** Credits dataset
- **Relationship Key:** Title ID

Data aggregation was performed using:

- Genre
- Show Type
- Release Year
- Production Country

KPI-style reporting was simulated using `groupby()` and aggregation functions.

---

## 📊 Analysis & Key Measures

### 📌 Performance Metrics Calculated:

- **Total Titles** = Count of unique content
- **Total Movies** = Count where show_type = Movie
- **Total TV Shows** = Count where show_type = TV Show
- **Average IMDb Score** = Mean of imdb_score
- **Total IMDb Votes** = Sum of imdb_votes
- **High Rated Titles** = Count where imdb_score > 8
- **Average Popularity Score** = Mean of tmdb_popularity

### 🎯 KPIs Focused On:

- Content Volume
- Ratings Performance
- Popularity Trends
- Growth Rate by Year
- Genre Contribution

---

## 📈 Dashboard & Visuals



### Visualizations Included:

- KPI Summary Metrics
- Trend charts (Content growth over time)
- Genre distribution bar charts
- IMDb rating distribution histograms
- Correlation heatmaps
- Scatter plots (IMDb Votes vs Popularity)
- Runtime distribution boxplots

### Users Can:

- View trends across release years
- Compare performance across genres
- Evaluate popularity vs rating alignment

---

## 🔍 Insights & Findings

- 🎬 Movies dominate the platform compared to TV Shows.
- 🎭 Drama is the most common genre, followed by Comedy and Action.
- 📈 Significant content growth occurred after 2015, indicating aggressive expansion strategy.
- ⭐ Majority of titles have IMDb ratings between 6–7.
- 🔥 Strong positive correlation exists between IMDb votes and popularity scores.
- 🌎 USA contributes the highest share of content production.

---

## 💡 Strategic Recommendations

- Increase investment in high-engagement genres such as Drama and Action.
- Develop more high-rated premium content (IMDb > 8).
- Expand regional content diversity to reduce geographic concentration.
- Promote high-vote titles to maximize engagement.
- Leverage rating-popularity correlation to improve recommendation algorithms.

---

## 🏁 Conclusion

This project delivered a data-driven view of Amazon Prime’s content ecosystem, enabling better decision-making around:

- Content acquisition strategy
- Genre prioritization
- Regional investment planning
- Engagement optimization

### Achievements:

- Identified content growth patterns
- Analyzed rating-performance relationships
- Evaluated genre dominance
- Extracted business-relevant insights

### Future Scope:

- Predictive modeling for content success
- User behavior analytics
- Competitor benchmarking (Netflix, Disney+)
- Recommendation engine enhancement

---

## 🛠 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

---

## 👤 Author

**Subhadip Pal**  
Data Analyst | Python | SQL | Data Visualization  

---

⭐ If you found this analysis valuable, consider starring the repository!
