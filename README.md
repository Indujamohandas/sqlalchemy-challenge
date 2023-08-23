# sqlalchemy-challenge
In this Challenge I haved used Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, I have  used SQLAlchemy ORM queries, Pandas, and Matplotlib and completed the following steps:
I have used the provided files (climate_starter.ipynb and hawaii.sqlite) to complete your climate analysis and data exploration.
Used the SQLAlchemy create_engine() function to connect to your SQLite database.
Used the SQLAlchemy automap_base() function to reflect your tables into classes, and then save references to the classes named station and measurement.
Precipitation Analysis:
Found the most recent date in the dataset.
Using that date, get the previous 12 months of precipitation data by querying the previous 12 months of data.
Select only the "date" and "prcp" values.Loaded the query results into a Pandas DataFrame. Explicitly set the column names.
Sorted the DataFrame values by "date".
Plot the results by using the DataFrame plot method.
Station Analysis:
Designed a query to calculate the total number of stations in the dataset.
Designed a query to find the most-active stations (that is, the stations that have the most rows). To do so, complete the following steps:
List the stations and observation counts in descending order.
Designed a query that calculates the lowest, highest, and average temperatures that filters on the most-active station id found in the previous query.
Design a query to get the previous 12 months of temperature observation (TOBS) data and plot the results using the dataframe plot method.
