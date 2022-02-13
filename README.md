# Travel Itinerary with Weather Data for users using APIÕs

## Overview of Project
This project combines the use the of pandas, matplotlib, & Google Maps APIÕs in order to support a travel app obtain necessary data elements to recommend hotel preferences to users. 

### Creating a database of cities
Prior to obtaining data elements from Open Weather & Google Map APIÕs, a database of cities was created using the citypy module. A randomized list of longitudes & latitudes within a specific range created the list of cities used as part of this project. 

### Retrieving Weather data in identified cities
Following creation of a city database, weather data elements were then extracted from Open Weather for these cities via an API. These various data elements such as weather description, temperature, cloudiness, wind speed, etc. were retried for each of the cities. With necessary weather data of each of these cities, this data frame needed to be condensed based on user preferences. 

### Locating nearest hotels and plotting
Once a user identified their weather preferences, this resulted in a condensed list of cities in which a Google Maps API was used to determine the nearest hotel to that preferred city. In addition, using a Google Map figure, these hotels were plotted onto a visual map to aide in identifying ideal hotels.


