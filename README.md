# World_Weather_Analysis

# Purpose

To analyze data depending on latitude and longitude for consumers.

# How was the analysis performed

  Numpy was imported and used to create a set of random latitudes and longitudes. These were then zipped into pairs to get coordinate points. Citipy was imported to get the nearst city to our random coordinates. Next was acquiring the cities weather description through openweather API and putting those in a dataframe.

  I promted the user to enter the minimum and maximum temperature they would like for thier trip then created a Dataframe from it. The next step was getting hotel data through GoogleAPIs if we found a hotel if was added to the list if not the hotel was skipped. The hotels were added to the current dataframe and any city that didn't have a hotel was removed. Markers were added to show each city on the map.
  
  The last step was our Vacation Itinerary where our userers selected a country and in that country 3 locations they would like to visit. Markers and directions were added so the user could see a physical map of where they were touring. They could've selected driving, cycling or walking depending on how close the cities were.
  
# New Things Learned
 - Creating Heatmaps
 - Creating Markers
 - Using iterrows to iterate through data
 - Importing a config file in multiple ways
 - Try and except
 - Setting up a base URL
 - Making a request from a URL
 - JSON
 - Numpy & Zip




