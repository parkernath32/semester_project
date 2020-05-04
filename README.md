# A Python Code for Retrieving Rainfall at a given location from Gridded Rainfall products
#### Name: Nathaniel Parker
#### Research Area: Soil water Processes
#### Institution: Agronomy Dept., Kansas State Univerity 
#### Semester: Spring 2020

## Motivation
Rainfall is the main source of water for plants, animals and humans and doubles as the input variable in the soil water balance. Accurate rainfall measurement is important for monitoring environmental events such as drought and flooding. The stardard technique for rainfall measurement is rain gauge. However, it only gives a point measurement for the location it is installed and cannot give readings for ugauged locations. Radars and satellites give rainfall measurements over a large area but are often prone to errors because they do not directly measure rainfall but instead infer rainfall from signal reflectivity (Hong et al., 2013; Brocca et al., 2019). Owing to the limitations of the individual techniques, the use of multi-sensor gridded rainfall products have proven to be a useful approach in getting fairly accurate rainfall data on a large spatial scale (Lawrence et al., 2003). Multi-sensor gridded rainfall products is derived by combining rainfall measurements from rain gauge, radars and satellites into a single gridded rainfall data over a large area. 

Although weather-monitoring agencies such as the National Weather Service have made it easy to download gridded rainfall data through their website, it is not straight forward and often complicated to retrieve a point rainfall measurement from gridded poducts at any given location since it requires great experience in processing data with Geographic Information Systems (GIS) softwares. There is therefore a need to create a simplified python code for retrieving point level rainfall data from gridded products to aid decision-making. The code created here is compatible with the multi-sensor gridded rainfall products from the National Weather Service and require the latitude and longitude of the location of interest as the only input. 
## Objective 
Create a python code for retrieving rainfall measurements at a given location from the National Weather Service’s multi-sensor rainfall product

## Methodology
The data for this project was obtained from the National Weather Service's (NWS) multi-sensor gridded rainfall product. NWS have gridded rainfall products in hourly, daily, monthly, and yearly time intervals accessible via https://water.weather.gov/precip/download.php. 
Here, a single rainfall map (in GeoTiff format) for the last 365 days (i.e. 365 days before April 26, 2020) for contiguous USA from the National Weather Service's (NWS) multi-sensor gridded rainfall product was used as an example data file to set up this code. However, the code should be compatible with GeoTiff files from other sources. In addition, the code can be easily modified to process multiple maps (i.e. stacked maps).

The steps is outlined in the chart below.

## Sketch
<img src="sketch.JPG"  width="500"/>


## Outcome 
I want to derive rainfall measurement for for a particular location in Kansas using the location's latitude and longitude. 

## References
Brocca, L., Filippucci, P., Hahn, S., Ciabatta, L., Massari, C., Camici, S., Schüller, L., Bojkov, B. and Wagner, W., 2019. SM2RAIN-ASCAT (2007–2018): Global daily satellite rainfall from ASCAT soil moisture. Earth Syst. Sci. Data Discuss, pp.1-31.

Hong, Y., Adhikari, P. and Gourley, J.J., 2013. Flash flood. Encyclopedia of natural hazards, pp.324-325.

Lawrence, B.A., Shebsovich, M.I., Glaudemans, M.J. and Tilles, P.S., 2003, February. Enhancing precipitation estimation capabilities at National Weather Service field offices using multi-sensor precipitation data mosaics. In Preprints, 19th Conf. on IIPS, Long Beach, CA, Amer. Meteor. Soc (Vol. 15).