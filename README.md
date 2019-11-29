# Automatic OpenWeatherMap data to Google Sheet
**Automatically download weather data to a Google Sheet from OpenWeatherMap**



Method (Video tutorial at https://youtu.be/764HGIfrMpA):
- Create a new Google Sheet
- Copy the entire code from the OpenWeatherMap.js file in this repository (https://github.com/DrKrisChan/SheetOpenWeatherMap/blob/master/OpenWeatherMap.js)
- On the top toolbar, under Tools, click Script editor
- Replace the entire script with the copied script
- Edit as instructed in the script (copied below):

  1) Setup an OpenWeatherMap account and find the API key
  2) EDIT THE LATITUDE (lat=), LONGITUDE (lon=) AND API KEY (APPID). Note that it can take a bit of time for your API key to become active (normally less than an hour).
  3) We recommend renaming 1) the function (change Tawarano to your location), 2) "code.gs" (left toolbar), and 3) your project title (top toolbar). Save the Google script file.
  4) Under "Publish" on the top bar, click "Deploy as web app". Click Update and allow permissions via Google
  5) navigate to script.google.com. For the specific web app, click ... then Triggers. Click "create a new trigger", "Event source" -> "Time Driven" and set an appropriate interval (10-15 minutes is generally good).


**Created by Dr Kristofer Chan - Department of Geography, King's College London**

*Disclaimer: We are in no way affiliated with OpenWeatherMap or Google. Please abide by their terms of use and consider supporting them.
