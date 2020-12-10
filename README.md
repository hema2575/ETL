## Gun Violence versus Full Moon Project

# Project Team:

    Tom Henry
    Michelle Bannon
    Gisela Gutierrez
    Hema Sankaran

## Project Objective:

# Data Extraction:

    The team extracted data from two data sources that includes the following URLs:

    (1) https://www.kaggle.com/jameslko/gun-violence-data?resource=download/EjFLhcAT9PHva6db5VwE/versions/G8ZiPMsjqRino5GKnNFI/files/gun-violence-data_01-2013_03-2018.csv

    (2) https://www.kaggle.com/lsind18/full-moon-calendar-1900-2050

# Data Transformation:

    The following transformations were performed:

    1. Reformatted dates.
    2. Converted date types to match for the join.
    3. Renamed columns headers. 
    4. Removed columns.
    5. Replaced NaN values with boolean values.
    6. Merged the two data sources into a single data set.
    7. Exported the data to a CSV file.
    8. Created filtered database using specific columns.

# Data Loading:

    Load: the final database, tables/collections, and why this was chosen.
    
    The team loaded both a No-SQL and SQL databases as follows:
    
      Mongo DB: etl_crimedata
      Mongo Collection: violence_data
      Sql DB: CrimeData 
      SQL Collection: violence_data

# Inferences:

    What inferences should we draw?
    1. There is no correlation between gun related crimes and full moons.
    
    
