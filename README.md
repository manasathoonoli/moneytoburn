# moneytoburn


The visualization tool was realized by coding in Python in Jupyter Notebook. A heat-map of world wealth distribution was created using matplotlib, geopandas, and world wealth data. NASA's global pollution image was overlaid on the world wealth heat-map to obtain the visual.



The major problem we faced was to generate a world wealth heat-map. Getting the geometry pattern values to generate a world map required some digging into matplotlib's ability to generate a world map and then a heat-map. The other hurdle that we faced was in trying to get the heat-map overlaid on NASA's global pollution map, which required some trial and error in figuring out the dimensions of the map.

We programmatically overlaid a map of pollution (concentration of nitrogen dioxide in the troposphere averaged over 2014) on a map of wealth (mean wealth per adult in each country for 2019 in US dollars) to show where each are concentrated to let the viewer come to conclusions on their own by seeing where concentrations of wealth and pollution are.

This code was developed for the SpaceApps 2020 Challenge for the "Universal Event" location. The challenge that this code was submitted for is "Better Together."
