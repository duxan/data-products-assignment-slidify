---
title       : EM clustering 
subtitle    : Example of Old Faitful data / Data Products assignment
author      : Dusan Randjelovic
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## EM clustering

Recently, I found out about expectation-maximisation algorithm, and was fascinated with how easily it could be understood. This project is a demo of clustering data with this algorithm.

Data used is Old Faitful geyser eruption data. When initial variables are set, algorithm converges in set number of iterations.

EM here was done using `mvtnorm` library, to fit data to multivariate normal distributions.

Final shiny app could be found [HERE](https://duxan.shinyapps.io/Data_products_EM_example/)

--- 

**Initialising**: User should first provide initialising data for both clusters, which will produce (reload) first plot, like here too

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

---

**Iterations**: After that user can set how many iterations algorithm should run, which updates second plot, like here too (27 iterations set, for previous initialising data)

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)

---

Shiny app: [duxan.shinyapps.io](https://duxan.shinyapps.io/Data_products_EM_example/)  

THIS CODE GITHUB: [github.com/duxan](https://github.com/duxan/data-products-assignment-slidify)

## Thank you!

