# Weather Clock
Desk Clock with a dial for scrolling through the day's weather forecast

## Specification
* Raspbery Pi with a touchscreen, rotary encoder, and WIFI connectivity.
* Initialization prompts user to connect to set date and time, connect to WIFI, and choose a location.
* After initial internet connection, weather forcast is pulled form Weather Underground API (https://www.wunderground.com/weather/api/)
* Screen displays date and time, along with image representation of day's weather.
* When rotary encoder is rotated clockwise, the time displayed is advanced, and the corosponding weather image is changed.
* After several seconds of no activity, the screen resets to the current time.
* A cron job queries the api to update the forecast.
* LEDs inside the case will change color in accordance with the weather.  The goal being that you can look at the clock from any angle and know what the current conditions are.

## References
* https://github.com/n0bel/PiClock is an excellent RPI clock which may be a great starting point.
