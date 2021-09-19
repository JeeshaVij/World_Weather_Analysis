# Overview of the Project

PlanMyTrip is a travel technology company. They’ve recommended a few changes to take the app to the next level. 
Specifically, they recommend adding the weather description to the weather data.

# Steps to be included in the application

- Retrieve weather data: a set of 2,000 random latitudes and longitudes was gnerarted, retrieved the nearest city, and performed an API call
  with the OpenWeatherMap. Through using APIs, the current weather description for each city was retrieved.

- Create a Customer Travel Destinations Map: customer weather preferences were retrieved to identify potential travel destinations and nearby 
  hotels. These destinations were then shown on a marker layer map with pop-up markers.

- Create a travel itinerary map: using the Google Directions API a travel itinerary that shows the route between four cities chosen from the 
  customer’s possible travel destinations was created. Then a marker layer map with a pop-up marker for each city on the itinerary was created.
