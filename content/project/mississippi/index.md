---
title: Data Sensing on the Mississippi
summary: Data Analysis for a Canoe Trip Down the Mississippi River
tags:
date: "2020-05-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  url: https://github.com/jkim5/miss-canoe

slides: ""
---

Over the summer and fall of 2019, John Kim, a professor at Macalester college and his team canoed large stretches of the Mississippi River to better understand the myriad interactions humans have with the river. As part of this, he attached a data sensing device to his canoe. 

By the end of the trip, over 150,000 observations had been recorded. In order to make better sense of the data, John Kim asked me perform the data analysis for this trip. This collaboration resulted in the following [draft page](http://mississippistudies.org/data-sensing-testing/).


I made the following two maps as part of this collaboration in order to understand and learn from this trip. The first uses leaflet and d3 to allow the user to see the values of the sensors at every part of the trip. 

<div height = "600" width = "100%">
  <iframe height="600" width="100%" src="https://ellen-graham.com/miss/dynamic/index.html" scrolling="no" frameborder="0"></iframe>
</div>

The second allows for an at a glance view of the trip, vertically oriented so you can easily follow the river as it flows to the Gulf of Mexico. 

<div height = "600" width = "100%">
  <iframe height="600" width="100%" src="https://ellen-graham.com/miss/static/index.html" scrolling="no" frameborder="0"></iframe>
</div>

The code can be found on my github at https://github.com/grahamammal/mississippi_canoe. The repository was created for analysis and is messy, but the code for the maps can be found at [d3_fun/dynamic](https://github.com/grahamammal/mississippi_canoe/tree/master/d3_fun/dynamic) and [d3_fun/static](https://github.com/grahamammal/mississippi_canoe/tree/master/d3_fun/static_map) respectively.  