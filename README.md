
# Assignment 04

# Project Proposal

![http://www.pratt.edu/tiny_mce/plugins/imagemanager/files/Light_brown_blue22.jpg](http://www.pratt.edu/tiny_mce/plugins/imagemanager/files/Light_brown_blue22.jpg)

The **purpose of this project** is to have some **well-written** and **well-documented code** in a GitHub repository that illustrates you can write some Python code. This project is for **your** Portfolio, so pick something you are **interested in** or that's **useful** (either in some professional work or automating some task). [Learn how the project is evaluated (rubric)](https://github.com/pratt-savi-810/pratt-savi-810-2020-03-project).


#### Project Routes

There's a couple of routes you can go;

1. **Creating a Tool to Automate a Task** - usually for some task automation, less an analysis, more data engineering. 
2. **Performing Data Analysis to Answer a Research Question** - this type of project requires plots and data insights. 

Since writing the code is the challenging part. Do not think about this in scope of a normal project. **Keep your scope focused!** Keep it limited in functionality and if you finish early, you can add more features. I've seen students go down some pretty deep rabbit holes and emerge with some very disorganized projects. You could have only 30 lines of code or so, and still have a great project so long as the code is well written and the doc's are informative and it has some functionality that's useful in some capacity. Most likely someone such as a hiring manager will only glance at your Repository, so you want it to be organized and clean and very clear as to its purpose. 



## Assignment 04 Submission
You will **Fork** and **Clone this Repo** and **edit this README.md Markdown file**. This is your submission, just the link to your forked Repo and edited README.md file. This project should be the edited version of this README.md (**Markdown**) file. 

#### Learn more about [Markdown](https://www.markdownguide.org/). 

Most code editors allow editing of Markdown files, some recommended editors are;

* [Atom](https://atom.io/)
* [MacDown](https://macdown.uranusjr.com/)
* [Visual Studio Code (VS Code)](https://code.visualstudio.com/)
* [StackEdit (edit in-browser)](https://stackedit.io/)
* [Dillinger (edit in-browser)](https://dillinger.io/)
* You can even edit inside of [GitHub](https://github.com/). 

Your Assignment 04 Deliverables are listed below:


# Deliverables

You should edit the following items in-line and substitute any of the provided text with your response below for your README.md Assignment 04 submission. 


---

## Executive Summary

A _brief description_ of your final project idea. 

- **Why** are you doing this project? 
	- Amid the Novel Coronavirus pandemic, I would like to provide a clear presentation of the differt COVID-19 outbreak responses, specifically South Korea and the U.S., and their outcomes
    
- **How** do you imagine you'll accomplish this project? 
	- Collect COVID-19 data from both US government and South Korea government
	- Organize and modify collected data
	- Create interactive maps, charts, timelines
	- Compare and contrast
	- Analyze 

- Is this a project **Creating a Tool to Automate a Task** or **Performing Data Analysis to Answer a Research Questio**? 
	- This project will focus more on data analysis rather than task automation.

This should be a paragraph or so and provide a _high-level overview_ of your project. Again this is a summary, so think of this as the "Elevator Pitch". 



## Background

A more **detailed background** of your project, please include any information that would be useful for understanding the context of the project. This can be as long or short as you'd like. 

> I will put into a paragraph by Wednesday



## Resources
List any possible articles, resources or analysis or anything useful and include links and perhaps annotate a sentence as to the key findings of this resource. Or if you cannot find any resources please mention. 

#### Resources List

##### U.S.
* Johns Hopkins University & Medicine Coronavirus Resource Center 
	- https://coronavirus.jhu.edu/map.html 
	- https://github.com/CSSEGISandData/COVID-19
	- description

* Humanitarian Data Exchange
	- https://data.humdata.org/event/covid-19
	- description

* Coronavirus in the US, New York Times 
	- https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html 
	- https://github.com/nytimes/covid-19-data
	- description
    
* Coronavirus Disease (COVID-19) - Statistics and Research, Our World in Data 
	- https://ourworldindata.org/coronavirus 
	- description 
    
* Live Tracker: How many coronavirus cases have been reported in each U.S. state?, POLUTICO 
	- https://www.politico.com/interactives/2020/coronavirus-testing-by-state-chart-of-new-cases/ 
	- description
    
* The COVID Tracking Project 
	- https://covidtracking.com/ 
	- description 

* Our World in Data Github
	- https://github.com/owid/covid-19-data/tree/master/public/data 
	- description 


##### South Korea
* Korean Centers for Disease Control and Prevention 
	- http://www.cdc.go.kr/cdc/ 
	- http://ncov.mohw.go.kr/ 
	- description
    
* Coronavirus Tracker 
	- https://coronapath.info/index.html 
	- description
    
* Corona Map (Contact Tracing Site) 
	- http://coronamap.site/ 
	- description
    
* OpenStreetMap (Korean States)
	- https://www.openstreetmap.org/relation/307756#map=6/35.818/128.260 
	- description
 
 
## Input Data 

#### Data Sources List 
List any possible data including links with any input data sources you'll be using. 

* State Historical Data, Covid Tracking Project 
	- https://covidtracking.com/api/v1/states/daily.csv 
	- description
    
* US Historical Data, Covid Tracking Project 
	- https://covidtracking.com/api/v1/us/daily.csv 
	- description 
    
* Complete COVID-19 dataset, Our World in Data
	- https://covid.ourworldindata.org/data/owid-covid-data.csv
	- description




https://www.cdc.go.kr/board/board.es?mid=a20501000000&bid=0015

#### Data Wish List
List and describe any type of data you'd like to include but had difficulty tracking down. 

* Data Wish List Item A - description
* Data Wish List Item B - description



## Technical Requirements

#### Python Libraries
List any Python libraries you think you may need. Desribe what you may use them for. 

* from datetime import datetime
	- work with dates as date objects (manipulate dates)

* import matplotlib.pyplot as plt
	- create static, animated, and interactive data visualizations
    
* import seaborn as sns
	- based on Matplotlib, provides a high-level interface for data visualization

* import numpy as np 
	- scientific computing for multidimentional array objects

* import pandas as pd 
	- create data structures, perform data analysis and manipulation

* import geopandas as gpd / from geopandas import GeoDataFrame
	- work with geospatial data and perform spatial/geometric operations (done by shapely) on geometric types
	- manage projections, geocode, geoprocess

* from shapely.geometry import Point/MultiPoiny/LineString/MultiLineString/Polygon/etc
	-
    
* import folium
	- 

* from geopy.geocoders import Nominatim
	- locate the coordinates of addresses, cities, countires, and landmarks across the globe
	- Nominatim is a search engine for OpenStreetMap data
    
* import networkx as nx
	-

* import osmnx as ox
	- retrieve, model, analyze, and visualize street networks from OpenStreetMap
	- download spatial geometries and model, project, visualize, and analyze street networks and other spatial data from OSM's APIs
    


#### Library Wish List
Also note any libraries or functionality that you may need that you're not sure exists. Try your best to articulate this in words. This will be helpful if I can provide any libraries to suggest for use in the project. 

* Python Library Wish List Item A - description of desired functionality
* Python Library Wish List Item B - description of desired functionality



## Measuring Success: 

- How will you measure your project's sucess?
	- Is there some metric you'd hope to generate from your project.  	 
	- Is there some plot or visualization that will be generated? 

	- Is some manual task now fully automated? 



## Project Execution Plan Outline
Please include a short outline describing the steps you'd imagine going through. 

Could be as simple as;

```
- Background Research 
	- Spend some time researching the topic

- Data Collection
	- Spend time collecting and looking for additional data
	-
- Exploratory Data Analysis
	- Summarize the input data, plot and examine any columns that may be useful. 

- Data Processing
	- A couple of steps that may be needed to Process your data. 

- Results and Conclusion 
	- Key findings
	- Was your Project Successful. 
	- Generate Assumptions and Limitations. 
```
