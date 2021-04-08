<img src="https://github.com/huseyinelci2000/DE-ETLProcessingWithPython/blob/main/image/ETL.png?raw=true" width="100%">
---

## ETL Processing With Python & SQLAlchemy
Understanding **Extract**, **Transform** and **Loading** (ETL) in **Data Driven world** with an example in codes Python and SQLAlchemy 

Data Driven people, be it a programmer, business analyst, data scientist or database developer, has been developing ETL pipeline directly or indirectly. For data-driven businesses, ETL is a must.

## What is the ETL?
In computing, extract, transform, load (ETL) is the general procedure of copying data from one or more sources into a destination system which represents the data differently from the source(s) or in a different context than the source(s). The ETL process became a popular concept in the 1970s and is often used in data warehousing.[1](#1) 
You can extract data from any data sources such as Files, any RDBMS or NoSql Database, Websites (with scrabing) or real-time user or machine activity (from Kafka).
Transform the acquired data and then load the transformed data into a data warehouse for your business uses such as reporting, analytics or visualization.
ETL is a 3 main steps process:
1. **Extract**ing Data from single or multiple Data Sources. Transforming Data as per business logic. 
2. **Transformation** is in itself a two steps process. Data cleansing and data manipulation.
3. **Loading** transformed data into the target data source, data warehouse or data mart.


## Extract
The first part of an ETL process involves extracting the data from the source system(s). In many cases, this represents the most important aspect of ETL, since extracting data correctly sets the stage for the success of subsequent processes. Most data-warehousing projects combine data from different source systems. 

## Transformation
In this stage, a series of rules or functions are applied to the extracted data in order to prepare it for loading into the end target.
An important function of transformation stage is data cleansing, which aims to pass only most 'proper' data to the target.
In this stage uses label encoding, cleaning from null values, calculating some group or aggregations, splitting or any transforming.

## Loading
The load phase loads the data into the end target, which can be any data store including a simple delimited flat file or a data warehouse.[2](#2) Depending on the requirements of the organization, this process varies widely. Some data warehouses may overwrite existing information with cumulative information; updating extracted data is frequently done on a daily, weekly, or monthly basis. 
> ETL should not be confused with a tool like Informatica, DataBricks or Airflow. It is a data processing concept that can be created with programming languages and the help of various tools.

## Creating ETL pipeline
Let's we establish ETL pipeline. Data engineers, data scientists, machine learning engineers and data analysts mostly use data. And these mostly use the Python scripting language.

Wherefore, here we will establish our ETL pipeline by using Python programming language with SQLAlchemy. (You can use sqlite3, etc wıth Pythoninstead of SQLAlchemy) It shouldn't forget Python comes with lots of different libraries that help to establish tens of Data Analytics, Data Visualization or Data Science solutions.

Here is my simple 3 main steps process for ETL:
* Extract data from **.sqlite** file with **SQLAlchemy**
* Transform / Manipulate Data with **pandas**
* Load Data into **.sqlite** Database with **SQLAlchemy**

## Source, Licensing, Authors, and Acknowledgements

#### Source
The Source owner is [Luis Rocha](https://github.com/lerocha) [Download File](https://github.com/lerocha/chinook-database/blob/master/ChinookDatabase/DataSources/Chinook_Sqlite.sqlite)
Chinook is a sample database available for SQL Server, Oracle, MySQL, etc. It can be created by running a single SQL script. Chinook database is an alternative to the Northwind database, being ideal for demos and testing ORM tools targeting single and multiple database servers.
#### Licensing
In this project is **OpenSource** and owner is  [Luis Rocha](https://github.com/lerocha). Also, if _you plan to use this database in your article research or else_ you must taken and read main Source in the **Luis Rocha repository**.
#### Authors
Huseyin ELCI
  |  [Github](https://github.com/huseyinelci2000)  |  [Kaggle](https://www.kaggle.com/huseyinelci)  |  [Linkedin](https://www.linkedin.com/in/huseyinelci/)   |  
#### Acknowledgements
Thanks to [Luis Rocha](https://github.com/lerocha) for providing cool data which we can create a cutting edge project.



- <a id="1">1 Denney, MJ (2016) [Validating the extract, transform, load process used to populate a large clinical research database](http://https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5556907)</a>
- <a id="2">[2 Data Integration Info](https://www.dataintegration.info/etl)</a>
