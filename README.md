# Weather-Forecast

##I created some components:
  - Databasemanager is to store the JSON string of hourly forecast date
  - WeatherAdapter to map the data to views that being defined in XML file
    + this one has DownloadImage which is an Asynctask performs downloading the icon by URL parsed.
  - MainActivity connects every components so that the app works.
