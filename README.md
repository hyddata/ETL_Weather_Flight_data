# ETL_Weather_Flight_data
A step-by-step journey of extracting data from 3 different sources, cleaning it with Pandas, storing it in MySQL, and visualizing beautiful forecasts — all in pure Python.
Below should be written in MySQL

/***************************
Setting up the environment
***************************/

-- Drop the database if it already exists
-- DROP DATABASE IF EXISTS weather_flight_data ;

-- Create the database
CREATE DATABASE weather_flight_data;

-- Use the database
USE weather_flight_data;



/***************************
Creating the first table
***************************/




SELECT * FROM weather_condition;
select * from airports;
select * from arrivals;
