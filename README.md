# linux command guidline

A data pipeline with  GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.


## Description

### Objective

The goal of this project is to analyze Uber data using tools like GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio. We aim to explore TLC Trip Record Data for yellow and green taxi trips, focusing on details like dates/times, locations, distances, fares, rate types, payment types, and passenger counts. The objective is to gain insights and perform data analytics for informed decision-making.

### Dataset

TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 

Here is the dataset used  - [Link](https://github.com/aditishraq/Ride-Sharing-ETL-Pipeline/blob/main/data/ride_share.csv)

More info about dataset can be found here:
1. Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
2. Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
#Table of Contents

# Table of content:
### File System Navigation

- List the contents of the home directory.
- Change the current directory to /var/log and list its contents.
- Find and display the path to the bash executable using the which command.
- Find current shell

### File and Directory Operations
- Create a directory named linux_fundamentals in your home directory.
- Inside linux_fundamentals, create a subdirectory named scripts.
- Create an empty file named example.txt inside the linux_fundamentals directory.
- Copy example.txt to the scripts directory.
- Move example.txt from linux_fundamentals to linux_fundamentals/backup

### Permissions
- Change the permissions of example.txt to read and write for the owner, and read-only for the group and others.
- Verify the permission changes using ls -l
### File Modification
- Create a file named example.txt in your home directory.
- Change the owner of example.txt to a user named student
- Change the group of example.txt to a group named students.
- Verify the changes using appropriate commands.

### Architecture

![architecture](img/1.1.JPG)
![architecture](img/1.2.JPG)
![architecture](img/1.3.JPG)
![architecture](img/2.1.JPG)
![architecture](img/2.2.JPG)
![architecture](img/2.3.JPG)
![architecture](img/2.3.JPG)
![architecture](img/2.4.JPG)
![architecture](img/3.1.JPG)
![architecture](img/3.2.JPG)

### Data Model

![datamodel](img/data_model.jpg)

### Dashboard

![dashboard](img/ride_sharing_dashboard.jpg)


