
#Impact Assessment 
Create impact metric based on various inputs 
CoS-IT-FloWS: Flood Impact Assessment
Links & Badges
CoS-IT-FloWS Documentation
License
Table of Contents
About
Overview
Key Features
Tech Stack
Usage
License
Help and Support
##About
This repository serves as the public source code repository for the Impact Assessment of Flood Forecasting System. The system integrates various data inputs to assess the impact of flooding on different geographical features, including buildings and road networks.


##Overview
The Flood Forecasting System in CoS-IT-FloWS utilizes multiple inputs to assess the impact of floods on different areas. The system incorporates data on the impacted area, open buildings, and road networks ,population, land use land cover classes to provide a comprehensive analysis of the potential impact of flooding events.

##Key Features
Impacted Area Assessment:

Utilizes DEM file for elevation data to create shapefiles based on elevation thresholds.
Analysis of open buildings data to determine the number of buildings impacted by floods.
Integration of road network data to assess the impact on transportation infrastructure
Calculation of population affected by flooding
Analysis of impacted agriculture area by flooding from Land use land cover class data

#Tech Stack
Python for data processing
GIS tools for spatial analysis

#Usage
To use the Flood Forecasting System Impact Assessment, follow these steps for metrics:

##Input Data
1.Impacted Area: Load the DEM file to create shapefiles based on elevation thresholds 
2.Open Buildings: Download open buildings data and convert it to shapefiles for analysis.
3.Road Network: Download road data from OpenStreetMap and convert it to shapefiles.
4.Affected People : Download population data as tif file from World pop data
5.Impacted Agriculture land: Download 2020 LULC data and extract agriculture area

##Processing Steps:

1.Calculate the area impacted by flooding based on elevation thresholds.
2.Count the number of buildings within each panchayat affected by flooding.
3.Assess the total length of impacted roads under specific elevation thresholds.
4.Count number of people directly affected in each panchayat under different elevation thresholds
5.Calculate the agriculture area impacted under different elevation threshold

##Output:

Generate tables summarizing the impacted areas, buildings, and road lengths,population and impacted agricultural area for each panchayat.

##License
 CoS-IT-FloWS is released under the MIT License. See the License file for more information.

##Help and Support
For any questions, feedback, or support, please contact us at team@equinoct.com. You can also raise an issue in the issue tracker for assistance.

