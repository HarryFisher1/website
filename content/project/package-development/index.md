---
date: "2020-04-27T00:00:00Z"
external_link: ""
#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
summary: "Exploring ideas for developing my first package in R :package:"
tags:
- R
title: Package development in R
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Having greatly benefit from a huge number of packages on CRAN and github for many different project, I would love to be able to contribute my own package that would be of use. This would also be a great learning experience and improvie my understanding of package development and deployment.

My current ideas are expanding the set of functions I developed during my PhD for working with Marco Scutari's `bnlearn` package. bn learn provdes a great set of tool to work with Bayesian Networks, and coupled with formed a major part of my PhD.

I developed several helper functions including;

- Easy median split of continuous variables to "High" and "Low" categories
- A scoring function that would iteratively score different combinations of varibales in a network structure based on variables in the data set
- A function that took the data set, the fitted network, a target outcome variable and a list of preidctor variables that would calculate the probability of the outcome variable being a particular state based on all the vales of the predictor variables.

While these functions were quite sepcific to my needs, they may be useful for someone else working with the bnlearn package.







