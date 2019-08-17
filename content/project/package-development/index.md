---
date: "2020-04-27T00:00:00Z"
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/harry__fisher
- icon: github
  icon_pack: fab
  name: GitHub
  url: https://github.com/harryfisher1
summary: "Exploring ideas for developing my first package in R :package:"
tags:
- R
title: Package development in R
---

Having greatly benefit from a huge number of packages on CRAN and GitHub for many different project, I would love to be able to contribute my own package that would be of use. This would also be a great learning experience and improve my understanding of package development and deployment.

My current ideas are expanding the set of functions I developed during my PhD for working with Marco Scutari's `bnlearn` package, which provdes a great set of tools to work with Bayesian Networks, and  formed a major part of my PhD.

During my PhD I developed several helper functions including;

- Easy median split of continuous variables to "High" and "Low" categories.
- A scoring function that would iteratively score different combinations of varibales in a network structure - so you can justify inclusion/exclusion of certain variables.
- A function that took the data, the fitted network object, a target outcome variable and a list of preidctor variables and would calculate the probability of the outcome variable being a particular state based on different combinations of values of the predictor variables.

While these functions were quite sepcific to my needs, they may be useful for someone else working with the bnlearn package. 

I would also like to do something with the athletics data I have been working with. Maybe some kind of plugin what lets you search for an athlete and generates a specific report for their performances...

I have been working on a [dashboard](https://harryfish.shinyapps.io/resultsdashboard/) to summarise athleteics results, but wonder if there is something more I could do... :thinking:

To be continued!









