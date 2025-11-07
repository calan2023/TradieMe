# SENG302 Team 1000 project
A website using ```gradle```, ```Spring Boot```, ```Thymeleaf```, and ```GitLab CI```.

This is a website that allows renovators to manage their own home renovations.
Records can be made that contain all details about their ongoing renovations, including the rooms being renovated and jobs that need to be done.
These records can be shared so renovators can share their progress on their renovations.
Renovators can also post renovation jobs they are wanting help with, allowing tradies to find work.
Tradies can search through all posted jobs to find one that fits their expertise and submit a quote of how much they are willing to complete the job for.
Renovators have the ability to compare tradie statistics and reject tradies using a Tinder-style swiping feature that will help renovators quickly find the best tradie for their job.

## How to run locally
### 1 - Running the project
From the root directory ...

On Linux:
```
./gradlew bootRun
```

On Windows:
```
gradlew bootRun
```

By default, the application will run on local port 8080 [http://localhost:8080](http://localhost:8080)

### 2 - Running unit, integration and acceptance tests
On Linux:
```
./gradlew test
```
```
./gradlew integration
```
```
./gradlew cucumber
```

On Windows:
```
gradlew test
```
```
gradlew integration
```
```
gradlew cucumber
```

## Licence
Our full licence can be found at LICENCE.md

## Contributors

- SENG302 teaching team
- Alex Cheals
- Calan Meechang
- Dury Kim
- Fergus Ord
- Luke Burton
- Morgan Lee
