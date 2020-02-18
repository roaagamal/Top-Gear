mpg prediction for your car
========================================================
author: Roaa Gamal
date: 18/2/2020

Overview
========================================================

This is a presentation about an app that helps the users to predict the miles per gallon of their car based on the specifications of the car.

The variables that we are using for the prediction are the following:

1. Horsepower
2. Number of cylinders
3. Transmission type 
4. Weight of the car.


Functionality
========================================================

The user need to insert the horsepower, number of cylinders, transmission type, weight of the car in 1000 lbs. Then the application is going to filter the data and is going to build a model of the mpg rate of the car based on specifications and the users will get the rate in the main page of their device.


Slide With Code
========================================================


```r
summary(mtcars)
```

```
      mpg             cyl             disp             hp       
 Min.   :10.40   Min.   :4.000   Min.   : 71.1   Min.   : 52.0  
 1st Qu.:15.43   1st Qu.:4.000   1st Qu.:120.8   1st Qu.: 96.5  
 Median :19.20   Median :6.000   Median :196.3   Median :123.0  
 Mean   :20.09   Mean   :6.188   Mean   :230.7   Mean   :146.7  
 3rd Qu.:22.80   3rd Qu.:8.000   3rd Qu.:326.0   3rd Qu.:180.0  
 Max.   :33.90   Max.   :8.000   Max.   :472.0   Max.   :335.0  
      drat             wt             qsec             vs        
 Min.   :2.760   Min.   :1.513   Min.   :14.50   Min.   :0.0000  
 1st Qu.:3.080   1st Qu.:2.581   1st Qu.:16.89   1st Qu.:0.0000  
 Median :3.695   Median :3.325   Median :17.71   Median :0.0000  
 Mean   :3.597   Mean   :3.217   Mean   :17.85   Mean   :0.4375  
 3rd Qu.:3.920   3rd Qu.:3.610   3rd Qu.:18.90   3rd Qu.:1.0000  
 Max.   :4.930   Max.   :5.424   Max.   :22.90   Max.   :1.0000  
       am              gear            carb      
 Min.   :0.0000   Min.   :3.000   Min.   :1.000  
 1st Qu.:0.0000   1st Qu.:3.000   1st Qu.:2.000  
 Median :0.0000   Median :4.000   Median :2.000  
 Mean   :0.4062   Mean   :3.688   Mean   :2.812  
 3rd Qu.:1.0000   3rd Qu.:4.000   3rd Qu.:4.000  
 Max.   :1.0000   Max.   :5.000   Max.   :8.000  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](Presentation-figure/unnamed-chunk-2-1.png)

Shiny application and files
========================================================

You can go to: https://roaagamal.shinyapps.io/Peer-graded-Assignment/
and start working with the app.

The application is build using Shiny package and the source code is in 2 files:
- `ui.R`
- `server.R`
