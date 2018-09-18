# VIZ_UM UNIVERSITY of MIAMI 2018
In 2018 the [Center for Computational Science](https://ccs.miami.edu/) sponsored the VizUM Visualization Competition. The focus was on civic engagement and the tag line was; "Your City, Your Neighborhood and You". I decided to enter and *invited* (AKA coerced) two of my work mates at UM to join me. Suri and Carmel, so we entered as "Team UM Analytics". The goal was to gain more skills with visualization and specifically Python. 
Our first attempt with GEOPandas was a failure so we switched to Power BI and tried a Sand Dance viz. At the first checkpoint our Sand Dance viz was completely outclassed by the R-studio  and Tableau presentations of the other teams. ( Did I mention that BI was completely OUTCLASSED). After that embarrasement we went back to Python and finally got Seaborn to work. GeoPandas was replaced by ArcGIS and Folium and we finally started to make some progress.

This is a link to the [GIT live site](https://idoneo.github.io/VIZ_UM/).

We decided to host our results on Google pages because at the time we did not have GIT hub up and running. Here is the Google pages site:  
[Google UM_VIZ SITE](https://sites.google.com/view/umvizcompetition2018/home)

_______
# RESULTS

## Pedestrian and Motor Vehicle Crashes in Miami-Dade 2011-2018 

We found that the average speed for the accidents in this dataset was higher on Sundays. This is a countplot with error bars in Seaborn.

<img src= "/images/m .png" alt = "m"/>

The average speed was higher from 3AM to 6AM

<img src= "/images/n.JPG" alt = "n"/>

Males tended towards higher speeds. Seaborn violin plot.

<img src= "/images/spedbygender.JPG" alt = "spdgender"/>

We used ArcGIS near function to calculate the number of accidents within 20 meters of an intersection, then exported these results as an excel sheet and plotted them with seaborn. 

<img src= "/images/morethan10violet.JPG" alt = "intersections"/>

The speed tended to vary depending on the neighborhood. Here we used ArcGIS to create a neghborhood category by using the spatial join tool, then we created a dot plot of speeds by neigborhood.

<img src= "/images/suri'scrashes.JPG" alt = "spdneighborhood"/>


