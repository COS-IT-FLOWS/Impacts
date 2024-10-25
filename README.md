
# Impact Assessment 
Assess the impact of a flood event based on river water level 
## CoS-IT-FloWS: Flood Impact Assessment

## Table of Contents
* Overview 
* Key features
- Tech Stack
* Usage
* License
* Help and Support

## Overview

The Flood Forecasting System in CoS-IT-FloWS utilizes multiple inputs to assess the impact of floods on different areas. The system incorporates data on the impacted area, buildings, road networks, population, and land use land cover to provide a comprehensive analysis of the potential impact of flood events.

## Key Features

* Utilizes DEM file for elevation data to create shapefiles based on elevation thresholds.
* Analysis of buildings data to determine the number of buildings impacted by floods.
* Integration of road network data to assess the impact on transportation infrastructure
* Calculation of population affected by flooding
* Calculate the agriculture area affected by flooding from Land use land cover class data

## Tech Stack
+ Python for data processing
+ GIS tools for spatial analysis

## Usage
To use the Flood Forecasting System Impact Assessment, follow these steps for metrics:

### Input Data
1. Impacted Area: Load the DEM file to create shapefiles based on elevation thresholds 
2. Buildings: Download open buildings data and convert it to shapefiles for analysis.
3. Road Network: Download road data from OpenStreetMap and convert it to shapefiles.
4. Affected People : Download population data as tif file from World pop data
5. Impacted Agriculture land: Download 2020 LULC data and extract agriculture area

### Processing Steps:

1. Calculate the area impacted by flooding based on flood thresholds.
2. Count the number of buildings within each panchayat affected by flooding.
3. Assess the total length of roads impacted under specific flood thresholds.
4. Count number of people directly affected in each panchayat under different flood thresholds
5. Calculate the agriculture area impacted under different flood threshold

### Output:

Generate tables summarizing the impacted areas, buildings, and road lengths,population and impacted agricultural area for each panchayat.

## License
 CoS-IT-FloWS is released under the MIT License. See the License file for more information.

## Help and Support
For any questions, feedback, or support, please contact us at team@equinoct.com. You can also raise an issue in the issue tracker for assistance.

