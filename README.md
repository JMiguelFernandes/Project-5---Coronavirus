# Project 6 - Visualizing Real World Data

Project by Shelley Obery, Nicholas Gotzens and João Fernandes

## Project Description

This project is part of the IronHack Data Analytics Bootcamp and its goal is to practice creating and interpreting different types of visualizations using real world data as well as statistical analysis. Our team decided to work on the topic of Covid-19 in the USA.
In that coherence we analyzed if there is a correlation between the number of Covid-19 cases, as well as deaths, and the political landscape of the different U.S. states. In addition, the population density and laws at federal level were analysed.

## Questions & Hypotheses

In the beginning of the project, the general question arose, if the U.S. political landscape is affecting the number of outbreaks and deaths of the Covid-19 pandemic. As political ruling should'nt have a good or bad influence on the evolvment of pandemics, we decided to start with the null hypotheses that political parties dont affect the numbers of Covid-19 cases and deaths. To further supplement our analysis, we also included other factors to our analysis, like lockdown policies, mask policies and population density.

## Data

#### Covid-19 epidemiological data

We retrieved data regarding the number of confirmed cases, deaths and recoveries for each US state from Datahub ([here](https://datahub.io/core/covid-19#resource-covid-19_zip)). This data covered the time period between 2020-01-22 and 2020-07-04. It was available as a csv file, which can be found in the raw_data folder.

#### Covid-19 policy data

Data regarding the different policies enacted in each US state, including the days when they were enacted, was retrieved from Github ([here](https://github.com/COVID19StatePolicy/SocialDistancing/blob/master/data/USstatesCov19distancingpolicy.csv)). It was available as a csv file, which can be found in the raw_data folder.

#### US political data

For data regarding the political landscape of each state in the US, we scraped [this](https://en.wikipedia.org/wiki/Political_party_strength_in_U.S._states) wikipedia page, which contained a table with all the information we needed. The code is available in notebook _number of notebook_ and the resulting table was stored as a csv file in the data folder.

#### US population data

State population and population density was obtained from [here] (https://worldpopulationreview.com/state-rankings/state-densities) as a csv file and can be found in the raw_data folder


## Workflow & Organization

Starting our project, we first discussed possible topics of interest. Later, we decided on the topic of Covid-19 in the U.S. and developed a Trello Board in order to get an overview of the different tasks neccerssary. After allocating the tasks, which included data cleaning, the analysis of the data, as well as its visualisation and the creation of a presentation. 

In that context, we worked together on the analysis and created visualizations using Tableau Public for our presentation. Yet, the heart of the analysis are the graphs using Matplotlib in the Jupyter Notebook. After this process, we created the slides, adding all the information possible that a 5 minute presentation allow. 


## Links

[Trello](https://trello.com/b/vm5KySnv/week-6-project)
[Tableau](https://public.tableau.com/profile/nicholas5299#!/vizhome/Week6Project_15941277490120/PopulationdensitywithinthestatesoftheUSAincorrelationwithconfirmedcasesofCovid-19)
[Tableau](https://public.tableau.com/profile/nicholas5299#!/vizhome/LengthsofpolicyWeek6/Blatt1)

