---
layout: post
title:  "First steps in R shiny"
date:   2022-04-14 14:30:00 +0100
categories: jekyll update
---


Even though I already answered some questions about R *shiny* on Stack Overflow ([1](https://stackoverflow.com/questions/68270439/change-default-color-of-bar-plot-and-legend-in-ggplot2/68270714#68270714), [2](https://stackoverflow.com/questions/66211325/how-to-create-a-barchart-with-plotly/66213252#66213252)), I never got a basic introduction. You know how it goes in bioinformatics: copying and pasting or a tutorial are often enough to handle a program superficially.   

Recently, I have caught up with this introduction. I attended a course at the Swiss Institute of Bioinformatics (SIB) that broadened my understanding of R *shiny*. The basis for the course was knowledge of R, but no prior knowledge of R *shiny*. Within one day we learned how to design and deploy our own R *shiny* app.   

I decided to do a normality test app. It allows to evaluate the normality of a variable of a data frame based on visualizations (Histogram, Boxplot, QQ Plot), kurtosis, skewness, and a Shapiro-Wilk test. You can use it with your own data and it runs locally. Using this app requires no R pre-knowledge. A step-by-step guide with screen shots can be found on my [GitHub page](https://github.com/pascalangst/Normality_evaluation). Basically, just open the code in R (studio) and hit “Run app”. It should be working on all systems but might be slower with large data and low resources.  
 
Let me know if you have any questions or comments about the app. Happy testing.



