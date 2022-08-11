

# Boston Airbnb Analysis

A sneak peek into the Airbnb activity in Boston, MA, USA : <a href="https://www.kaggle.com/datasets/airbnb/boston" target="_blank">Kaggle Link</a>

* #### Blog post URL: https://medium.com/@harshthakkar93/boston-airbnb-analysis-1c6423db5c92


Table of Contents:
- Installations
- Project Motivation
- File Descriptions
- Steps to run the project
- Acknowledgements


## Installations

- NumPy:
NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays


- pandas:
pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series


- matplotlib.pyplot:
matplotlib.pyplot is a collection of functions that make matplotlib work like MATLAB. Each pyplot function makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels, etc.


- wordcloud:
Word Cloud is a data visualization technique used for representing text data in which the size of each word indicates its frequency or importance. Significant textual data points can be highlighted using a word cloud. Word clouds are widely used for analyzing data from social network website

* Installation Syntax:
  * import numpy as np 
  * import pandas as pd
  * import matplotlib.pyplot as plt
  * from wordcloud import WordCloud 

## Project Motivation

Boston Airbnb is a huge DataSet that comes with a lots of information about the listings, hosts, availability, pricing, reviews.
This opens up a lot of possible findings about how the properties have been listed, type of properties, change in pricing per neighborhood and type of properties, amenities offered,type of rooms offered.


## File Descriptions
* BostonAirbnb.ipynb : Python notebook file with all the scripts that help identify information about Boston Airbnb Listings
    * import packages, read listings.csv
    * Identify missing values and clean data on Price Column
    * Average Price of listings per Neighborhood
    * Average Rating of listings per Neighborhood
    * Top amenities offered for the listings
    * Average Price as per the Type of Property
    * Average Price as per the Room Type
    * Distribution of Listings as per RoomType
    * Hosts with most listings 
    * Neighborhoods with most listings

* listings.csv : Including full descriptions and average review score

## Steps to run the Project:
* BostonAirbnb.ipynb is the entry point to the project.
* A convenient way to run would be through Jupyter Notebook app
* Ruuning each cell through BostonAirbnb.ipynb would first read through the listings.csv file and later yield results for the about listed scenarios under File Descriptions --> BostonAirbnb.ipynb


## Acknowledgements: 
* https://stackoverflow.com/  : Scenario based syntax assistance and troubleshooting
* https://www.delftstack.com/ : Matplotlib sceanrio based assistance to improvise the visual components

