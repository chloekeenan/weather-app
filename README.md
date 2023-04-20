![Todays Weather](images/game.png)



## Application Overview 

* Deployed Site: [Here](https://chloes--weather-app.herokuapp.com/)
Users of the straightforward app 'Weather Today' may check the temperature and current weather in the city of their choice.  
 

## Goal
I wanted to make an app that is both practical and simple to use. The user may simply observe the current weather and temperature.

## Target Audience
This application is aimed at users of all ages who simply just want to check the weather of any location. 

# Current Features
**Header**
- The 'Todays Weather' header sits at the top of the application and shows the name of the game in a minimalistic font.
- Using the pyfiglet module, the style is produced. The user is prompted to check the weather in any certain city when the software first loads.
 
![Game](images/game.png)

![Game Running](images/running.png)

**Error**
- When a user types in an invalid address, the program displays "no city found." 
![Game Error](images/Error.png)

# Future Features
- 5 day forecast: The next feature I would want to include is the capability of 5 day forecasting for each city.

- Comparison of Historical Data: OpenWeatherMap provides a premium option for up to 40 years of historical weather information. Future functionality that enables a user to compare weather data to past years is something I would want to implement. This would make it possible to assess the consequences of climate change or a crisis by contrasting real-time data with historical data.

# Validation Testing
 When running through the , CI Linter no issues were reported.
 ![Validator](images/CI%20Linter.png)

 ## Bugs

Bug | Status | Fix |
----|--------|-----|
CI Linter Error, line too long on API key| Resolved | Spent time with the student support team and they introduced me to noqa. 
requests==2.28.1 needed to be added to requiremnts.txt | Resolved | Checked with fellow students on Slack. 


# Known issues
- I am aware that not all phones can access the deployed Heroku site. 

# Frameworks and Libraries
 
- Code for the game was inspired by: How to Build a Weather App with Python | Weather API (https://www.youtube.com/watch?v=baWzHKfrvqw&t=453s)
