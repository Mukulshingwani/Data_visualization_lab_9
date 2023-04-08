# Data visualization Lab 9
## Weather Dashboard
The Weather Dashboard provides an overview of weather conditions in the specified city with an option to toggle all temperature units to Celsius and back to Fahrenheit. Sidebar provides access to random major cities and their current weather. Along with that it displays in background an image related to the searched location.

<img src="https://user-images.githubusercontent.com/25181517/189715289-df3ee512-6eca-463f-a0f4-c10d94a06b2f.png" width="20px">  <img src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" width="20px"> <img src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" width="20px">  <img src="https://user-images.githubusercontent.com/25181517/183898054-b3d693d4-dafb-4808-a509-bab54cf5de34.png" width="20px"> <img src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png" width="20px">

## Key Features

- Implemented light/dark mode toggling feature to switch between light and dark themes.
- Dynamically changed the landscape background image based on the searched location.
- Used CSS variables to store and apply the light and dark mode styles across the application.
- Stored the user's last searched city and theme preference in the localStorage for persistence.
- Created reusable functions for making API calls related to search, geolocation, and sidebar panel city selection.
- Sidebar panel displays a random set of 5 major cities each time the page is loaded.
- Utilized forEach() and for loops to dynamically display icons, city information, and daily forecast.
- Provided support for both Celsius and Fahrenheit units.
- Added a custom message based on the type of weather condition (under "Feels Like" value).
- Employed Axios library to make HTTP requests to API.
- Implemented a custom loading spinner animation as a placeholder image for weather icons (to avoid displaying a broken image tag before the weather icon loads).

## Light Mode
<img src="/assets/light_mode.jpeg" style="max-width: 100%;">

## Dark Mode
<img src="/assets/dark_mode.jpeg" style="max-width: 100%;">
