# Module 6 Challenge - World Weather Analysis

## Overview
The goal is to create vacation recommnedations based on users preferences. The challenge will start by generating 2,000 random coordinates. With those coordinates we'll use citipy to gather their nearest cities. Next a DataFrame is created with City, Country, Lat, Lng, Max Temp, Humidity, Cloudiness, Wind Speed, and Current Description. That DataFrame is exported for use in the next step.

From that random cities file, the cities will be filtered based on user inputs of minimum temperature and maximum temperature. A new DataFrame will be created by those cities that fit the users preferences and Hotel Names will be added to that DataFrame. The hotels will then be plotted on a world map.

The final portion of the challenge will take 4 cities and create an itinerary for travel to those four cities, starting and stopping in the same city. Maps with travel directions and hotel info will complete the challenge.
