# Subway Lines
Geometry Type: polyline<br><br>![image](https://github.com/CityOfNewYork/nyc-geo-metadata/blob/master/Images/SubwayLines.PNG)

### Table of Contents<br><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**1. Identification**](#1-identification)<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**2. Data Quality and Specifications**](#2-data-quality-and-specifications)<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[**3. Attribute Information**](#3-attribute-information)<br><br>
## 1. Identification
---------------------------------------------
|     |     |
| --- | --- |
**Purpose** |The subway line layer may be used to assist with routing. 
**Description** |Line representing NYC Transit Subway Lines. Lines are optimized for cartographic representation in web applications. 
**Source(s)** |Metropolitain Transit Authority (MTA) website
**Publication Dates** |**Data**: 09/13/2010<br>**Last Update**: 1/5/2017<br>**Metadata**: 1/5/2017<br>**Update Frequency**: As needed
**Available Formats** |Shapefile. Additional data formats are available for download on the [NYC Open Data Portal](https://data.cityofnewyork.us/Transportation/Subway-Lines/3qz8-muuu).
**Use Limitations** |Open Data policies and restrictions apply. See [Terms of Use](http://www.nyc.gov/html/data/terms.html)
**Access Rights** |Public
**Contact Information** |**Name**: Colin Reilly, Director GIS Division, Department of Information Technology and Telecommunication (DOITT)<br>**Email**: creilly@doitt.nyc.gov
**Links** |https://data.cityofnewyork.us/Transportation/Subway-Lines/3qz8-muuu
**Tags** |mta, metropolitan transportation authority, jobs and economic mobility, location, map, cartography, basemap, transit, transportation, train, subway, travel, entrance, station
## 2. Data Quality and Specifications
---------------------------------------------
|     |     |
| --- | --- |
**Horizontal Coordinate System** |New York State Plane Coordinates, Long Island East Zone, NAD83, US foot
**Resolution** |NA
**Spatial Coverage** |New York City, NY
**Temporal Coverage** |Data is current as of last update date.
**Positional Accuracy** |Position of lines are optimized for cartography and therefore are approximate. 
**Features Captured** |Includes all active subway lines as provided by the MTA. 
**Features Excluded** |Proposed or under construction features are not included in the dataset. 
**Capture and Update Notes** |Subway features are based on data provided by the MTA. Updates are made as new subway lines, entrances, or stations are opened. 
## 3. Attribute Information
---------------------------------------------
| Attribute | Description | Field Type | Sensitive Field (Y/N) | Notes| 
|------------ | ------------- | -------- | ----------- | ----------|
| ID | Segment of subway ID | double | 
| RT_Symbol | Value used for symbology of subway lines.  | text | 
| Name | Name of subway line | text | 
| URL | URL link to MTA | text | 