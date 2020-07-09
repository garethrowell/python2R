# python2R
This is a place to study Python-R interoperability. Projects here will employ the R Reticulate is the interoperability package

# Project 1:  Use the NPS I&M Environmental Settings Toolkit in R to obtain ACIS climate data and pass the data to a Pandas dataframe.

# Project 2: Display the data in Matplotlib and Seaborn, then visuaize the data again using R tools in Shiny

These two projects will serve as "proof-of-concept" that ACIS climate data aquisition can be automated in R and shared into the Python environment where it becomes available for ML modeling. From there, it can be passed to Shiny for end-user metrics.


Notes

This a "real-world" project. First learn

https://github.com/nationalparkservice/EnvironmentalSetting_Toolkit

To use the Environmental Settings Toolkit in R to automate ACIS data acquisition.  The purpose of this project is to create a dataframe in Python Pandas pulling data from the ES Toolkit. I will stage this by creating the initial dataframe in R, then pass it as an object to create a dataframe in Python via Reticulate.    So I am already committed to working in both R and Python.


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


