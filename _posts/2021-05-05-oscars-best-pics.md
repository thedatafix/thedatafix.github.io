---
title: "IMDB's Best Picture Rankings" #"The PGA Money List"
#last_modified_at: 2016-03-09T16:20:02-05:00
header:
 teaser: #assets/post_teasers/masters-driving-distances.png
categories:
  - Visualizations
tags:
  - Movies

excerpt: #"Plotting the Top 20 Earners Since 1980"
sidebar:
  nav: sidebar-sample

classes: wide

# The Oscar's award for best picture has been given each year since 1927.  Each year a new title is added to # the growing list. This in turn leads people to compare the best picture winners in debates to determine # where they rank amongst one another.  This plot is a distillation of IMDB's All time Rankings. We've # created a box plot for each decade to illustrate how its winners rank.  We then overlaid the top 25 ranked # films as a labeled scatterplot to which movies represent the upper echelon of ranking and when they won the # award.

#*A semi-interactive plot that represents each year's best picture winner ranking on IMDB through a box #plot. Additionally, we have overlaid the top 25 ranked films as a labeled scatterplot.*

---
*Plotting the success of Oscar Best Picture Winners relative to one another*

{% include oscars/oscars_decades_plot.html type="left" width="100" height="100"%}
