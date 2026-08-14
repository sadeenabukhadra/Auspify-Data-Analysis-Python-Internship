# Netflix Business Insights Report

## Objective
Create a comprehensive business intelligence report from the Netflix dataset by performing end-to-end exploratory data analysis, identifying key content trends, and generating actionable business insights.

## Steps Performed

### 1. Exploratory Data Analysis (EDA)
Loaded and previewed the dataset, checked shape, data types, missing values, duplicates, and unique values, then cleaned and standardized the data (whitespace, date parsing) and reviewed descriptive statistics.

### 2. Key Content Trends & Patterns
Identified trends in content type over time, top genres by content type, country × content type breakdowns, and rating distribution by content type.

### 3. Visual Dashboards
Developed multiple visual dashboards (executive overview and global content dashboards) combining content type, genres, countries, and growth trends into a single view.

### 4. Business Insight Metrics
Quantified genre and country concentration, and compared recent (2015+) vs. overall content mix to surface actionable patterns.

### 5. Final Analytical Report
Synthesized all findings into a written executive summary and business recommendations.

## Key Findings
- Catalog of **8,790 titles**: 69.7% Movies, 30.3% TV Shows — but the TV Show share rises to 35.3% among content released since 2015, showing a shift toward TV Shows.
- Content releases **peaked in 2018 (1,146 titles)**; platform additions peaked in **2019 (2,016)** and have since plateaued.
- Content is geographically concentrated: **United States (~37%)**, **India (~11%)**, **United Kingdom (~7%)**.
- Top genres: **International Movies, Dramas, Comedies** — reflecting a global content strategy.
- Mature ratings (**TV-MA, TV-14**) dominate the catalog.

## Business Recommendations
- Continue investing in TV Shows given their rising share of recent content.
- Expand sourcing beyond the US/India/UK core to support international growth.
- Sustain focus on International and Drama genres as proven top performers.
- Investigate the post-2019 slowdown in content additions.

## Tools Used
Python, Pandas, Matplotlib, Seaborn

## Dataset
`Dataset.csv` — Netflix titles dataset (type, country, release_year, date_added, rating, listed_in)
