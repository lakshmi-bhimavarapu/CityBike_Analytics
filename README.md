# CityBike_Analytics 2022


[Tableau link.](https://public.tableau.com/app/profile/lakshmi.bhimavarapu6627/viz/CitiBike_Analytics_16748796420470/TopHours?publish=yes)

### Objective

The purpose of this project was to aggregate data found in the Citi Bike History Logs and find several interesting insights from data.

These designed visualizations were used to assemble dashboards and finally our Story.

 

### Data Source

The data is collected from the files found in the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage. 

Jersey City trip histories files from 2022 were downloaded (12 files) into "Resources" folder.

The files were then joined with Pandas to one dataframe. geopy library was used to calculate geographical distance between start stations and end stations. At the end the dataframe was saved to a csv file to be used in Tableau.

### Data Analysis

#### Trips (rides) breakdown
#### User Type Breakdown
#### Start Stations
#### End Stations

### Tableau

The following Tableau features I used during this project:

##### Combined Fields:

Start St. Id --> End St. Id 

Start Station Name --> End Station Name



##### Calculated Fields:

Geodistance (miles)

Number of Trips

Percent of Total

Rank

Top 10 - Bottom 10

Trip Distance

Trip Duration (min.)

Tripduration Aggregations



##### Parameters:

Select Aggregation
