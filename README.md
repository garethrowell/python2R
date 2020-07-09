# python2R
This is a place to study Python-R interoperability. 

Essentially two projects, both involveing Python and R. 

Project 1: First see the NPS I&M Environmental Settings Toolkit in R by Lisa Nelson.  to use the Environmental Settings Toolkit to automate ACIS data acquisition?  My "proof-of-concept" project would be to create a dataframe in Python Pandas pulling data from the ES Toolkit. I would probably stage this by creating the initial dataframe in R, then pass it as an object to create a dataframe in Python via Reticulate.  Ultimately, my goal is to run Python ML libraries on climate data and serve up the metrics on Shiny.  So I am already committed to working in both R and Python.


The goal is to deploy Python ML models on an R shiny app server. 

Python is rich with libaries for model development while R has 1000's of stats packages. Both have good data visualization. 
But, R shiny app web services are widely available and, in some instances, its the default web deployment platform.
How far can you go with Python ML deployed to Shiny Apps?

Enter RStudio Reticulate package...


# Notes

Installed R Studio; Installed R 4.0; Created an account on shiny.io. Installed shiny and ggplot2 packages. Implemented and published 
shiny "Getting started..." demo.

# To do

Install R reticulate package and try out something very simple in Python.


