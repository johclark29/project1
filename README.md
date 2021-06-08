## Increasing Ridership at Lyft Bay Wheels

This project is an analysis ridership of Lyft Bay Wheels and the purpose is to ascertain if there are opportunities to increase ridership throgh deals, including those through the mobile application. The project involves the analysis of three different publicly available datasets through the Google Cloud platform. After analyzing the data, a number of conclusions and recommendations are presented for management consideration. 

Key opportunities that were identified included opportunities for additional stations, specific targeted marketing campaigns and further information, if collected moving forward, would enable improved recommendations on further such activities. 

### Project Description

Lyft Bay Wheels offers bicycles at 78 locations in San Francisco, San Jose, Mountain View, Redwood City, and Palo Alto. The company provides a number of different potential offers and marketing information to potential riders, such as: 

* Single Ride 
* Monthly Membership
* Annual Membership
* Bike Share for All
* Access Pass
* Corporate Membership

The goal of this analysis is identify opportunities to increase ridership by conducting an observational data analysis of information provided through three datasets available on the Google BigQuery Cloud Platform: 

* bigquery-public-data.san_francisco.bikeshare_trips - provides information on trips taken such as duration of ride, start and end data/time of ride, start and end station IDs, bike number and subscriber type
* bigquery-public-data.san_francisco.bikeshare_stations - provides information on the bicycle stations including the station ID, name of station, longitude, latitude and dockcount
* bigquery-public-data.san_francisco.bikeshare_status - provides status at the station including bikes and docks available at a particular station at a particular time

The process for conducting this project first involved asking a several important business questions relating to ridership, stations and station status. After that, a number of SQL queries and visualizions were conducted using Google Cloud tools including BigQuery and Google's Jupyter Notebooks service. 

### GIT Table of Contents

Three different files are provided as the output from this project. 

* project1.pynb - Jupyter Notebooks file containing report content, SQL queries and Python code
* Lyft Bay Wheels Report.PDF - PDF report adapted from Jupyter Notebooks
* README.md - This document describing the project and content of this GIT repository
