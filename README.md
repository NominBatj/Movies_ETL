# Movies ETL
## Project Overview
In this project as part of the Amazing Prime Hackathon, we are creating an automated data pipeline that will fetch new data from Wikipedia data, Kaggle metadata, and MovieLens rating data. It then performs the appropriate transformations and loads the data into an existing PostgreSQL database.
For this analysis, we divided this project into four deliverables:
### Deliverable 1: write an ETL function to read three data files
- The function takes the Wikipedia JSON, the Kaggle metadata and MovieLens csv files and creates three separate DataFrames.
### Deliverable 2: extract and transform the Wikipedia data
- We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.

### Deliverable 3: extract and transform the Kaggle and rating data
- Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

### Deliverable 4: load the data to a PostgreSQL Movie Database
- Load data with PostgreSQL.
