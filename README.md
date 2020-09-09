# COVID EXPLORATION
Analysis of COVID-19 Data with R

## Required Libraries
```
library(readxl)
library(ggplot2)
library(dplyr)
library(readr)
library(gridExtra)
library(scales)
library(lubridate)
library(wordcloud)
library(tidytext)
library(tm)
library(tidyr)
```

## Options, Theme, & Color Pallette 
```
options(repr.plot.width=15, repr.plot.height=7)
my_colors <- c("#3E7DCC", "#8F9CB3", "#00C8C8", "#F9D84A", "#8CC0FF", "#4D525A")
show_col(my_colors, labels = F, borders = NA) #color palette
my_theme <- theme(plot.background = element_rect(fill = "grey98", color = "grey20"),
                  panel.background = element_rect(fill = "grey98"),
                  panel.grid.major = element_line(colour = "grey87"),
                  text = element_text(color = "grey20"),
                  plot.title = element_text(size = 22),
                  plot.subtitle = element_text(size = 17),
                  axis.title = element_text(size = 15),
                  axis.text = element_text(size = 15),
                  legend.box.background = element_rect(color = "grey20", fill = "grey98", size = 0.1),
                  legend.box.margin = margin(t = 3, r = 3, b = 3, l = 3),
                  legend.title = element_blank(),
                  legend.text = element_text(size = 15),
                  strip.text = element_text(size=17))
                  
```

![](/images/US%20Deaths%20Over%20Time.jpeg)
