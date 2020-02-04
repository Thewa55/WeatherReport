# WeatherReport

This webpage will tell you today's weather along with a five day forcast. The webpage will save any previous searches you had below the search bar. The main display will show you: 
The city name, date, current weather icon, temperature in Celsius and Fahrenheit, humidity, windspeed in MPH, and a UV index with a colored background.
The five day forcast will yield the weather icon, temperature in Fahrenheit and humidity.
If you click on "My location", the browser might ask you to allow sharing your location, hit yes if you want to get local weather otherwise it won't show your current weather.
The clear all button will clear your saved searches along with any buttons for previous searches.
Any city input that yields a 404 error or numerical input will spit back out an error under the search bar that will time out in 2 seconds.


//
Thoughts on the homework: 
This homework is tricky as it requires 3 separate API calls in order to get all the information you need to fill everything. I learned that you can find the actual time from dt by doing "new date (dt * 1000)". After that I spent more time then I would like to admit trying to convert the dt time to the searched city local time, which is possible by using Google Map API... At that point I gave up and was a bit over my head. After that I settled on my original idea of pulling every 8th index from the five day forcast since it'll always be 1 day ahead. Afterwards, I spent the rest of the time debugging and trying to break my code. Total time spent on assignment: ~12 hours.