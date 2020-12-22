# Spring Boot Jokes App
This application displays random joke on the index.

1. Create Spring Boot Project from Spring Initializr
   
    1.1. We will need "Spring Web" and "Thymeleaf" as dependencies.
   
2. Add Dependency: "Chuck Norris For Actuator"
   
    2.1. Follow this link for getting the newest version: https://mvnrepository.com/artifact/guru.springframework/chuck-norris-for-actuator
   
3. Create Service to return joke string
   
    3.1. Creating package name service.\
    3.2. Creating JokeService Interface with getJoke() function signature. \
    3.3. Creating implement class for JokeService. \
    3.4. Creating Spring MVC Jokes controller. First, creating controller package. \
    3.5. Creating Controller class with showJoke() function. \
    3.6. Setting up the request mapping, that maps context root ("/","") to Jokes View. \
    3.7. Adding new attribute to Model (org.springframework.ui.Model) named "joke". \
    3.8. Returning view name "chucknorris", \
    3.9. Creating view for "chucknorris" with thymeleaf.
    
   