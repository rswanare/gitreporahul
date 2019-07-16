# Weather-Application

This application shows the weather information based on the City searched. The weather information includes City searched, Weather Description, Current temperature, Minimum temperature, Maximum temperature, Sunrise and Sunset.

## Getting Started
### Steps to run weather-application through IDE

1. Go to gitrepo
2. Take the git clone of the repository.
3. Import the cloned repository into spring compatible IDE. Importing the project will take time to download the dependencies.
4. Right click on the project and click on "Run As"-> spring boot application. Weather-application gets started listening on port 8080.

*Use link http://localhost:8080/weather-app/login

### Steps to run weather-application using command prompt through maven command

1. Go to gitrepo
2. Take the git clone of the repository.
3. Go to the directory of repository where pom exists; open the command prompt on the directory.
4. Run command: "mvn spring-boot:run". After execution of this command weather application started listening on port 8080.

*Use link http://localhost:8080/weather-app/login to connect to the application. 

### Application Userguide
1. Go to login page http://localhost:8080/weather-app/login
2. Register with the application, credentials required for registration is username, password and dateofbirth.
3. After registration enter the login details to access the application.
4. Type the city name into search button to access the weather information of city.
5. Logout from the application by clicking the logout button.

## Improvements

1. UI can be improved using bootstrap and css. Showing notification and validation messages in standard ui format using bootstrap css, for example validation messages should be in red color, etc.  
2. Exception Handling: Handled Generic exception, application can be improved to handle the exact exception thrown by the code.
3. Used password encryption it works with JDK 8 and 64 bit processor. Code related to password encryption is present in java files, however commented to avoid any issue at user end.
4. Negative scenarios of tests need to be added.

## Information
1. Database used: H2 Database
2. URL to view Database table: http://localhost:8080/weather-app/h2-console
3. To access database use password provided in application.properties file.
3. Used JpaRepository from Spring for database creation and mapping.
4. For delete operation used post method mapping in WeatherInfoController class, @PostMapping is used instead of @DeleteMapping because html form supports GET and POST.

## Running the tests
Junit test written and can be executed with command prompt using maven command or through IDE.

## Author

* **Rahul Wanare** 

