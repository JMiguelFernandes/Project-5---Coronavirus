# Project 6 - Visualizing Real World Data

Project by Shelley Obery, Nicholas Gotzens and João Fernandes

## Project Description

This project is part of the IronHack Data Analytics Bootcamp and its goal is to practice creating and interpreting different types of visualizations using real world data, as well as statistical analysis. 

Our team decided to work on the topic of Covid-19 in the USA.
_______

## Questions & Hypotheses

We were interested in understanding whether there were differences between Democratic and Republican states in terms of handling and outcomes of the COVID-19 pandemic. Specifically, we wanted to answer the following:

- Were there differences in the number of cases or deaths (total numbers and per capita)?
- What factors influenced the number of cases or deaths?
- How have different policies (stay at home orders, public mask mandates) affected the evolution of the pandemic?
- Were there differences in the implementation of these policies between Democratic and Republican states?
- How do Democratic and Republican states compare in terms of testing?
_________

## Data

#### Covid-19 epidemiological data

We retrieved data regarding the number of confirmed cases, deaths and recoveries for each US state from Datahub ([here](https://datahub.io/core/covid-19#resource-covid-19_zip)). This data covered the time period between 2020-01-22 and 2020-07-04. It was available as a csv file, which can be found in the raw_data folder.

#### Data on testing by state

Data concerning testing by state was obtained from the Covid Tracking Project API [here](https://covidtracking.com/data/download).

#### Covid-19 policy data

Data regarding the different policies enacted in each US state, including the days when they were enacted, was retrieved from Github ([here](https://github.com/COVID19StatePolicy/SocialDistancing/blob/master/data/USstatesCov19distancingpolicy.csv)). It was available as a csv file, which can be found in the raw_data folder.

#### US political data

For data regarding the political landscape of each state in the US, we scraped [this](https://en.wikipedia.org/wiki/Political_party_strength_in_U.S._states) wikipedia page, which contained a table with all the information we needed. The code is available in notebook _number of notebook_ and the resulting table was stored as a csv file in the data folder.

#### US population data

State population and population density was obtained from [here](https://worldpopulationreview.com/state-rankings/state-densities) as a csv file and can be found in the raw_data folder
__________

## Workflow & Organization

Starting our project, we first discussed possible topics of interest. Later, we decided on the topic of Covid-19 in the U.S. and developed a Trello Board in order to get an overview of the different tasks necessary. We then allocated the tasks, which included data cleaning, the analysis of the data, as well as its visualisation and the creation of a presentation. We met regularly every day, every one to two hours, to discuss our progress and the next steps.

In that context, we worked together on the analysis and created visualizations using Tableau Public for our presentation. Yet, the heart of the analysis are the graphs using Matplotlib in the Jupyter Notebook. After this process, we created the slides, adding all the information possible that a 5 minute presentation allow. 


## Analysis
![](images/stay_at_home_orders_plot.png)


## Links

* [Trello](https://trello.com/b/vm5KySnv/week-6-project)
* [Tableau 1](https://public.tableau.com/profile/nicholas5299#!/vizhome/Week6Project_15941277490120/PopulationdensitywithinthestatesoftheUSAincorrelationwithconfirmedcasesofCovid-19)
* [Tableau 2](https://public.tableau.com/profile/nicholas5299#!/vizhome/LengthsofpolicyWeek6/Blatt1)
* [Presentation](https://docs.google.com/presentation/d/18exl3zWcM4C_qBaOxa7t_OlXZhz9xOK7Gt3vN9Uxxew/edit#slide=id.gc6f9e470d_0_0)
