# Movies-ETL
## Analysis Overview
The purpose of this repository is to perform an ETL on data originating from JSON wikipedia and CSV formats. We will extract the data (pull the data from the sources), Transform the data by using regular expressions to parse data and to transform text into numbers, clean the data, eliminate unnecessary columns, merge dataframes, and load the data into PostgreSQL. ETL is used to move information between databases to improve performance and comprehension. The goal is to create a pipeline that automates as much data processing as it can.

## Results
By looking at the png files located within this repository, we can see that both our movies and ratings tables have loaded successfully into our PostgreSQL Database and the final runtime to load the data was 2944.77 seconds, or 49 minutes.
