---
title       : Introduction for Brief information of 50 states of the USA
subtitle    : A simple shiny application
author      : Daopeng Shi
job         : Serviceman
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Overview

Brief information of 50 states of the USA is a very simple shiny application which can be used to get some basic informations about 50 USA states. The information include the specific location of a state on the USA map and some statistics figures of the state based on R maps package and R state.x77 dataset respectively.

You can visit the shiny application by the link:
[Visit Brief information of 50 states of the USA!](https://shidaopeng.shinyapps.io/shinyapp/)

--- .class #id 

## Information UI:  map

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 

The information UI of map is as above:
* The left figure shows when non of a specific state is chosen from the select box.
* The right figure show when a specific state is chosen(In the figure, California
is chosen). The chosen state will be showed in blue to highlight the location of
the state.

---

## Information UI:  datatable


```
   Statename Population Income Illiteracy Life Exp Murder HS Grad Frost   Area
1    Alabama       3615   3624        2.1    69.05   15.1    41.3    20  50708
2     Alaska        365   6315        1.5    69.31   11.3    66.7   152 566432
3    Arizona       2212   4530        1.8    70.55    7.8    58.1    15 113417
4   Arkansas       2110   3378        1.9    70.66   10.1    39.9    65  51945
5 California      21198   5114        1.1    71.71   10.3    62.6    20 156361
```

Above is the display of detail information of state when non of a specific state
is chosen from the select box(You can also uncheck the check box to hide the 
detail information). The default length of the information is 5 rows(Can be 
adjusted through the shiny datatable). 

```
   Statename Population Income Illiteracy Life Exp Murder HS Grad Frost   Area
5 California      21198   5114        1.1    71.71   10.3    62.6    20 156361
```

When a specific state is chosen, the display of detail information of state is 
as above.

--- &checkbox

## Little quiz

Which of following information about states of the USA can you get from 
application?

1. _Location of state(s) on map of the USA_
2. _Pupulation of state(s)_
3. _Area of state(s)_

*** .hint
Please refer page 3 and 4 of this presentation.

*** .explanation
All the choices are right.

Thank you to use this application. May you have a better understand of the states
of the United States of America.
