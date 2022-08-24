Mapping Earthquakes
===================

Overview
--------

The purpose for this project was to extract data within a json format and
visualize it by utilizing the JavaScript libraries D3 and LeafLet. Assisting a
non-profit organization whose mission is to report data-backed stories about
natural disasters around the world has provided the opportunity to analyze their
data and build data visualizations with interactive features. This project
incorporates JavaScript and the calling of APIs to visualize gathered earthquake
data.

## Resources Data Sources: -
- https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson -
- https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
- https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson

Software: - MapBox APIs - D3 - Leaflet \#\# Summary MapBox, a company that
providees custom maps for websites and applications, supplies APIs that are used
to create interactive maps. Incorporating these APIs in combination with the
Leaflet JavaScript library, enables easy and highly customizable map creation.
The earthquake data was collected from the U.S. Geological Survey website
containing data from earthquakes worldwide over the past week. This data was
extracted and loaded as a GeoJSON file, a type of JSON data specifically
designed to hold geographical information. The final map contained the
earthquake data represented as circular markers with their size and color
corresponding to the magnitude of the earthquake. Each marker also has a popup
that displays the magnitude and location of the earthquake. The map also
contains multiple viewing layers (i.e. satellite, street, and night) as well as
the ability to toggle visibility of the earthquake visualizations.

![1](./images/1.png)

## Project Process \#\#\# (1) Add Tectonic Plates 
====================================================

![Tectonic](./images/2.png)

### (2) Add Major Earthquakes

![major](./images/3.png)

### (3) Add Third Layer The two pictures above have showed that the third
layer, dark mode, was successfully added to the base map.  
Finally, here is the screenshot of all jobs done.

![final](./images/4.png)

## Challenge Summary Visualizing the relatioship between the distance of
earthquakes and tectonic plates can be seriously powerful when trying to predict
where another earthquake might occur. This challenge first consisted of
utilizing the JavaScript libraries D3 and Leaflet via including their respective
CDNs within script tags inside the HTML file. Leaflet was used to easily create
and customize maps, while the D3 library was used to load and manipulate data
that was originally packaged within a JSON format. Finally, this data was then
displayed onto a map as a customizable viewing option, where the user has the
ability to toggle the different data visualizations on or off.

![5](./images/5.png)
