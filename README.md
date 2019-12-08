# Project2
### Team Members:
Archana, Kristine, Jacky, Allison, Carol

# Chapel Hill Crash Analysis Project
### Analyzed data from more than 16,500 North Carolina Police reported bicycle-motor vehicle and pedestrian-motor vehicle crashes for the years 1997 through 2013. Created visualized Accident map, Interactive Bike Chart, Interactive Pedestrian Chart.


## DATA ANALYSIS-Questions
1. What is the relationship between median household income, education level and ATM location/number?
2. What relationships between population density and ATM number?
3. Are there relationships between ATM use fees and demographic variables?
4. Are there significant relationships between a demographic area and the types of ATMs found in that area?
5. We wanted to examine the placement of ATM machines in today’s banking landscape.  We wanted to understand who owned them, where they were placed, and what strategies owners use to place ATM machines today.
6. Who uses them & who owns them?
7. What can we learn about ATMs?

## Datasets Used:
NYC Pedestrian/Bicycle Crash Data: https://www.policedatainitiative.org/crash-data/
Police Data Initiative Dashboard: https://www.policedatainitiative.org/datasets/#all
Open Data better API information for calls  from Chapel Hill -PL https://www.chapelhillopendata.org/explore/dataset/pedestrian-crashes-chapel-hill-region/api/
https://www.chapelhillopendata.org/explore/dataset/bicycle-crash-data-chapel-hill-region/api/

## Breakdown of Tasks:
1. Get dataset from sources.
2. Cleaned data.
3. Breakdown and analyze the dataset.
4. Compare relative numbers of ATMs and contrast that with demographic data. 
5. Examine ATMs in a given geographic area correlated with population density, and other social economic factors. 
6. Examine various types of ATMs
7. Graph using matplotlib.

## ATM Data Search Method:
Pulled 1000 random latitudes and longitudes in the Richmond region
Used Latitude and Longitude with Google’s API “near by me” to generate ATM name & street addresses
Google search had a 60 item limit
Used ATM addresses and Google’s Geo mapping to retrieve zip codes
First pull was 30 miles – 60 ATMs
Second pull was 100 3 mile radius pulls – 67 ATMs after dups
3rd pull was 200 3 mile radius pulls – 67 ATMs (none new)
4th pull of 1000 (1000 meter) pulls – 147 ATMs – maxing the 60 ATM limit
Census, pulled 2013-2017 using the same keys, choose to use the most current census data (2017)
First merged ATM onto the census data ultimately showing numerous null values for missing data
Changed the join to add census data into the ATM file, thus eliminating null values

## Obervation.

# Majority of ATMs located in zip codes with larger HHI >$100K
![GitHub Logo](/Bar_HHI_ATM.png)
# 60 percent of ATM are in zip codes with populations greater than 40,000 residents
![GitHub Logo](/Bar_Population_ATM.png)
# ATMs located in zip codes with rent between $700-$1150
![GitHub Logo](/Bar_Rent_ATM.png)
# Owners of ATM in RVA
![GitHub Logo](/Bar_long_ATM.png)

# Other Observation
50/50 split between bank and non-bank ATMs.  Expect that we are missing more non-bank owed ATMs than bank owned ATMs.
There is a major ATM strategy difference between the big banks Wells Fargo vs Sun Trust vs. Capital One.
Wells Fargo has 18 ATMS in the RVA area, compared to 8 and 2 for Sun Trust Bank and Capital One, respectively.

# Learning and Limitations
Ensure the data is joined in the right order, eliminating unnecessary nulls.
Be flexible and change approach as needed, data was difficult to get; not convinced we have a complete universe of ATM data
More time to spend with Master Card and Visa; still convinced this is possible, just not within our time frame or ability at this point
Relied on ATMs listed in Google;  assume large organizations and a few small entities list their ATMs in google. 

# Tools Used:  Jupiter NoteBook /Python, JavaScript, HTML, MongoDB
