# February 2021 Power Outage Analysis in Houston, Texas
## Overview
This repository contains an RMarkdown document and associated R scripts for conducting a detailed analysis of the power blackouts that occurred in the Houston Metropolitan area during the severe winter storms in February 2021. Aside from determining which homes in the Houston area were affected by the loss of power caused by the storms, another large focus of this analysis is to investigate is socioeconmic factors, specifically median income, can serve as predictors regarding communities' recovery from loss of power. The analysis is accomplished using remotely-sensed night light data, providing a unique spatial perspective on the extent of power outages during the storms.

## Background
In February 2021, the state of Texas faced severe electricity generation failures during three consecutive winter storms occurring between February 10-11, 13-17, and 15-20. These extreme weather events resulted in widespread power outages affecting over 4.5 million homes[^utexas].This analysis employs remotley-sensed nightlight data from February 7, 2021, and February 16, 2021 to understand the extent of power loss experienced and to identify which homes experienced blackouts as a result of the storms. Furthermore, the analysis incorporates data from the US Census Bureau, synergizing socioeconomic factors with night light data. The primary objective is to explore if median income, as a socioeconomic indicator, can serve as a predictive factor influencing communities' recovery from power loss during the storms.

## Data
- *Nightlight Data* : Night light data from the Visible Infrared Imaging Radiometer Suite (VIIRS) onboard the Suomi satellite and collected on 2021-02-07 (before the storm) and 2021-02-16 (after/during the storm) are utilizied
- *Highways Data* : Geofabrik's OpenStreetMap-derived dataset provides information on highways in the Houston area.
- *Building Data* : Geofabrik's dataset on OpenStreetMap buildings assists in identifying homes affected by power outages.
- *Socioeconomic Data*: The United States Census Bureau's American Community Survey (ACS) 2019 furnishes demographic and socioeconomic data, specifically median income, at the census tract level.

The data associated with this analysis is too large to include in the GitHub repo, and thus were omitted using gitignore, however the zipped data can be downloaded [here](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view?usp=sharing).

## Credit
This analysis is based on materials developed by Ruth Oliver at UC Santa Barbara.

[^utexas]: The University of Texas at Austin, Energy Institute. 2021. "The Timeline and Events of the February 2021 Texas Electric Grid Blackouts." July 2021. https://energy.utexas.edu/research/ercot-blackout-2021#:~:text=The%20Timeline%20and%20Events%20of,more%20than%204.5%20million%20homes.
