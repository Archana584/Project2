# Project2
# Tools Used:  Jupiter NoteBook /Python, JavaScript, HTML, MongoDB
### Team Members:
Archana, Kristine, Jacky, Allison, Carol

# Chapel Hill Crash Analysis Project
### Analyzed data from more than 16,500 North Carolina Police reported bicycle-motor vehicle and pedestrian-motor vehicle crashes for the years 1997 through 2013. Created visualized Accident map, Interactive Bike Chart, Interactive Pedestrian Chart.


## DATA ANALYSIS-Questions
1. Which location is more vulnerabale for Bicycle and/or Pedestrain Accident?
2. What are Bicycle and/or Pedestrain Accident factor?

## Datasets Used:
### Bicycle Crashes:
This data set maps the locations of crashes involving bicyclists in the Chapel Hill Region of North Carolina.The data comes from police-reported bicycle-motor vehicle and pedestrian-motor vehicle collisions that occurred on the public roadway network, public vehicular areas and private properties (if reported) from January 2007 through December 2013. Users are able to click and view information specific to each crash. Information for each crash includes: County, City, Crash Date, Crash Day, Crash Group, Crash Location, Crash Time, Crash Severity, Bike/Pedestrian Age Group, Bike/Pedestrian Alcohol Detected, Bike Direction, Bike/Pedestrian Injury, Bike/Pedestrian Position, Bike/Pedestrian Race, Bike/Pedestrian Sex, Ambulance Response, Driver Age Group, Driver Estimated Speed, Speed Limit, Driver Alcohol Detected, Driver Injury, Driver Race, Driver Sex, Driver Vehicle Type, Hit and Run, Development, Light Condition, Locality, Number of Lanes, Road Characteristics/Class/Condition/Configuration, Road Defects/Features, Traffic Control, Crash Type, and/or Weather. Crash identification numbers have been removed from the data for protection of privacy. Crash records were obtained NCDOT’s Traffic Engineering Accident Analysis System (TEAAS).
From <https://catalog.data.gov/dataset/bicycle-crashes>
 
### Pedestrian Crashes:
This data set maps the locations of crashes involving pedestrians in the Chapel Hill Region of North Carolina.The data comes from police-reported bicycle-motor vehicle and pedestrian-motor vehicle collisions that occurred on the public roadway network, public vehicular areas and private properties (if reported) from January 2007 through December 2013. Users are able to click and view information specific to each crash. Information for each crash includes: County, City, Crash Date, Crash Day, Crash Group, Crash Location, Crash Time, Crash Severity, Bike/Pedestrian Age Group, Bike/Pedestrian Alcohol Detected, Bike Direction, Bike/Pedestrian Injury, Bike/Pedestrian Position, Bike/Pedestrian Race, Bike/Pedestrian Sex, Ambulance Response, Driver Age Group, Driver Estimated Speed, Speed Limit, Driver Alcohol Detected, Driver Injury, Driver Race, Driver Sex, Driver Vehicle Type, Hit and Run, Development, Light Condition, Locality, Number of Lanes, Road Characteristics/Class/Condition/Configuration, Road Defects/Features, Traffic Control, Crash Type, and/or Weather. Crash identification numbers have been removed from the data for protection of privacy. Crash records were obtained NCDOT’s Traffic Engineering Accident Analysis System (TEAAS).
From <https://catalog.data.gov/dataset/pedestrian-crashes>

## Breakdown of Tasks:
1. Get dataset from sources.
2. Cleaned data.
3. Data abbreviations from json:
    Severity = crsh_sevri
    Road conditions = rd_conditi
    Drivers age group = drvrage_gr
    Speed = drvr_estsp
    Intoxication (driver) = drvr_alc_d
    Intoxication (biker) = crashalcoh
4. Getting data from pedestrian and bike json  into database - Mongodb
5. Markers  - leaflet map with generic markers for a starting place. Leaflet layers - like in the bike stations -- layers for pedestrian and bicycle - overlay for factors that are similar and different based on crash data
6. Data wrangling - skeleton of D3 information / JSON unpacking
7. Analyze the dataset.
8. Extra JS Library: JQuery and FancyBox (part of HTML CSS)
9. Visualizations:
  Compare Location, severity of injury based on accident, time of year, date/time of crash, road conditions (weather and type of road),
  Map - based  on accidents themselves - placement on map
  Icons for bike and pedestrians / icons change size based on amount of accidents - options for clusters or icons
  Color for severity -- if concentrated then you could use clusters
  Custom D3 
  Factors on Y axis - conditional: weather, time of day, time of year
  Accident data on X axis- number of accidents  - pedestrian / bikes / total
  Web page 
  Navbar that provides links to the 2 types of maps: Geographic map of locations and D3 comparative map showing factors

## Obervation.
![GitHub Logo](/Project2/blob/master/Project2/img/basemap_v2.png)

15 people were killed as a result of bicycle and pedestrian accidents from 2007-2013!
[GitHub]https://cbwittig.github.io/Project2/index.html)
![GitHub Logo](/Bike_ages.png)
![GitHub Logo](/img/basemap_v2.png)
![GitHub Logo](/blob/master/Project2/img/basemap_v2.png)

! https://github.com/Archana584/Project2/blob/master/Project2/img/basemap_v2.png

