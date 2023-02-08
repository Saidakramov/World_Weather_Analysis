# World_Weather_Analysis

## Overview of the analysis:

  - The purpose of this analysis was to retrieve weather data, create a custom travel destinations map, to create a travel itinerary map.

## Results:
  
  - Retrieve a weather data:
   
    - We created weather data by generating random 2,000 latitude and longitude sets, which resulted in 737 cities. Then, we saved 737 cities in the DataFrame in a CSV file. 
   
  - Create a customer travel destinations map:
  
    - During this part of our analysis, we retrieved our saved data using APIs and located nearby Hotels. Afterward, we created a new DataFrame with a list of hotels and a map showing all the hotel locations.

<img width="977" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/89552059/182049799-a7718e81-82ef-4ff1-a680-efd22807a9c6.png">

  - Create a travel itinerary map:
  
    - Finally, we used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, we created a marker layer map with a pop-up marker for each city on the itinerary.
    
 
 <img width="1440" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/89552059/182049906-a6d7e99f-cc93-4de3-8960-ee023954c072.png">

<img width="975" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/89552059/182049916-082e368c-10c9-4abf-a206-5db2e5aa2669.png">
