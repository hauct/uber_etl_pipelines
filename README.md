# Uber elt pipeline project

## Introduction

The objective of this project is to utilize a range of tools and technologies, such as GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio, for the purpose of conducting data analytics on Uber data.

## Architecture 
<img src="architecture.jpg">

## Technology Used
- Programming Language - Python

Google Cloud Platform
1. Google Storage
2. Compute Instance 
3. BigQuery
4. Looker Studio

Modern Data Pipeine Tool - https://www.mage.ai/

Contibute to this open source project - https://github.com/mage-ai/mage-ai


## Dataset Used
TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used in the video - https://github.com/hauct/uber_etl_pipelines/main/data/uber_data.csv

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Data Model
<img src="data_model.jpeg">

## Let begin
### Firstly, we need import the data in folder `data` into Google Cloud database. Follow the instruction in the `.\setup
\google_cloud_db\bucket_db` to do this
