---
title: Clustering Longitudinal Categorical Data
summary: A summer research project that my team and I worked with for Professor Brianna Heggeseth.
tags:
# - Deep Learning
date: "2019-08-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  url: https://github.com/heggesethlab/ClusterLongCat-mirror

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

For summer research with professor Brianna Heggeseth, we collected all the methods for clustering categorical longitudinal data we could find with R implementations in the literature and integrated them into a Shiny app that streamlined the process of running analyses using these methods.  

<!--more-->

A GitHub mirror of the project can be found [here](https://github.com/heggesethlab/ClusterLongCat-mirror). This contains all the code needed to run the analyses. There is also a copy of the app hosted on ShinyApps.io that can be found [here](https://heggesethlab.shinyapps.io/ShinyApp/).

I learned how to write shiny apps for this project, as well as diving deep into the statistical literature searching for methods, then trying to find packages that implemented those methods. A full list of the methods we integrated into our app can be found on the front page of the app, but they included chi-squared distance, optimal matching distance, and mixtures of markov models.

Above is an example output of a dissimilarity matrix, which shows how different elements in different clusters are from each other (yellow more different).
