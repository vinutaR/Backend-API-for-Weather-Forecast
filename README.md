# Backend-API-for-Weather-Forecast
Weather api
Application Programming Interfaces that provide access to current & historical weather data on a global scale. There are several public weather APIs like OpenWeatherMap API, Dark Sky API, & Visual Crossing Weather API. These REST APIs can be used to build powerful weather apps
# Prerequisites

- Python
- Fladk
- Requests library
- Openweather API

# Brief Procedure
Install the required libraries.
Get your OpenWeatherMap API key.
Run the application.
Open Postman and create a new request to http://127.0.0.1:5000/weather with the GET method.
Add a query param location with the value being the city and state (eg: Bengaluru, KA).
Send the request and check the output.
NOTE: You can check the accuracy of the retrieved weather data by OpenWeatherMap.

# Weather API:  https://openweathermap.org
# Detailed explanation
Run the python script in VScode
In the terminal you can see the base url http://127.0.0.1:5000. When you click on this url, you will see 404 error.
Now go to your Postman workspace, set the request type to GET.
Enter the URL for your Flask API endpoint i.e, http://127.0.0.1:5000/weather?.
Click on the "Params" tab. In the "Key" column, enter location. In the "Value" column, enter the city and state for which you want to retrieve the weather information.
Click the send button to make the request.
Now go back to the base url, inorder to fetch the weather data, you have to append the base url with the api endpoint i.e, http://127.0.0.1:5000/weather?location=city,state (eg: http://127.0.0.1:5000/weather?location=Bengaluru, Karnataka&location=Shivamogga, Karnataka).
Now you can see the json file.

# Screenshots



# Additionals
This python script accepts multiple query parameters. The code includes the ability to retrieve weather information for multiple locations through the /weather endpoint.
The code includes try-except blocks to catch and handle exceptions that may occur during API requests or data processing.
Appropriate status codes are returned in the API responses, such as 400 for bad requests, 200 for response and 500 for internal server errors.
