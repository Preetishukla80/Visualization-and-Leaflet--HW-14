# Visualizing Data with Leaflet

## Background

The main task of this assignment is to visualize an earthquake data set.
United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Technology used in developing this web application is as follows:

**leaflet.js**

**HTML/CSS/Bootstrap/Javascript**

**GeoJSON**


### Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

The first task is to visualize an earthquake data set which we can get from [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)page. We can pick a dataset to visualise it.On clicking the data set we will be given a JSON representation of that data. We will be using the URL of this JSON to pull in the data for our visualization.

![3-Data](Images/3-Data.png)


![4-JSON](Images/4-JSON.png)

2. **Importing & Visualizing the Data**

   CreateD a map using Leaflet that plots all of the earthquakes from our data set based on their longitude and latitude.

   * Our data markers reflects the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes appears larger and darker in color.

   * It Includes popups which provide additional information about the earthquake when a marker is clicked.

   * Created a legend which provides context for our map data.

   





