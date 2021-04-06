# Introduction to Shiny

Scripts for a presentation on Shiny and its utility. This is structured for Nyssa Silbiger's Computer Modeling class (Biol 551) at CSUN. 

***

If you want to follow along with examples and do exercises, you'll need the following packages:

```{r}
# Basics
library(tidyverse)

# Shiny
library(shiny)
library(shinythemes) # bootstrap themes

# Maps with leaflet
library(leaflet)

# Dashboards
library(shinydashboard)
```

This talk will introduce Shiny and its glorious abilities, with the assumption that you have heard of Shiny but haven't necessarily used it yet. Because there are tons of great examples online, I have highlighted tools that I have found useful and fun. The talk structure will be, more or less:

1. The building blocks: basic `shiny` functionality
2. Making interactive maps using `leaflet`
3. Making dashboards with `shinydashboard`

If you want to explore more learning materials and exercises, check out my general shiny overview [repo](https://github.com/mcsiple/shinyoverview). 