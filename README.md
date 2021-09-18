# Week-3-Independent-Project
BUSINESS UNDERSTANDING

Business Overview
The goal of every business is to be able to maximize value while minimizing costs, a process commonly known as efficiency of business. MTN Côte d’Ivoire, a leading telecom company, strategically seeks to upgrade its technology infrastructure for its mobile users within the country. The business would like to get some insights from the existing data so that it can invest efficiently in the upgrade. 

Business Objective

The main objective of this report is to identify the cities that MTN Cote d'Ivoire should prioritize technological upgrades. 

Business Success Criteria

To compile  a list of cities where there is high usage of MTN Cote d’Ivoire products to form the priority for upgrade.

Assessing the Situation

Resource Inventory

Datasets:
Telcom_dataset3.csv(link)
Telcom_dataset2.csv(link)
CDR_description.xlsx(link)
cells_geo.csv(link)
cells_geo_description.xlsx(link)
Telcom_dataset.csv(link)
Software( Github and  Google Collaboratory)

Assumptions

The data provided is correct and up to date

Constraints
All the datasets cannot be merged fully.

Data Mining Goals
Our data mining goals for the project are as follows:
Arrange the usage of MTN products in Cote d’Ivoire.
Order the cities in terms of usage in a descending order.
Understand the usage of MTN products, that is in Business hours and home hours.



Data Mining Success Criteria
Our success criteria will be measured by understanding the usage of MTN products and the level of usage in the cities.



DATA UNDERSTANDING

Data Understanding Overview
For this project, we are using the availed dataset by the company. These datasets are:
Telcom_dataset3.csv - Give data on the products’ usage on 8th and 9th.
Telcom_dataset2.csv - Give data on the products’ usage on 7th.
CDR_description.xlsx- Gives data on the telecom data format
Cells_geo.csv - a dataset defining location including cities. 
Cells_geo_description.xlsx - describes the format of the file cells geo.
Telcom_dataset.csv- Give data on the products’ usage on 6th.

Data Description

We have two main datasets available for this project in four files. A detailed description of the datasets is provided as follows:
Cell Geo - this dataset contains a description of location, cities, latitude, longitude, cell id and site code that the cells used.
Telecom Datasets - There are three datasets for three consecutive days showing the usage MTN products that are voice, sms and data.
Verifying Data Quality
There were datasets with null values that we removed to have quality data.

DATA PREPARATION
These are the steps followed in preparing the data 
Loading Data 
The data was loaded in a collaborative python notebook. 
Cleaning Data
The column names from the three datasets had pronunciation errors and we changed them to the correct names. We also ensured that all the column names were similar and in capital letters.
Merging of the Datasets
After cleaning the data, I merged the three datasets. Thereafter, we merged the merged telcom data and cell geo data using the similar column Site Code.

ANALYSIS
The following cities in Cote d’Ivoire were the most active cities:
Yopougon
Abobo
Cocody
Adjame
Koumassi
The most used product is SMS, Voice then Data. The  cities that used each product the most was:
SMS 	- Yopougon
-Abobo
Voice 	- Yopougon
-Abobo
The above analysis was done using Collaborative python notebook. The full analysis can be found in the following notebook.[Link]

RECOMMENDATIONS

From our analysis, we would recommend that MTN should prioritize the above-listed cities in the process of upgrading its technology. Our main reason behind this recommendation would be that the cities above have huge usage of MTN Cote d’Ivoire products.Therefore, prioritizing these cities would ensure that the services in these cities are effective and sufficient. This would ensure that MTN is reliable and ensure growth of usage in these cities. It would also ensure that there is a return in the investment in a short period. 

