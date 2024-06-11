# USGS Leaflet Challenge

## Overview

This project visualizes earthquake data using the USGS GeoJSON feed and the Leaflet.js library. The goal is to create an interactive map that displays earthquake occurrences based on their magnitude and depth.

## Part 1: Create the Earthquake Visualization

### Steps to Complete

1. **Get Your Dataset**
   - The USGS provides earthquake data in various formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and choose a dataset to visualize.
   - For example, selecting "All Earthquakes from the Past 7 Days" will provide a JSON representation of the data.

2. **Import and Visualize the Data**
   - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
   - Data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Higher magnitude earthquakes should appear larger, and earthquakes with greater depth should appear darker in color.
     - **Hint:** The depth of the earthquake can be found as the third coordinate in each earthquake's data.
   - Include popups that provide additional information about the earthquake when its associated marker is clicked.
   - Create a legend to provide context for your map data.

<!-- ### Example Visualization

Your map should resemble the example below:
![Example Map](example-map.png) *(Include an example image of your map here)* -->

## Part 2: Gather and Plot More Data (Optional)

### Additional Features (Optional)
Enhance your map by plotting a second dataset to illustrate the relationship between tectonic plates and seismic activity. This part is optional and intended as a challenge to boost your skills.

1. **Plot Tectonic Plates Data**
   - Data on tectonic plates can be found at [this GitHub repository](https://github.com/fraxen/tectonicplates).

2. **Additional Enhancements**
   - Plot the tectonic plates dataset on the map alongside the earthquake data.
   - Add other base maps for users to choose from.
   - Separate each dataset into overlays that can be turned on and off independently.
   - Add layer controls to your map.

<!-- ### Example Advanced Visualization

Your enhanced map should resemble the example below:
![Advanced Example Map](advanced-example-map.png) *(Include an advanced example image of your map here)* -->
