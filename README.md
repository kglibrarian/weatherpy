# weatherpy

This repository contains python scripts to visualize the weather of 500+ cites across the world and focuses on the Python library Citipy, the Open Weather Map API, MatPlotLib, Pandas, and Jupyter Notebooks.

## Background

The Python code in this repository randomly selects 500+ cities across the world, uses a series of succesive API calls, prints a log of each city as it's being processed (with the city number and city name), saves all data in a CSV, and creates scatter plots showing relationships between: 

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Also included in the repository is a written description of theree observable trends based on the data. 

## Instructions

Install Python 3.0 (https://www.python.org/downloads/)
Install Jupyter Notebooks (https://jupyter.readthedocs.io/en/latest/install.html)
Install Anaconda (https://docs.anaconda.com/anaconda/install/windows/)
Intall the citipy module. In the Git Bash prompt type in "pip install citipy"(don't type the quotes). 

To run Jupyter Notebooks in your browser: 
Open the Anaconda prompt on your computer and type in: jupyter notebook 
OR open the Git Bash prompt and type in: juypter notebook

Then navigate in Jupyter Notebooks to the .ipynm file that you downloaded from this repository. 

You may also consider installing a virtual environment (https://packaging.python.org/guides/installing-using-pip-and-virtualenv/)and installing Python version 3.7.0 and Citipy into that environment. 


## Copyright

Data Boot Camp © 2018. All Rights Reserved.
