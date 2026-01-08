## Overview
This project analyzes my personal Spotify listening history to identify trends in music preferences and listening behavior over time. Using Spotify’s official personal data export, Python for data processing and analysis, and Power BI for visualization, I built an interactive dashboard that transforms raw streaming logs into meaningful insights. The project demonstrates an end-to-end data analytics workflow using a real-world dataset.

## Final Dashboard
<img width="1256" height="714" alt="image" src="https://github.com/user-attachments/assets/7a109f72-fe79-4a02-a637-1959d770762d" />

## Objectives
- Clean and transform raw Spotify streaming history data
- Engineer time-based features for analysis
- Perform exploratory data analysis (EDA)
- Build aggregated datasets for BI use
- Create an interactive Power BI dashboard

## Tools
- Python (pandas, json) for data cleaning and analysis
- Power BI for data modeling and visualization
- Git/GitHub for version control and documentation

## Methodology
- Loaded and combined multiple Spotify JSON files
- Cleaned data and created derived features (date, hour, weekday, month, minutes played)
- Filtered out short listens to reduce noise
- Built artist-level and time-based summary tables
- Visualized insights in Power BI

## Dashboard Highlights
- Top artists by total listening time
- Listening trends over time
- Listening behavior by weekday and hour
- High-level KPIs (total plays, total minutes listened)

## Future Improvements
- Add genre and audio feature enrichment from public music databases
- Normalize listening trends across time periods
- Automate updates for future Spotify data exports
