IMDb Movies Dataset Analysis
This project explores and analyzes the IMDb dataset to uncover insights about movie production trends, genres, durations, and data quality. The SQL scripts dive deep into multiple tables such as movie, genre, ratings, and more.
Key Analysis Segments
- Data Overview: Count of records in each table; identification of columns with null values.
- Release Trends: Year-wise and month-wise release trends highlighting peak production periods.
- Country Production Focus: Focused analysis on India and USA's contributions in 2019.
- Genre Insights: Unique genres, most popular genre (Drama), and number of single-genre films.
- Duration Stats: Average movie durations by genre—Action movies top the chart.
- Genre Rankings: Using SQL ranking to position Thriller among all genres by production count.
 Data Sources
This analysis utilizes the following tables from the imdb schema:
- movie
- genre
- ratings
- names
- director_mapping
- role_mapping
Technologies Used
- SQL (MySQL dialect)
- DBMS tools (like MySQL Workbench or pgAdmin)
How to Run
Make sure you’ve imported the IMDb dataset into your SQL database. Then execute the queries from the script to analyze each insight segment.
