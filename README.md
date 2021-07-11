# San Francisco Neighborhood Housing Market Analysis

This is a Jupyter notebook analysis to evaluate the housing market throughout various
neighboorhoods in San Francisco.  Multiple databases are utilized to show the average sales price
per square foot and in comparison, the average gross rental income.  With these figures, a
real estate investor could narrow in on specific neighborhoods to find the largest return on investment.

---

## Technologies

This analysis leverages a Jupyter notebook, multiple csv files and a Mapbox API access token.

---

## Installation Guide

Before running this analysis, the following libraries and dependencies need to be installed:

'''
import os
import pandas as pd
import plotly.express as px
import hvplot.pandas
from pathlib import Path
from dotenv import load_dotenv
'''

---

## Usage

To visualize the sales price per square foot and gross rent trends between 2010 and 2016
within multiple San Francisco neighborhoods, clone the repository and utilize the sfo_housing_analysis file along with the csv files in the Resources folder (housing_per_year, neighborhoods_coordinates and sfo_neighborhoods_census_data).  You will find descriptive and interactive
graphs and maps that show the various neighborhoods along with a heat map legend directing you
to the most profitable scenarios. 

The first graph displayed will demonstrate the steady increase in housing units within the San Francisco 
housing market between 2010 and 2016.

Moving forward through the analysis, a visual shows how the gross rent increases at a much steeper rate
as compared to the sale price per square foot, which experienced only a slight increase.

Using a more targeted approach, the next graph is interactive and the user can toggle through the various neighborhoods to pinpoint the difference and trends with sale price per square foot and average
gross rent.

Finally, geospatial relationships in data are showcased in an interactive map of the neighborhoods.  This visual will assist a real estate investor in making the most of their investment based on the potential gross retal income.  

---

## Contributors

Brought to you by ABPT - the leader in proptech!

---

## License

MIT