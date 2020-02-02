# PLUTO Data Challenge

### img
contains the static maps generated from the choroplethNYC.py. Please see the [jupyter notebook](https://github.com/td928/pluto-data-challenge/blob/master/script/pluto_datachallenge_final.ipynb) for more details about those maps. Dr.Bianco's choroplethNYC.py [repo](https://github.com/fedhere/choroplethNYC). 


### pluto_viz
contains the Python script used to set up the [Bokeh web applicaton](https://vast-everglades-01302.herokuapp.com/pluto_viz) for interactive mapping. The application is deployed with Heroku. It also contains the requirement file and profile for deploying on Heroku.


### script
__choroplethNYC.py__ Dr.Bianco's code for creating New York City choropleth.

__pluto_datachallenge_final.ipynb__ is the notebook used to generate most of the answers to the challenge questions and also where the static maps were generated.


### DU_pluto_datachallenge_answers.pdf
has the written answers to the questions from the challenge. 


### pluto_datachallenge_subset.csv
is the original dataset.


## NOTE
The nyc_mappluto_20v1_shp is necessary to run part of the jupyter notebook __pluto_datachallenge_final.ipynb__. It is however omitted from the repo since the shapefile size exceeds the 100MB limits on github. You can find the same shapefiels on the city planning [website](https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page).