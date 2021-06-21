# Battle of the Neighborhoods
This project is a part of the [Capstone Project](https://www.coursera.org/learn/applied-data-science-capstone?specialization=ibm-data-science) at [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science?). 

-- Project Status: [Completed]

## Project Objective

The purpose of this project is to apply an unsupervised machine learning technique, `Clustering`, to categorize the suburbs in metropolitan Melbourne based on the recorded crime incidents, venue categories, and rental status in 2020. The analysis results could help an individual or a company gain insights into the features of suburbs and make life or business decisions.

## Methodology

- Web Scraping
- Data Collecting
- Data Cleaning
- Data Exploration/Descriptive Statistics
- Data Visualization
- Data Processing
- Clustering

## Technologies

- Python 3.8
- Pandas 1.2.4
- Numpy 1.20
- Matplotlib 3.4.2
- Folium 0.12.1
- Seaborn 0.11.1
- BeatifulSoup 4.9.0
- Scikit-Learn 0.24

## Project Description

A start-up company plans to expand and grow their business in Australia in the next five years. The company is planning to establish their headquarter office in Docklands, Victoria. Furthermore, twenty of the senior-level employees will be asked to relocate to Melbourne and supervise the progress of this business establishment.

As a part of the plan, the company will provide accommodations to their senior-level employees to help them transit into new location seamlessly and reduce the negative influence of relocation on their work efficiency. According to the company's founders, their selection criteria of accommodations' locations must be in the suburbs with a few features shown as below:

- 15kms in radius distance or equivalently 30mins travel time to the office during peak hours (Office will be in Docklands, VIC 3008)
- An affordable rental price with a large volume of rental properties available in the market
- Safe area with low assaulting class crime incidents
- Easy to access venues such as restaurants, cafe, and parks.

The objective of this project is to apply clustering to categorize the suburbs in metropolitan Melbourne based on recorded crime incidents, venue categories, and rental status in 2020. A feature evaluation will be carried out for each set of cluster. Finally, the cluster with the desired features will be recommended to the company as suitable accommodations locations.

In this project, all data was collected from free and public available datasets.

### Data Requirements

Based on the project's objective, the datasets used in this project will cover the following sectors:

General information by suburb including name, postcode, coordinates, and council which it belongs to
Types of crime incidents and their frequencies recorded by suburb
Number of rental properties available and their median prices by suburb
Categories of venues and their numbers by suburb

### Data Source

- General information of suburbs in Metropolitan Melbourne (https://en.wikipedia.org/wiki/List_of_Melbourne_suburbs)
- Nominatim API to extract geographical coordinates of each suburb (https://nominatim.org/release-docs/develop/api/Overview/)
- Crime Statistics Agency Data Tables - Criminal Incidents (https://discover.data.vic.gov.au/dataset/crime-by-location-data-table)
- Rental Report - Quarterly: Moving Annual Rents by Suburb (https://discover.data.vic.gov.au/dataset/rental-report-quarterly-moving-annual-rents-by-suburb)
- Foursquare API to extract venues information (https://developer.foursquare.com/docs/places-api/)


## Getting Started

1. Clone this repo(for help please see this [tutorial](https://help.github.com/articles/cloning-a-repository/))

2. The crime incident report and rental status report datasets have been downloaded and stored locally at [./dataset/raw_data](https://github.com/xpgon1/Battle_of_the_Neighborhoods/tree/main/datasets/raw_data) to reduce the download requests made in the notebook, 

3. Notebooks are stored at [./notebooks]()

4. Images and Graphs presented in the notebooks can be found at [./images/battle_of_neighborhoods](https://github.com/xpgon1/Battle_of_the_Neighborhoods/tree/main/images/battle_of_neighborhoods)

## Featured Notebooks
- [Data Collection and Cleaning](https://github.com/xpgon1/Battle_of_the_Neighborhoods/blob/main/Data_collection_and_cleaning.ipynb)

- [Data Exploring and Preprocessing](https://github.com/xpgon1/Battle_of_the_Neighborhoods/blob/main/Data_exploring_and_preprocessing.ipynb)

- [Clustering](https://github.com/xpgon1/Battle_of_the_Neighborhoods/blob/main/Clustering.ipynb)

### Author
[Johnny Gong](https://github.com/xpgon1)

[Linkedin Account](https://linkedin.com/in/johnny-gong-phd-184b28ba)
