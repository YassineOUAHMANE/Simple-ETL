# ETL Process for Extracting Data from Autolist API 🚗📊
## Overview
This project demonstrates the ETL (Extract, Transform, Load) process for retrieving automotive data from the Autolist API, transforming the data to meet requirements, and loading it into a MySQL database. The data can then be queried for insights on vehicle models, prices, mileage, and more.
## Introduction
The automotive market is rich with data that can provide valuable insights for buyers and sellers alike. By leveraging the Autolist API, we can gather information on various vehicles and store it in a structured format within a MySQL database. This enables efficient querying and analysis. 🔍
## Requirements 🛠️
Python 3.x 🐍
Libraries:
requests 📦
pandas 📊
Sqlalchemy which simplifies the insertion process. 📥
MySQL server running 🗄️
Access to the Autolist API 🌐
## API Overview
The Autolist API provides access to automotive listings, including details such as make, model, price, mileage, and dealer information.

# ETL Process
## Extract 🌐
The extraction phase involves sending a GET request to the Autolist API with specified parameters and headers, including cookies for session management. The response data is retrieved in JSON format.
## Transform 🔄
Once the data is extracted, it is transformed into a more usable format. This involves selecting specific fields and organizing them into a structured format, such as a Pandas DataFrame.
## Load Data into MySQL 📥
We load the transformed data into a MySQL database using SQLAlchemy

## Query the Data 🧐
Now that the data is loaded, you can run various SQL queries to analyze the vehicle listings.

