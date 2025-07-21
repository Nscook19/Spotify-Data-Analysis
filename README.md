# Spotify Data Analysis

Exploratory data science project analyzing my personal Spotify streaming history to uncover listening trends, genre preferences, and temporal patterns using Python and Jupyter notebooks.

🔗 **Project Overview**  
This project applies data analysis and visualization techniques on raw Spotify streaming JSON data enriched with artist genre metadata fetched via the Spotify API. It delivers insights into my music habits over hours, months, seasons, and years, revealing nuanced listening behaviors and genre transitions.

---

## 🧠 Data Science & Analysis Highlights

Through comprehensive data wrangling, cleaning, and enrichment across three Jupyter notebooks, I demonstrated key data science skills:

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

## 🛠️ Tech Stack

| Layer           | Tools Used                       |
|-----------------|----------------------------------|
| Data Collection | Python, Spotipy, Spotify Web API |
| Data Processing | Pandas, NumPy                    |
| Visualization   | Matplotlib, Seaborn, Plotly      |
| Analysis & EDA  | Jupyter Notebooks                |
| Data Storage    | JSON                             |

---

## ⚙️ Key Features

- Robust Spotify streaming history ingestion with JSON file parsing  
- Artist genre lookup leveraging Spotify API with caching for performance  
- Time-based feature extraction to analyze listening habits by hour, month, season, and year  
- Advanced visualization including heatmaps, line plots, bar charts, Sankey diagrams, and stacked area plots  
- Detailed logging and error handling throughout data enrichment processes  

---

## 🧰 Technical Achievements

- Integrated third-party API data to enrich and contextualize raw streaming data  
- Built a reproducible, modular data pipeline for cleaning, transformation, and analysis  
- Created interactive and static visualizations that reveal complex behavioral patterns  
- Applied data storytelling to communicate insights clearly and effectively  

---

## 📚 What I Learned

- Real-world API integration challenges and best practices for data enrichment  
- Advanced time series feature engineering in user behavior data  
- Effective visualization techniques to capture multidimensional data trends  
- Translating complex data into actionable insights for behavioral understanding  
- The importance of clean data and robust error handling in data science workflows  
