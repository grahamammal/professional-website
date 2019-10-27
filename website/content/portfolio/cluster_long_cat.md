+++
showonlyimage = false
draft = false
image = "img/portfolio/cluster_long_cat/dissim_mat.png"
date = "2016-11-05T18:25:22+05:30"
title = "Clustering Longitudinal Categorical Data"
weight = 1
+++

For summer research with professor Brianna Heggeseth, we collected all the methods for clustering categorical longitudinal data we could find with R implementations in the literature and integrated them into a Shiny app that streamlined the process of running analyses using these methods.  

<!--more-->

A GitHub mirror of the project can be found [here](https://github.com/heggesethlab/ClusterLongCat-mirror). This contains all the code needed to run the analyses. There is also a copy of the app hosted on ShinyApps.io that can be found [here](https://heggesethlab.shinyapps.io/ShinyApp/).

I learned how to write shiny apps for this project, as well as diving deep into the statistical literature searching for methods, then trying to find packages that implemented those methods. A full list of the methods we integrated into our app can be found on the front page of the app, but they included chi-squared distance, optimal matching distance, and mixtures of markov models.

Here is an example output of a dissimilarity matrix, which shows how different elements in different clusters are from each other (yellow more different):

{{< figure src="/img/portfolio/cluster_long_cat/dissim_mat.png" height="50%" width="50%" >}}
