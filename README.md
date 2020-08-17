# python2R
This is a place to study Python-R interoperability. The idea here is to take advantage of some existing R tools and use them from Python. 
The whole process is broken down into a series of projects.

Project 1: Passing data from R dataframe to Pandas dataframe

WHY this project: Natural resource and ecological scientists commonly work in R. They are already pulling climate data through existing R data APIs. 
As proof-of-concept for R to Python interoperability, this project takes "real-world" climate data from a dataframe in R and passes it to a dataframe in Pandas.

WHEN this project does: Loads ACIS .csv climate data into an R dataframe and pushes it to a Pandas dataframe.


Project 2: Use the NPS Environmental Settings ToolkingR Toolkit to acquire ACIS climate data

Use the NPS I&M Environmental Settings Toolkit in R to obtain ACIS climate data and pass the data to a Pandas dataframe.

Project 3: Conducting some simple exploratory data analysis of climate data in Python and reporting to R Shiny

These two projects will serve as "proof-of-concept" that ACIS climate data aquisition can be automated in R and shared into the Python environment where it becomes available for ML modeling. From there, it can be passed to Shiny for end-user metrics.

Project 4: Exploring time series climate data using Python ML

This is a separate repo.



# Notes

Install R reticulate package and try to move data from R to Python.


