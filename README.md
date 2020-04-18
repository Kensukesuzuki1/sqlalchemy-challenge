# sqlalchemy-challenge
Using SQLAlchemy and Python to explore Hawaii's climate database.

# Analysis 

Precipitation Analysis

-In the on one year period between 2016-08-23 and 2017-08-23, there were 4 periods when Percipitation exceeded 1 inch. Avoid going to Hawaii during these periods! 

Station Analysis

-The most active station is USC00519281

# App (App.py)
Available Routes

/api/v1.0/precipitation

-List of precipitations from last year:

/api/v1.0/stations

-JSON list of stations from the dataset:

/api/v1.0/tobs

-JSON list of Temperature Observations (tobs) for the previous year:

/api/v1.0/<start> 

-JSON list of tmin, tmax, tavg for the dates greater than or equal to the date provided:

Replace <start> with a date in Year-Month-Day(like: 2017-01-07) format.
  
/api/v1.0/<start>/<end>
-JSON list of tmin, tmax, tavg for the dates in range of start date and end date inclusive:

Replace <start> and <end> with a date in Year-Month-Day(like: 2017-01-07) format.inclusive.

