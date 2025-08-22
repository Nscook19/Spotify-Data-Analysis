# Spotify Data Analysis

Exploratory data science project analyzing my personal Spotify streaming history to uncover listening trends, genre preferences, and temporal patterns using Python, SQL, and Jupyter notebooks.

**Project Overview**  
This project applies data analysis and visualization techniques on raw Spotify streaming JSON data enriched with artist genre metadata fetched via the Spotify API. It delivers insights into my music habits over hours, months, seasons, and years, revealing nuanced listening behaviors, genre transitions, and patterns best uncovered through SQL-based relational analysis.

---

## Data Science & Analysis Highlights

Through comprehensive data wrangling, cleaning, enrichment, and relational querying across four Jupyter notebooks, I demonstrated key data science skills:

- **Data Collection & API Integration**  
  - Automated genre enrichment for thousands of unique artists using Spotipy and the Spotify Web API  
  - Implemented caching and error handling for robust, efficient metadata retrieval  

- **Data Wrangling & Feature Engineering**  
  - Extracted temporal features (hour, month, season, year) from timestamped listening data  
  - Mapped artists to genres, filtering unknowns to maintain data quality  
  - Engineered features for transitions between genres for sequence analysis  

- **Exploratory Data Analysis & Visualization**  
  - Created heatmaps to show genre popularity by hour of day  
  - Trended listening habits monthly and seasonally using line and clustered bar charts  
  - Used Sankey diagrams to visualize common genre transitions in back-to-back plays  
  - Produced stacked area charts tracking genre distribution evolution over multiple years  

- **Data Storytelling & Interpretation**  
  - Derived meaningful interpretations connecting seasonal trends to user behavior  
  - Identified genre dominance patterns and shifts over time  
  - Explored genre transition dynamics revealing listening flow and preferences  

---

## SQL-Based Analysis (New)

A dedicated notebook focuses on using SQL (via SQLite) to uncover deeper relational patterns in listening behavior. This layer of analysis supplements Python-based EDA with structured querying for optimized aggregation, filtering, and time-based insights.

**Key Achievements from the SQL Notebook:**

- **Relational Data Modeling & Storage**  
  - Cleaned and loaded over 100,000 rows of enriched listening history into a normalized SQLite database  
  - Ensured genre consistency by excluding unknown mappings for higher data integrity  

- **SQL-Powered Trend Discovery**  
  - Identified top listening days with daily total minutes played using SQL aggregation  
  - Analyzed hourly listening patterns to pinpoint peak engagement times  
  - Tracked monthly genre popularity shifts with time-windowed grouping  
  - Used SQL window functions to compute previous and current genres for transition analysis  

- **Visualization & Insight Generation**  
  - Visualized listening trends by hour of day, showing clear engagement spikes in the evening  
  - Revealed rap as the dominant genre over multiple years through a stacked area chart  
  - Surfaced the most common genre-to-genre transitions, with *Rap to Rap* dominating followed by *Rage to Rage* and *Melodic Rap to Melodic Rap*  
  - Demonstrated SQL's strength in tracking sequential listening behavior and comparing intra- vs inter-genre habits  

This notebook showcases the power of structured queries to surface insights that are difficult or inefficient to compute with raw Python alone.

---

## Tech Stack

| Layer           | Tools Used                              |
|-----------------|-----------------------------------------|
| Data Collection | Python, Spotipy, Spotify Web API        |
| Data Processing | Pandas, NumPy, SQLite                   |
| Visualization   | Matplotlib, Seaborn, Plotly             |
| Analysis & EDA  | Jupyter Notebooks, SQL                  |
| Data Storage    | JSON, SQLite                            |

---

## Key Features

- Robust Spotify streaming history ingestion with JSON file parsing  
- Artist genre lookup leveraging Spotify API with caching for performance  
- Time-based feature extraction to analyze listening habits by hour, month, season, and year  
- SQL-backed analysis for advanced temporal and transition-based insights  
- Rich visualizations including heatmaps, line plots, bar charts, Sankey diagrams, and stacked area plots  
- Detailed logging and error handling throughout data enrichment and analysis  

---

## Technical Achievements

- Integrated third-party API data to enrich and contextualize raw streaming data  
- Built a reproducible, modular data pipeline for cleaning, transformation, and analysis  
- Leveraged SQL to efficiently query time-series and relational data  
- Created interactive and static visualizations that reveal complex behavioral patterns  
- Applied data storytelling to communicate insights clearly and effectively  

---

## What I Learned

- Real-world API integration challenges and best practices for data enrichment  
- Advanced time series feature engineering in user behavior data  
- Effective SQL querying techniques to extract layered insights  
- Visualization strategies that highlight multidimensional data trends  
- Translating complex data into actionable insights for behavioral understanding  
- The importance of clean data and robust error handling in data science workflows  
