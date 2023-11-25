# Zillow_Data_Analytics
 
## Overview
In This project, we build and automate a python ETL process that would extract real estate properties data from Zillow Rapid API
## Project Goals
This project would extract real estate properties data from Zillow Rapid API, loads it unto amazon s3 bucket which then triggers a series of lambda functions which then ultimately transforms the data, converts into a csv file format and load the data into another S3 bucket using Apache Airflow. Apache airflow will utilize an S3KeySensor operator to monitor if the transformed data has been uploaded into the aws S3 bucket before attempting to load the data into an amazon redshift. 
After the data is loaded into aws redshift, then connect to amazon quicksight to the redshift cluster to then visualize the Zillow (rapid data) data.
Apache Airflow is an open-source platform used for orchestrating and scheduling workflows of tasks and data pipelines. This project will entirely be carried out on AWS cloud platform.
## Services will be using

## Dataset Used

## Architecture Diagram

<img src="architecture.jpeg">

