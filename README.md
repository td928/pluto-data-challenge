# PLUTO Data Challenge

### img
contains the static maps generated from the choroplethNYC.py. Please see the [jupyter notebook](https://github.com/td928/pluto-data-challenge/blob/master/script/pluto_datachallenge_final.ipynb) for more details about those maps. The original code came from Dr.Federica Bianco. Please see more at the NOTE section of this README. 



### pluto_viz
contains the Python script used to set up the [Bokeh web applicaton](https://vast-everglades-01302.herokuapp.com/pluto_viz) for interactive mapping. The application is deployed with Heroku. It also contains the requirement file and profile for deploying on Heroku.

There are few features for this app: you can adjust the slider at the bottom of the map to select an assessed total value, then the map will be updated to include only BBL has valuation above the selected value. You can also choose the criteria (number of residential units, number of buildings, and total lot area) by which the choropleth is generated. You can also hover over individual lot and it will show information such as BBL, assessed total value, number of residential units, total lot area, and number of buildings.



### script
__choroplethNYC.py__ Dr.Bianco's code for creating New York City choropleth.

__pluto_datachallenge_final.ipynb__ is the notebook used to generate most of the answers to the challenge questions and also where the static maps were generated.



### DU_pluto_datachallenge_answers.pdf
has the written answers to the questions from the challenge. 



### pluto_datachallenge_subset.csv
is the original dataset.



## NOTE
Dr.Bianco's choroplethNYC.py [repo](https://github.com/fedhere/choroplethNYC).

The Bokeh application was largely based on and borrowed codes extensively from this [blog post](https://towardsdatascience.com/how-to-create-an-interactive-geographic-map-using-python-and-bokeh-12981ca0b567) by Jim King. 


The nyc_mappluto_20v1_shp is necessary to run part of the jupyter notebook __pluto_datachallenge_final.ipynb__. It is however omitted from the repo since the shapefile size exceeds the 100MB limits on github. You can find the same shapefiels on the city planning [website](https://www1.nyc.gov/site/planning/data-maps/open-data/dwn-pluto-mappluto.page).


