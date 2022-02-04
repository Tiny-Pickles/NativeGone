# Main Goal for Displaying Data:
Within the interactive map section of this project is that I want to display at least a 5-year span that shows a correlation or a small relationship between the Tribal crimes that were reported and the location and occurrences of Extraction Projects within the United States. 

## Map Data:  ##
### Crime Data:  ###
I found several datasets that pertain to Tribal Crime data from the Bureau of Justice and Statistics. The BJS is a federal government agency that is a part of the U.S. Department of Justice responsible for providing data about crime at the federal, state, local, and tribal level.

First, I did find Tribal Crime data that displays all crimes reported to Tribal agencies on reservations from the year 2008 to 2019. Here is the [Tribal Crime data from 2008-2019] (https://bjs.ojp.gov/tribal-crime). Based on further research I will probably display Tribal crime data from the time range of 2008 to 2015. This is due to the fact that there was a huge oil boom that occurred within the Bakken Shale Formation located mostly in the state of North Dakota and some parts of Montana. This oil boom caused a lot of extraction industry and construction projects to occur that brought in a rush of oil workers near Native American Reservations and communities. These outside workers would set up camp in temporary housing units called “man camps”. 

#### Benefits and Limitations:   ####

All datasets are formatted into csv files and each csv file represents one year worth of crime data reported. My only concern is that I will have to manually enter in all of the latitudes and longitudes coordinates for each Tribal Agency that reported. Another consideration is to separate each yearly report separately or if I should combine all reports into one large dataset. If I did create one large dataset, I would have to add an additional column to represent each year that crime was committed. 

One large issue is that not all Tribal Law Enforcement Agencies have reported consistent data across each yearly report. For example in 2008 only 12 agencies reported while in 2012 168 agencies reported. This might be due to past legislation or court case decisions that occured during this time period regarding criminal reporting like the [Tribal Law and Order Act of 2010] (https://bjs.ojp.gov/topics/tribal-crime-and-justice).

### Extraction Project Data:  ###

I have found several datasets regarding extraction and construction projects from the U.S. Energy Information Administration which is the statistical and analytical agency that is a part of the U.S. Department of Energy. 

These data sets display extraction projects of certain resources and materials within the United States, such as crude oil and natural gas. I have found datasets of documented projects for [Natural Gas](https://www.eia.gov/naturalgas/data.php) and [Crude Oil](https://www.eia.gov/petroleum/data.php#movements). 

#### Benefits and LimitationsL:   ####

The overall datasets are very detailed regarding which Extraction company did what project, or if the project was interstate or not, what state did it start in and what state did it end in. Also the start year of the project and the status of it. Again I am having issues finding datasets with latitude and longitude coordinates. Most pipelines go across several state borders and have many joints and connections that go off in various directions. I would have to look into each project's latitudes and longitudes as well and depending on the type of project that would make it a bit tricky. 

An issue I am encountering is trying to find a large dataset that displays “man camps” within the United States. I am still trying to find data about the history of man camps within the extraction industry. But I think if I have data about construction and extraction projects that will still show a correlation between extraction projects and Native American crime.

## Coordinates from EIA Map Layers:  ##

### Option 1:   ###

I could download the shape files from the EIA website and use that to find the geo coordinates of Crude Oil Pipelines. 

### Option 2:   ###

Export the already existing map layers from ArcGIS Pro into KML and find the latitude and longitude coordinates for Crude Oil Pipelines 

I am willing to experiment with either option, preferably the most efficient one. I believe that either way this will help me with geo coordinates for the extraction projects listed above.



