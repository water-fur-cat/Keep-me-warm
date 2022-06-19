# Final Project of MPCS51030
##### Name: Chengyue Lin
##### UChicago Email: chengyuel@uchicago.edu
##### Name: Yue Zhou
##### UChicago Email: zhouyue@uchicago.edu

## Resources:
We use two APIs one is trying to get the weather information about the latitude and longitude we input. The URL link is https://api.openweathermap.org/data/2.5/weather?lat=\(lat)&lon=\(lon)&appid=13dd5cf354a7c0eefbc84328c83db108
<br>
The other API is trying to get the city name within the U.S. and it is a local file which is called "cities.json". In the file, each city contain the particular latitude and longitude.  
<br>

## User Interface:
Launch Animation:
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/launch_flash.jpg"/>
<br>
Main Page:
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/main_page.jpg"/>
<br>
Weather Page
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/weather_page.jpg"/>
<br>
Add cities:
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/add_city.jpg"/>
<br>
Search cities by name:
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/search_page.jpg"/>
<br>
Calculate the temperature by clicking the checkbox:
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/calculate.jpg"/>
<br>
Some 3D details about cloth:
<br>
<img width="300" height="639" src="https://github.com/water-fur-cat/Keep-me-warm/blob/main/3D_details.jpg"/>
<br>

## Functions:
The app that we built is a weather app and can help you to decide your daily dressing based on the temperature of the day. Our app contains multiple views and the design of each view is beautiful. There are multiple features that work inside our app. The following bullet points are the features contained in our app: <br>
1. Contain a splash screen that has an animation in the screen to show around 3 second. Users can easily skip the splash screen to not wait 3 second just click the “skip” button on the top right corner.
2. In the main screen, it shows us today's date and the temperature of the user’s location for now.
3. In the main screen, click the “Weather” button and go to the view of the list of weather that user “add” into the list.
4. In the main screen, click the “OOTD” button and go to the view with checkbox to select which clothing you want to want and determine whether the outfit is warm by calculating whether the body temperature reaches 26 degrees Celsius.
5. In the checkbox screen, click the “3D images” button and go to the view displaying the clothes in 3D view.
6. In the checkbox screen, click the “?” button to see what the 26 degrees Celsius dressing rules.
7. In the view of the list of weather, by default, there is only “Chicago” in the list and by locating the user’s location “San Francisco” is added into the list.
8. Adding different city names within the U.S. can be done by clicking on the button at the top right of the view of the list of weather.
9. For the view of adding a city name, there is a search bar inside the view. There will output the list of all of the city names we can add. The search result is based on user’s input. For example, we input “las” in the search bar, the result will be “Las Vegas”, “Dallas”, “Pulaski” and etc.
10. We can click any city name inside the list to display all of the information about the weather of that city.
11. It will prompt an alert when the app third launches.
12. We can delete the clothes in the ClothFeatureView by swiping to the left

## Reference
* https://stackoverflow.com/questions/41068860/get-weekday-from-date-swift-3
* https://stackoverflow.com/questions/58315628/repeating-animation-on-swiftui-image
* https://www.andyibanez.com/posts/using-corelocation-with-swiftui/
* https://openweathermap.org/guide
* https://www.youtube.com/watch?v=I6rqT8S9GpY
* https://stackoverflow.com/questions/56828331/display-a-float-with-specified-decimal-places-in-swiftui
* https://stackoverflow.com/questions/26849237/swift-convert-unix-time-to-date-and-time
