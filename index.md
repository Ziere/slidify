---
title       : Developing Data Products
subtitle    : Course Project
author      : Francisco Moreno Arcas
job         : Coursera
framework   : io2012   # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Car comparison explorer

-. This application was created for the Developing Data Products MOOC from Coursera

-. You can check the application at <https://ziere.shinyapps.io/shiny/>

-. The purpose of this application is compare two properties of 2 given cars from the dataset **mtcars** using a plot to visualize those ones.

-. We will use this dataset to compare two cars using a x-y plot system with the variables includes in this dataset.

-. Also is add a slider with the size of the text to show in the plot.

---

## Things you can use in the application form (1 of 2)

1. Car 1 and Car2 can be selected from the mtcars database:


```r
row.names(mtcars)
```

```
##  [1] "Mazda RX4"           "Mazda RX4 Wag"       "Datsun 710"         
##  [4] "Hornet 4 Drive"      "Hornet Sportabout"   "Valiant"            
##  [7] "Duster 360"          "Merc 240D"           "Merc 230"           
## [10] "Merc 280"            "Merc 280C"           "Merc 450SE"         
## [13] "Merc 450SL"          "Merc 450SLC"         "Cadillac Fleetwood" 
## [16] "Lincoln Continental" "Chrysler Imperial"   "Fiat 128"           
## [19] "Honda Civic"         "Toyota Corolla"      "Toyota Corona"      
## [22] "Dodge Challenger"    "AMC Javelin"         "Camaro Z28"         
## [25] "Pontiac Firebird"    "Fiat X1-9"           "Porsche 914-2"      
## [28] "Lotus Europa"        "Ford Pantera L"      "Ferrari Dino"       
## [31] "Maserati Bora"       "Volvo 142E"
```

---

## Things you can use in the application form (2 of 2)

1. X and Y axis can be adjust to each of the followings variables:


```r
names(mtcars)
```

```
##  [1] "mpg"  "cyl"  "disp" "hp"   "drat" "wt"   "qsec" "vs"   "am"   "gear"
## [11] "carb"
```

*In the next slide you can see a example plot using the following input data:*

1. Car 1 <- "Toyota Corona"

2. Car 2 <- "Hornet 4 Drive"

3. X <- "mpg"

4. Y <- "am"

5. Text size <- 10

---

## Plot example

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

---

## Thanks

If you have questions related to this work don't hessitate to contact me.
