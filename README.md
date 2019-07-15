# Weather-Application

This application shows the weather information based on the City searched. The weather information includes City searched, Weather Description, Current temperature, Minimum temperature, maximum temperature, sunrise and sunset.

## Getting Started

Take the git clone of the repository, import the cloned repository into spring compatible IDE. Run the application as Spring Boot Application.

### How the application works?
1. Go to login page 
2. Register with the application, credentials required for registration username, password and dateofbirth.
3. After registration enter the login details to access the application.
4. Type the city name into search button to access the weather information of city.
5. Logout from the application by clicking the logout button.

## Improvements

1. UI can be improved using bootstrap and css. Showing notification and validation messages in standard ui format using bootstrap css, for example validation 	messages should be in red color, etc. I have worked mostly on the backend side so has less experince of UI development. This project has given me the oppertunity to explore that, though it has taken a time still I learned a lot. 
2. Exception Handling : used generic exception handling, application can be improved by handling specific exception.

## Information
1. Database used : H2 Database
2. URL to view Database table: http://localhost:8080/weather-app/h2-console
3. Used JpaRepository from Spring for database creation and mapping.
4. For delete used post method in html form as html form only supports GET and POST.


## Running the tests

Junit test written and can be executed with command prompt using maven command and through IDE.


## Authors

* **Rahul Wanare** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)
