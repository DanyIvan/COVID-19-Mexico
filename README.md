### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)

## Installation <a name="installation"></a>

The anaconda default installation, plus geopandas and plotly, is necessary to run the notebook in any version of python 3.

## Project Motivation<a name="motivation"></a>

In this project I aimed to analyze a public dataset of COVID-19 cases in Mexico to understand:

* 1. __What kind of people are infected with COVID-19 in Mexico?__ To answer this question we will have to look at columns such as sex, age, or municipality_residence.
* 2. __What is related to the severity of COVID 19? Specifically, can we predict whether a person is likely to be intubated, hospitalized, or whether a person will survive the disease?__  To answer this question we will have to look at columns such as intubated, diabetes, asthma, etc.
* 3. __Can we make a prediction for the end of the pandemic in Mexico City from this data?__ To answer this question we will use the data from daily cases in Mexico City and an epidemic model.

## File Descriptions <a name="files"></a>

* `COVID-19 Mexico.ipynb`. This file contains all the code for the analysis
* `COVID-19 Mexico.html`. This file contains an html version of the notebook
* `COVID-19-mex.csv`. This file contains public data for COVID-19  cases in Mexico
* `mexico_city_municipalities.json`. This file contains the data for the geoshapes of the Mexico City municipalities.
* `mexican_states.geojson`. This file contains geodata for Mexican states.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@dan_y/understanding-covid-19-in-mexico-5abe4a8f81f4).

