# Manitoba Barley Crop Analysis <img src="/Data/Barley.png" align="right" width="120" />

---
This project is to analyse the Barley crop yields in the rural municipilities in Manitoba/Canada.
There are 3 main files in this project.
1) The  [Similar clusters of Manitoba Rms for Barley yields 2000-2022.pdf](https://github.com/lk-learner/Digital-Agriculture-Data-Analytics/blob/main/Assignments/Similar%20clusters%20of%20Manitoba%20Rms%20for%20Barley%20yields%202000-2022.pptx.pdf) file which has the final results presentation.
2) The [Digital Agriculture Capstone Project.ipynb](https://github.com/lk-learner/Digital-Agriculture-Data-Analytics/blob/main/Assignments/Digital%20Agriculture%20Capstone%20Project%20.ipynb) file that has the jupyter notebook code.
3) The Tableau Dashboard that can be found in the link  https://public.tableau.com/views/ManitobaRMs-BarleyYieldsAnalysis/BarleyDashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link 


## Introduction

Manitoba, a significant contributor to the Canadian agricultural sector, is particularly notable for its barley production. In this project, I delve into a data-driven exploration of hidden patterns and correlations in barley yields across Manitoba's Rural Municipalities (RMs). By employing data analysis techniques and visualizations, I aim to provide actionable insights for farmers, policymakers, and researchers.

## Data Gathering Process:
#### Crop Data

* Incorporate Manitoba yields for numerous crops 
* 11 Crop yields included for crop columns = ['Argentine Canola', 'Barley', 'Canary Seed', 'Durum Wheat', 'Lentils', 'Oats', 'Winter Wheat', 'Field Peas', 'Alfalfa', 'Faba Beans', 'Flax']
* - Total Municipalities for  Manitoba (MB)
* 2000 - 2022 Timeline of Data Gathered
* Manitoba Yields converted from pounds to bushels
* Source: [Manitoba Crop Data](https://www.masc.mb.ca/masc.nsf/mmpp_browser_soil_types.html)
  
#### Manitoba municipalities GIS Data

* Incorporate Geospatial data for each municipality from Manitoba
* 183 records, Total Municipalities have shape files available for Manitoba(MB) 
* Source: [Manitoba Municipalities Shapefiles](https://geoportal.gov.mb.ca/datasets/8b64285c3bf6445a8d0d8ea4a1c43849/explore?location=53.584348%2C-97.779011%2C6.81)



## Data Preprocessing and Exploratory Data Analysis (EDA)

My analysis commences with data loading, cleaning, and preprocessing, followed by an in-depth exploratory data analysis. I utilized visualization techniques such as histograms, boxplots, and scatter plots to examine the distribution and relationships of barley yields within and across RMs.

## Geographical Information System (GIS) Analysis

I subsequently integrate the aggregated data, including barley yield mean and standard deviation, with geographical data containing RM names and shapes. This process enabled me to visualize the results using maps, thereby providing a geographical context to my findings.

## Unsupervised Learning: K-means Clustering

To identify similar clusters of RMs based on barley yield patterns, I applied the Elbow Method and Silhouette Score method to ascertain the optimal number of clusters. Then illustrate the clusters on the map, unveiling distinct barley yield patterns across Manitoba's RMs.

## Conclusion and Future Work

My study successfully groups Manitoba RMs based on barley yield mean and standard deviation. These findings can inform agricultural practices, such as crop rotation, irrigation management, and fertilization strategies. Furthermore, the methodology can be extended to other crops or geographical regions, offering a versatile approach to understanding crop yield patterns.

## Acknowledgements

I gratefully acknowledge the provision of Manitoba crop yield data from [Manitoba Crop Data](https://www.masc.mb.ca/masc.nsf/mmpp_browser_soil_types.html) and the shapefiles for Manitoba RMs from [Manitoba Municipalities Shapefiles](https://geoportal.gov.mb.ca/datasets/8b64285c3bf6445a8d0d8ea4a1c43849/explore?location=53.584348%2C-97.779011%2C6.81) The analysis and visualizations were executed using Python, geopandas, seaborn, matplotlib, and other open-source libraries.


Should you find this analysis insightful, I encourage you to share it with your network and engage through comments or questions. Together, we can advance data-driven decision-making in the agricultural sector and beyond.
