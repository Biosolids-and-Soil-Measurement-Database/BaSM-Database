# Biosolids and Soil Measurements (BaSM) Database

This repository is for the development and release of the BaSM Database data files and tools. The database will be periodically updated with data sets and source code.

Last data update: 17 July 2020

# Introduction


The current focus for the collected datasets will be on **biosolids land-application**, with emphasis on *soil organic carbon* and *soil organic matter* changes. This metadata is to first address the carbon sequestration potential of land-applied biosolids from an analysis of existing data. The analysis will be used to aid in obtaining compliance with C crediting programs (e.g., American Carbon Registry) and integration into IPCC SOC protocols. Ideally, we are hoping to compile a range of baseline and temporal C values for biosolids treated lands. The data we collect will be added to this public repository. The intention is that this will be supplemented over time (see **How to contribute**). This will promote biosolids research, assist with the identification of research gaps, and hopefully better inform and harmonize future collection methods.


# How to contribute


To make this a dynamic and community-oriented database, we need the help of you! We are open to collaboration and suggestions on how to improve this database for future analyses and the extenison of new datasets as studies become published. Here are specific ways to contribute:

1. Fork out (using git) a copy of the data and you can modify/add data. Then send a pull request when done. The submitted code/data must pass our validation criteria.

2. If you're not comfortable with git/github, use the Excel document provided for data entry and then email the file back to the project administrator (Mike Badzmierowski, PhD) mikejb7@vt.edu.

3. If you would like to assist with the development of a website and public materials please email mikejb7@vt.edu

# Structure of repository

### Data

This folder contains all the data currently in BaSM Database. There is a `biosolids-master-file.csv file` containing all metadata from gathered sources. A list of the studies currently in BaSM Database `(studies_list.csv)`, as well as a guide for entering new data (Readme.md), an annotated blank template file `(template_metadata.csv)`, and a blank `initConditions.csv` file are located in this folder.

### Scripts

This folder contains R coded to analyze and visualize the current data.

### Website

This folder contains files to generate the BaSM Database website.
