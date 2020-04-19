# Flutter weather app

## Description
Implement weather mobile application using public https://www.metaweather.com/api/.

### Requirements
- The application should be implemented using Flutter SDK;
- Target platform is iOS;
- The application should not crash;
- The application should perform well with any amount of data;
- You're free to choose any 3rd party libraries for solving the task;
- Use any design solutions that you think work best for this task.

### Screens

#### Splash screen
- Display application logo for 3 seconds;
- Navigate user to catalog screen.

#### Catalog screen
- Show loading state;
- Fetch the list of the nearby cities by calling `metaweather` location search endpoint with the following coordinates `55.5815245, 36.8251489`;
- Display the list of the fetched cities;
- Tap on any city should open the corresponding city details screen.

#### City details screen
- Show loading state;
- Fetch the weather forecast for the specified city using location endpoint;
- Back link should lead to catalog screen;
- Display generic location name, including: city name and current time;
- Display the following data for each available forecasted day: 
  - Date
  - Weather state
  - Temperature range
  - Predictability

