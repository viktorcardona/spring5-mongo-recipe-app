[![CircleCI](https://circleci.com/gh/viktorcardona/spring5-mongo-recipe-app.svg?style=svg)](https://circleci.com/gh/viktorcardona/spring5-mongo-recipe-app)

[![codecov](https://codecov.io/gh/viktorcardona/spring5-mongo-recipe-app/branch/master/graph/badge.svg)](https://codecov.io/gh/viktorcardona/spring5-mongo-recipe-app)

# spring5-mongo-recipe-app
Recipe Application Using MongoDB

This repository is for an example application built in my Spring Framework 5 - Beginner to Guru

You can learn about my Spring Framework 5 Online course [here.](http://courses.springframework.guru/p/spring-framework-5-begginer-to-guru/?product_id=363173)

Gradle

    This project is configure with gradle instead of maven.
    Install gradle.
    Then, run:
        gradle -version
    Shows the version. for instance: Gradle 4.6
    For compiling the app run:
        gradle
    For running the app's tests run:
        gradle test
    Run the following command to show the list of gradle tasks available to execute:
        gradle tasks
    One of the options given was:
    bootRun - Runs this project as a Spring Boot application.
    So for running the Spring Boot execute the command:
        gradle bootRun
        
 
 MongoDB
 
    The app is configure to work with MongoDB.
    It uses a embeded mongoDB.
    When the application runs look for a text like this:
    Opened connection [connectionId{localValue:1, serverValue:1}] to localhost:50622
    This is because a different port is used after the app is started. 