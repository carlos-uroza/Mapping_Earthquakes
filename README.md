# Module 13 Challenge - Mapping Earthquakes

## Overview of the Project

### Purpose
The purpose of this project is to build an interactive visualization of earthquake data from the USGS. Our program takes live GeoJSON data from the USGS of both the weekly earthquake summary and the major (4.5+) earthquake feeds. The data is presented in a MapBox format with interactive overlay options for the datasets and the tectonic plate boundaries.

## Results

### Deliverable 1 - Add Tectonic Plate Data
The image below shows our map with the active tectonic plate overlay. The data for the lines are pulled from a GitHub repository featuring GeoJSON linestring data for the world's tectonic plate boundaries.
![Del 1](https://user-images.githubusercontent.com/103288980/184456176-4ac579e2-8283-459e-9edb-faa19ac0649e.PNG)

### Deliverable 2 - Add Major Earthquake Data
The image below features an overlay of the major (4.5+) earthquakes for the past 7 days. This data is pulled from the USGS' feed for  major (4.5+) earthquakes in the past 7 days. Our program styles these GeoJSON points as circle markers whose diameters' and colors' represent the earthquakes' magnitude.
![Del2](https://user-images.githubusercontent.com/103288980/184456181-23ab7a5d-7737-4457-97aa-1e325938cd80.PNG)

### Deliverable 3 - Add an Additional Map
The final map below shows an additional tile layer option for our map. In this step, we've added a dark map mode that can be selected from the overlay menu on the top right corner of the map. In total, our program features the ability to switch between 3 distinct tile layers.
![Del3](https://user-images.githubusercontent.com/103288980/184456186-119228b4-b5ae-46c9-8acb-08929446551d.PNG)

## Summary

### Recommendations
Our program would be improved by providing the user with a manner of filtering the data by date. A filter could be added using the built in filter option for the L.GeoJSON class. This would add an additional layer of interactivity that will allow customers the opportunity to narrow down the results presented on the map for a custom date or range.
