# IMDb SQL Analysis Project

This project explores a miniature version of the IMDb movie database using SQL within a Jupyter Notebook environment. The goal is to answer analytical questions related to movies, actors, and ratings by querying relational databases and visualizing patterns in movie data.

## Overview

Using a structured dataset with tables on **Titles**, **Names**, **Roles**, and **Ratings**, this project answers key questions including:
- What are the oldest movies in the dataset?
- How has movie production changed over time?
- Who are the most prolific and highest-rated actors?
- How do runtime and user ratings correlate?

## Features

- **SQL Queries**: Complex joins, `GROUP BY`, aggregations, filtering with `WHERE`, and conditional logic with `CASE`
- **Visualizations**: Trends in movie production and viewer ratings using `matplotlib`, `seaborn`, and `plotly`
- **Data Cleaning**: Filtering adult content, converting data types, and binning continuous variables

## Technologies Used

- Jupyter Notebook
- SQL (DuckDB with Jupyter SQL magic)
- Python (Pandas, NumPy, Seaborn, Matplotlib, Plotly)

## File Structure

- `hw07.ipynb`: Main notebook with SQL queries and data visualizations
- `imdbmini.db`: SQLite database containing four key tables: Title, Name, Role, and Rating
- `schemas.txt`: Descriptions of each table and column

## Key Insights

- Identified top 10 actors by number of movies and by average rating
- Showed how movie lengths relate to audience ratings
- Analyzed historical trends in film production volume

## Credits

This project was completed as part of UC Berkeley's Data 100 course.

