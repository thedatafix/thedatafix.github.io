---
title: #"TDF"
layout: single
permalink: "/"
header:
  overlay_color: #"#000"
  overlay_filter: #"0.2"
  overlay_image:
  image:
  actions:
    #- label: "See More"
    #  url: "test-link"
excerpt: "the data perspective"

#author_profile: True

sidebar:
  nav: sidebar-sample

feature_row_left:
  - image_path: assets/post_teasers/updated-pga-money-list.png
    excerpt: "**The PGA Money List** <br /> An interactive plot of the Top 20 PGA Earners Since 1980"
    url: "/visualizations/pga-money-list/"
    btn_label: "view"
    btn_class: "btn--primary" # "btn--secondar"

feature_row_left2:
  - image_path: assets/post_teasers/masters-driving-distances.png
    excerpt: "**Driving Distance at The Masters** <br /> Visualizing Driving Distance of the Field and Winner from 1990 - 2019"
    url: "/visualizations/masters-driving-distances/"
    btn_label: "view"
    btn_class: "btn--primary"

feature_row_left3:
  - image_path: assets/images/fav3/android-chrome-192x192.png
    excerpt: "**Welcome to The Data Fix** <br /> Using data science to make sense of the world around us"
    url: "/about/"
    btn_label: "view"
    btn_class: "btn--primary"

feature_row_left4:
  - image_path: assets/post_teasers/oscars-decades.png #assets/images/fav3/android-chrome-192x192.png
    excerpt: "**IMDB's Best Picture Rankings** <br /> Plotting the success of Oscar Best Picture Winners relative to one another"
    url: "/visualizations/oscars-best-pics/"
    btn_label: "view"
    btn_class: "btn--primary"

---
<h1 style="font-family:Monaco;text-align:left">The Latest</h1>

---
{% include feature_row id="feature_row_left3" type="left" %}
{% include feature_row id="feature_row_left4" type="left" %}
{% include feature_row id="feature_row_left" type="left" %}
{% include feature_row id="feature_row_left2" type="left" %}
---
