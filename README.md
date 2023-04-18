# #30DayMapChallenge, 2022
Data, code, and visualizations for 2022 #30DayMapChallenge. The collection of these assets can be found in the [personal website](https://renegamino012.github.io/projects/2022-30-day-map-challenge). 

## Day 01 (Points)
Last year, my mentor recommended opting for simple datasets and ArcGIS Online for the #30DayMapChallenge. However, after a hiatus, I followed the recommendation: a map that displays the County of Los Angeles' certified farmer's markets, showcasing their weekly availability (discounting holidays and seasonal absence).

### Resources
* [LA County Boundary](https://www.arcgis.com/home/item.html?id=8b26838d162d4e908ba48375f625a159) (County of Los Angeles; DPW; ISD; CEO)
* [Farmers Markets](https://geohub.lacity.org/datasets/lahub::farmers-markets/about) (The County of Los Angeles Location Management System)
* [ColorBrewer 2.0, for colorblind-safe, qualitative color scheme](https://colorbrewer2.org)

![County of Los Angeles' Farmer's Markets](/01__points/01__points.png?raw=true "County of Los Angeles' Farmer's Markets")

Please, visit the [ArcGIS Online Web Map](https://arcg.is/XejLv) to explore and interact with the points.

## Day 02 (Lines)
I was interested by the several minimalist maps, displaying infrastructure, boundaries, and natural resources. 

### Resources
* [Streets (Centerline)](https://geohub.lacity.org/datasets/d3cd48afaacd4913b923fd98c6591276_36/about)

![Streets in City of Los Angeles, Centerline](/02__lines/02__lines.png?raw=true "Streets in City of Los Angeles, Centerline")

## Day 05 (Color Friday: Green)
Ian Usher's [LinkedIn post](https://www.linkedin.com/posts/ian-usher-16591b3b_30daymapchallenge-naturalengland-gis-activity-6994232031282888704-7bk2?utm_source=share&utm_medium=member_desktop) influenced this visualization, especially for their focus on the Access to Natural Greenspace Standards (ANGSt). However, I chose the City of Los Angeles as the location of interest because of its personal relevance. 

### Resources
* [City of Los Angeles Boundaries](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html) (United States: United States Census Bureau)
* [Countywide Parks and Open Space](https://geohub.lacity.org/datasets/lacounty::countywide-parks-and-open-space-public-hosted/about) (Los Angeles County, 2016; PlaceWorks, 2015)
* [LA City Council Districts, Adopted 2021](https://geohub.lacity.org/datasets/76104f230e384f38871eb3c4782f903d_13/about) (County of Los Angeles, Bureau of Land Management)
* [ColorBrewer 2.0, for colorblind-safe, sequential color scheme](https://colorbrewer2.org)

### Geoprocessing (in ArcGIS Pro):
* Cell Statistics
* Clip Raster
* Pairwise Buffer
* Polygon to Raster
* Select

![Access to Natural Greenspace in Los Angeles](/05__colors_friday_green/05__colors_friday_green.png?raw=true "Access to Natural Greenspace in Los Angeles")
