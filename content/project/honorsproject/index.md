---
title: "Honors Thesis: Efficient Spatial and Temporal Generalized Linear Modeling"
summary: Extending an existing method for computationally efficent spatial modeling to the spatiotemporal domain.  
tags:
date: "2021-05-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  url: https://github.com/grahamammal/honors-project

slides: ""
---

Spatiotemporal data is a common occurrence in a variety of fields such as ecology and epidemiology.
However, observations are often spatially and temporally correlated, leading naive models of such
data to underestimate variance in parameter estimates. Furthermore, methods that do account for
this spatial and temporal dependence often take prohibitively long to estimate due to their
computational complexity. This paper extends a computationally efficient method for spatial
modeling to the spatiotemporal domain while retaining its computational efficiency. We implement
this method and examine its effectiveness using a simulation study and by applying it to Carolina
Wren population counts in the United States between 1990 and 2010. We find that it performs
favorably compared to the naive approach and is significantly more computationally efficient
compared to the full spatiotemporal model. Additionally, it requires much less expert knowledge to
specify compared to comparable methods, making this method an attractive approach for users with
less experience with spatiotemporal modeling.

My full honors paper can be found [here](/files/Honors_Project.pdf). Slides for my honors presentation can be found [here](/files/honors-defense-slides.pdf).

