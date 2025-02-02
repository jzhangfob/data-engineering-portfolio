# IGDB Games Data Pipeline 🎮📊
Dive into my journey to build a comprehensive, end-to-end analytics pipeline centered around publicly available video games data. This project leverages modern data engineering and analytics tools to transform raw information into actionable insights.

## What You'll Find Here:

- API ETL Workflows: Extracting, transforming, and loading data from APIs like Twitch/IGDB and other public sources, ensuring clean and structured datasets ready for analysis.
- Data Modeling (In-Progress): Designing efficient schemas to organize complex datasets, including games metadata, player statistics, and ratings.
- Advanced Analytics (In-Progress): Uncovering trends and insights in the video game industry, from release patterns to pricing strategies and player preferences.
- Interactive Dashboards (In-Progress): Visualizing the data in a user-friendly way, with compelling dashboards that tell a story about the gaming landscape.

## Repository Structure and File Details:
- notebooks: Colab notebook with Python scripts used for ETL and data modeling 
  - **Twitch-Data-ETL.ipynb**
    - Extracts and stores raw source data from Twitch/IGDB API's directly into GCP bucket storage
  - **Twitch-Data-Staging-Pipeline.ipynb**
    - Serves as the data modeling layer, loading raw data from storage and transforming it into fact and dimension tables designed for reporting and analytics 
- scripts: Raw .py file copies from the Colab notebooks (TBD)
- schema.jpg: A star schema that breaks raw video game data into structured fact and dimension tables for downstream reporting 

## Technologies Used:

- ETL Tools: Python (Pandas, NumPy), APIs, and orchestration tools.
- Data Warehousing: SQL, BigQuery, and Google Cloud Platform (GCP) for scalable data storage.
- Visualization: TBD (Tableau, Power BI, or custom dashboards built with Python libraries like Plotly)

## 🚧 Under Development 🚧

This portfolio is a work in progress! So far, I've completed the source ETL and data storage processes using GCP. Currently, I’m focused on data modeling and building fact and dimension tables to support robust analytics.

Check back periodically for updates as I continue refining the pipeline and adding exciting new insights. Feel free to leave feedback or share your thoughts—I’d love to hear from you! 🚀

