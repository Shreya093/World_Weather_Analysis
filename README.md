# World_Weather_Analysis

## Project Overview

The purpose of this project is to perform weather analysis on various cities for PlanMyTrip company. After doing the required changes the beta testers want to implement few new changes to the app. They recommend to add current weather description to the weather data along with other required metrics for the travellers to identify potential travel destinations and nearby hotels.
The **Open Weather Map API** will be used to pull the weather information and weather description will be added to the markers that pop up after clicking on a pin. The beta testers also wanted that customers should be able to pick their minimum and maximum temperatures for a trip. From there, four cities were chosen to create an itinerary map with pins and markers. The **Google Maps API** will be used to plot the different travel destinations with a hotel at each location.

## Process

### Retrieve the Weather Data

An API call was established with OpenWeatherMap to pull the weather information for different cities around the world. This list helps the travellers to choose their travel destination as per their requirements.

<img width="767" alt="Screen Shot 2021-09-29 at 4 11 59 PM" src="https://user-images.githubusercontent.com/88418201/135360921-e6dd7cae-ed16-4f01-bc45-33918962c86e.png">

### Create a Customer Travel Destinations Map

After receiving the preferred minimum and maximum weather preferences from the customer, we use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers.

<img width="988" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/88418201/135361305-bde122c9-3e10-4814-899a-5ed39ce8d63e.png">

### Create a Travel Itinerary Map

Using the Google Directions API  a travel itinerary was created that shows the route between four cities chosen from the customer’s possible travel destinations. 

<img width="988" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/88418201/135361537-c5101b7f-a302-4557-aab0-42e8471417a8.png">

A marker layer map was created with a pop-up marker for each city with respective hotel on the itinerary.

<img width="988" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/88418201/135361571-72e44c96-b88d-47d2-a347-ca1dc86c3f1f.png">


