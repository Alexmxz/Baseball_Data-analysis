# MLB Baseball_Data-analysis
In this notebook, we're going to wrangle, analyze, and visualize Statcast data to compare Mr. Judge and another (extremely large) teammate of his. There are two CSV files, judge.csv and stanton.csv, both of which contain Statcast data for 2015-2017. We'll use pandas DataFrames to store this data and data visualization libraries, matplotlib and seaborn.

* Created data wrangling, analysis on Statcast data for helping the further visualization.
* Seaborn regplot and kdeplot were implemented, especially the kdeplot is one of the straightforward methods showing smoothed contours to represent density. 
* Gridding hist2D heatmaps for analysis of pitch location and strike zone.

## Code and Resources
**Python Version:** 3.8   
**Packages:** pandas, numpy, matplotlib, seaborn    
**For Web Framework Requirements:**  ```pip install -r requirements.txt```      
**Future of the Game: Baseball's Latest Statistical Revolution:** https://www.youtube.com/watch?v=9rOKGKhQe8U   
**Batted Ball Event (BBE):** https://www.mlb.com/glossary/statcast/batted-ball-event

## KDE plot
In order to getting into their hitting profiles, exit velocity vs. launch angle were plotted by contours to represent density
