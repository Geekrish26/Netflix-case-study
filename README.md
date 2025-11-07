
# Netflix Case Study: Content Strategy Analysis

## Project Overview
This case study aims to analyze Netflix's catalog of movies and TV shows to identify what type of content the platform should focus on producing or acquiring to strengthen its business across different countries. The analysis explores viewing trends, content types, and genre preferences over time to support strategic decisions for future production.

## Problem Statement
Determine which types or genres of movies and TV shows Netflix should produce more of to enhance growth and engagement across different countries.

## Objective
From the provided dataset, the objective is to analyze:
- Which **type or genre** of content (movie or TV show) is most preferred in different countries.  
- How the preference has evolved over time.  
- Whether audiences prefer **movies** or **TV shows** across various regions.

## Dataset
The dataset used for this analysis contains information about Netflix’s movies and TV shows available globally.  
It includes attributes such as:
- Title  
- Director  
- Cast  
- Country  
- Date added  
- Release year  
- Rating  
- Duration  
- Genre  

Dataset source: "netflix.csv" file given    
Data was cleaned and transformed for exploratory analysis using pandas and NumPy.

## Methodology
1. **Data Cleaning**
   - Handled missing values in categorical and date fields.
   - Extracted additional time-based features such as year, month, and day from the `date_added` column.
   - Standardized text data for country, type, and genre columns.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of movies and TV shows over the years.
   - Analysis of popular genres by country.
   - Yearly trend of new releases.
   - Visualization of preferred content type using bar plots, count plots, and heatmaps.
   - Correlation between country and genre distribution to identify regional preferences.

3. **Visualization**
   - Seaborn and Matplotlib were used for interactive and static visualizations.
   - Visuals include box plots, count plots, histograms, and Q–Q plots to understand data distribution.

## Tools and Libraries Used
- **Python 3**
- **Pandas** for data cleaning and manipulation  
- **NumPy** for numerical computation  
- **Matplotlib** and **Seaborn** for visualization  

## Key Insights
- The number of **TV shows** has increased significantly in recent years compared to movies.
- Certain genres (e.g., Dramas, Documentaries, and International TV series) perform better in specific regions.
- Content diversification across countries plays a major role in Netflix’s global expansion strategy.
- The trend analysis over time indicates growing demand for **region-specific TV shows**.

## How to Run
1. Open the Colab notebook using this link:  
   [Netflix Case Study - Google Colab](https://colab.research.google.com/drive/1T0b1L-niv1O5S895EzP_GnC_5gE1GMxo?usp=sharing)
2. Run each cell sequentially.  
3. The notebook will automatically install dependencies and generate visual outputs.

## Future Work
- Perform audience segmentation using clustering to identify regional content clusters.
- Apply machine learning models to predict the success of upcoming shows based on features such as genre, country, and release year.
- Incorporate sentiment analysis on user reviews (if available) for deeper insights.

## Author
**Krishna Agarwal**  
Data Science Enthusiast | Exploratory Data Analysis | Visualization | Business Insights
