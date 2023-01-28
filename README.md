# leaflet_challenge

# Background

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. 

In this challenge, I have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.


# Level-1: Basic Visualisation

* DataSet
Earthquake data for the last 7 days is used for the visualization. The data is taken as a JSON format from the USGS, which is updated every minute.

* Visualization
Creating a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

* The visualzation includes

Data markers which reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appear larger and darker in color.

Popups that provide additional information about the earthquake when a marker is clicked.

A legend that will provide context for your map data.

<img width="1440" alt="Screenshot 2023-01-28 at 17 17 07" src="https://user-images.githubusercontent.com/111929009/215280101-f3a684e7-99c7-4b14-87b9-bb90c714f2ab.png">





# LEVEL 2: ADVANCED VISUALISATION

* Additional dataset
Tectonic plates were added in this map in order to illustrate the relationship between tectonic plates and seismic activity.

* Visualization
A base map object with 4 map layers to choose from was added
An overlay map which contains plates layer and geoJSON layer was also added.
Layer controls to our map was created.

<img width="1440" alt="Screenshot 2023-01-28 at 17 16 17" src="https://user-images.githubusercontent.com/111929009/215280128-928b01ab-604f-4992-aba8-d5f6ecde199d.png">


# TECHNOLOGIES USED:
* JAVASCRIPT 
* DS3 JS
* CSS
* HTML

# Conclusion
The final Map has 3 baseMaps: Satellite, Grayscale and Outdoors, which you can filter dynamically. Both Maps contain popups that provide additional information about the earthquake when its associated marker is clicked and a legend that will provide context for the map data.
 
