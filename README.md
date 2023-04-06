# NYC-Bike-Data-ETL

Performed ETL (Extract, Transform, Load) on the NYC bike data API, 
extracting data three times a day with more than three hours of gap between each extraction.

Transformed the extracted data by creating a new variable called "activity"
which was calculated by finding the difference in the number of bikes docked at subsequent times.

Loaded the transformed data into TinyDB, a lightweight document-oriented database, to perform further analysis on the merged data.

Used the activity variable to identify the high and low activity stations, gaining insights into the usage patterns of NYC bike stations.

By analyzing the activity data, identified which bike stations had the highest and lowest usage, 
allowing you to draw conclusions about the overall demand for bike share services in different areas of the city.


Overall, the project demonstrates your ability to perform ETL, transform data, load it into a database system, 
and analyze it using a combination of statistical analysis methods and data visualization techniques.
