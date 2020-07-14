# Dory
Exploration of inland shipping in Western-Europe. In this study we'll dive into location data of barges to explore their speeds. This information could be used to enhance estimations of arrival times which contributes to the reliability and therefore reputation of the transportation type.

# Installation
Runs with python, pandas, numpy, matplotlib, seaborn and arc.gis

# Data
Data is based on barge and location information gather over the month april in 2020. Following data is used for exploration

shipId: Reference of barges in local system
Speed: speed of barge on certain point in km/ph
Course: course of barge in on certain point based on 360 degrees radius
Location: Location name where signal of barge was send
Code: Code of location
Type: Type of location relevant to barging. For instance, port, terminal or waterway
Latitude: latitude of central point of location
Longitutde: longitutde of central point of location
Encodedpolyline: geofence of location
capacityton: capacity of cargo barge can carry in tonnage
length_m: Length of barge in meter
width_m: Width of barge in meter

# Useful tools
Lat and long where plot using <a href=https://developers.arcgis.com/python/>arcgis</a>
Polylines can be decoded with<a href=https://developers.google.com/maps/documentation/utilities/polylineutility>polylineutility</a>
