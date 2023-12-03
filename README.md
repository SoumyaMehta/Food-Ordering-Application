# Food Ordering Application

## Overview
This app allows users to browse and order their favourite dishes from nearby restaurants.

Development Involved:
* Using several REST API endpoints, such as Google Maps API, for querying information with a Spring-based backend.
* Writing unit tests and using error logs, IDE breakpoints, and assert statements for a structured debugging approach.
* Optimizing app performance for large load scenarios as well as including an advanced search feature within the app.

![image](https://github.com/SoumyaMehta/QEats/assets/69056406/8ca557bf-f8d6-4051-8694-1ac973fe0c7b)

![image](https://github.com/SoumyaMehta/QEats/assets/69056406/5061db46-abba-48fb-a98c-8ab8b2ae7080)

![image](https://github.com/SoumyaMehta/QEats/assets/69056406/4690177a-7eb7-4d2f-80f6-3d1a2cdd51c0)

# Pre-requisites

* Java 1.8/1.11/1.15
* Gradle 6

# How to run the code

Use `run.sh` if you are on Linux/Unix/macOS Operating systems and `run.bat` if you are on Windows

Use the following scripts for their respective commands:
* `gradle clean build -x test --no-daemon` to create the jar file `geektrust.jar` in the `build/libs` folder.
* `java -jar build/libs/geektrust.jar sample_input/input1.txt` to execute the jar file passing in the sample input file as the command line argument.

Use the build.gradle file provided along with this project. 

Change the main class entry under the `jar` task in the build.gradle if your main class has changed:
```
 manifest {
        attributes 'Main-Class' : 'com.geektrust.backend.App' //Change this to the main class of your program which will be executed
    }
```

# How to execute the unit tests

 `gradle clean test --no-daemon` will execute the unit tests.

# Help

You can read the build instructions [here](https://github.com/geektrust/coding-problem-artefacts/tree/master/Java) or reach me out at `isoumya.dev@gmail.com`
