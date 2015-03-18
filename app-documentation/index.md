---
title       : Developing Data Products Project Course
subtitle    : Shiny Application - Body Mass Index Calculator 
author      : 
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax,quiz,bootstrap]     # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Body Mass Index Calulator

This application calculates the Body Mass Index (BMI) of a user based on the user's weight and height. The user enters his/her weight in pounds and height in inches.

The application displays:
  + The weight entered in pounds
  + The height entered in inches
  + The calculated BMI
  + The categorization the BMI as "underweight", "normal", "overweight", or "obese" 

---

## Formula
The formula used for calculating the BMI in the US system is:



$$BMI = \frac{{weight~in~pounds} \times 703}{(height~in~inches)^2}$$
$$~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~$$

## Weight Category based on BMI



BMI | Weight Category
--- | ---
Below 18.5 | underweight
18.5 - 24.9 | normal
24.9 - 29.9 | overweight
Above 29.9 | obese

---
