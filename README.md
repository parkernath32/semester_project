# A Python Code for Retrieving Rainfall at a given location from Gridded Rainfall products
## Nathaniel Parker, KSU Dept. of Agronomy, Manhattan, KS


## Motivation
Rainfall is the main source of water for plants, animals and humans and doubles as the input variable in the soil water balance. Accurate rainfall measurement is important for monitoring environmental events such as drought and flooding. The stardard technique for rainfall measurement is rain gauge. However, it only gives a point measurement for the location it is installed and cannot give readings for ugauged locations. Radars and satellites give rainfall measurements over a large area but are often prone to errors because they do not directly measure rainfall but instead infer rainfall from signal reflectivity. As a result, the use of multi-sensor gridded rainfall products have proven useful in getting rainfall on a large spatial scale. Multi-sensor gridded rainfall products combine rainfall measurements from rain gauge, radars and satellites into one rainfall data (in grids) over a large area. Although weather-monitoring agencies such as the National Weather Service have made it easy to download rainfall data through their website, it is often complicated to retrieve point level rainfall measurements for any given location from gridded products as it often requires a great knowledge in Geographic Information Systems (GIS). Also, the data is usually not cleaned and contain missing values. There is therefore a need to create a simplified code for retrieving point level rainfall data from gridded products to aid decision-making. The code created here is compatible with the multi-sensor gridded rainfall products from the National Weather Service and require the latitude and longitude of the location of interest as the only input. Although the code runs with a single raster map, it is can be easily modified to process multiple maps (i.e. stacked maps). 

## Objective 
Create a python code to retrieve the rainfall measurement at a location from National Weather Service’s multi-sensor rainfall product

## Outcome 
I want to derive rainfall measurement for for a particular location in Kansas using the location's latitude and longitude . 

## Sketch
<img src="sketch.JPG"  width="500"/>