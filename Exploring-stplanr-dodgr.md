# Exploring stplanr (and dodgr)

## Summary

## Introduction
It's been nearly a year since I wrote my post on geospatial analyses in R as an alternative to my workflow in Python. Unfortunately, I was simply not doing much geospatial analysis in this time and the motivation behind the posts dried up. In the last month, I have had a couple of geospatial projects start up in R and spurring the desire to finish this planned series! The series will take a slightly different turn to expected - in that, I will mainly explore the different capabilities of stplanr (and dodgr) and compare them to the functionality provided by osmnx. 

### Expectations from python
The full functionality of osmnx is listed [here](https://osmnx.readthedocs.io/en/stable/) with the analysis (and visualisation) features listed in the table below. The list is pretty extensive and it's one of the main reasons why I've kept to the Python ecosystem for my geospatial analytics so far. 

|osmnx modules                        | description |
|-------------------------------------| ------------|
|osmnx.bearing module| Calculate graph edge bearings.|
|osmnx.boundaries module| Create GeoDataFrames of place boundaries.|
|osmnx.distance module| Functions to calculate distances and find nearest node/edge(s) to point(s).|
|osmnx.downloader module| Interact with the OSM APIs.|
|osmnx.elevation module| Get node elevations and calculate edge grades.
|osmnx.folium module| Create leaflet web maps via folium.|
|osmnx.footprints module|Download and plot footprints from OpenStreetMap.|
|osmnx.graph module|Graph creation functions.
|osmnx.io module|Serialize graphs to/from files on disk.|
|osmnx.plot module|Plot spatial geometries, street networks, and routes.|
|osmnx.pois module|Download points of interests (POIs) from OpenStreetMap.
|osmnx.projection module|Project spatial geometries and street networks.|
|osmnx.simplification module |Simplify, correct, and consolidate network topology.
|osmnx.speed module|Calculate graph edge speeds and travel times.
|osmnx.stats module|Calculate graph-theoretic network measures.
|osmnx.truncate module|Truncate graph by distance, bounding box, or polygon.
