# Data visualization Lab 9
## Weather Dashboard
The Weather Dashboard provides an overview of weather conditions in the specified city with an option to toggle all temperature units to Celsius and back to Fahrenheit. Sidebar provides access to random major cities and their current weather. Along with that it displays in background an image related to the searched location.

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
