# NYC Evictions

## Project Description
This project is intended to look at trends in evictions in New York City and to analyze how evictions have changed over the years, spanning from pre-pandemic to post-pandemic. This is spurred by multiple headlines I've seen this year stating that eviction rates in NYC have gone up, almost reaching pre-pandemic levels again. Knowing how bad the housing situation is currently in NYC, I was curious how bad evictions might possibly be.

## Approach
I wanted to do a project that would involve analyzing a large dataset and incorporate mapping and scrollytelling. I wanted to gain more experience with QGIS and ai2html, so I structured the project around these tools.

## Data Collection
I downloaded the <a href="https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4">Evictions dataset from NYC Open Data</a>. I also used <a href="https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm">Borough Boundaries</a> and <a href="https://data.cityofnewyork.us/City-Government/City-Council-Districts/yusd-j4xi">City Council shapefiles</a> that I downloaded from NYC Open Data for QGIS spatial analysis. I wanted to take the story a step further to look at other related housing issues, such as housing code violations, so I downloaded that data set from <a href="https://data.cityofnewyork.us/Housing-Development/Housing-Maintenance-Code-Violations/wvxf-dwi5/about_data">NYC Open Data</a> as well.

## Data Analysis
I cleaned and filtered the data in a Jupyter notebook to only look at 2017 to 2023. I then analyzed using pandas to look at trends over time, as well as trends in each borough.

For spatial analysis in QGIS, I created separate heat maps for each year, and used the City Council shapefiles to see which districts have the highest number of evictions each year. I compared the spatial analysis to the data analysis done in Jupyter notebook.

## Reflections
I had some difficulty figuring out the angle for this story.  If I had more time, I would include a zoomed-in map of the Bronx so I could label the city council districts with their respective neighborhoods. I also wanted to create a map in QGIS using data from the United States Census Bureau to visualize poverty levels in New York City, in order to verify the stats I found online about poverty rates in the Bronx. Unfortunately, I didn't have time to gather the data using the Census API (also, it's so confusing to use!) and create a map that would help better explain the high eviction rates in those particular neighborhoods in the Bronx. I also wasn't sure if the data on housing code violations was completely relevant or necessary to include, but I did find it interesting in my analysis that the same 4 council districts kept showing up in the Evictions analysis and Housing Code Violations analysis. Some further reporting could have been useful at this point to understand contributing factors, but again, time constraints kept me from pursuing the story more. Alas!
