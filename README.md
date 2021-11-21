# Cross platform query web application

## Data Transfer

In this project we Create an an EC2 cluster on AWS then Transfered the Instacart marketbasket analysis to the S3 bucket using copy function. Then we transfered that data from S3 bucket to EC2.

## Database connection and Technologies used for query execution

* We used Use Flask to create a web application in python.
* We used HTML to create the frontend for our web application and establish connection with our backend. 
* We used pymysql library to connect to the mysql database
* We used pyscopg2 to connect the web app to the redshift database
* We used devart pyodbc driver to establish connection to the MongoDB database
* We used pyodbc library to convert our mysql queries in the frontend to MongoDB in the backend

## Webapp Screenshots

### Before query execution

![Screenshot (83)](https://user-images.githubusercontent.com/79534543/124023505-01ab1380-d9bc-11eb-9156-cb2a104402a9.png)

### After query execution

![Screenshot (84)](https://user-images.githubusercontent.com/79534543/124023555-0d96d580-d9bc-11eb-9dc5-8fcdbcdcb80f.png)

## Functionalities of our web application

* Run SQL queries on relational databases like mySQL, Amazon redshift and non relational databases like MongoDB.
* Convert the output result of the query to a csv file.
* Display last executed query.
* Display the Time taken to execute query. 
* Throw an error if query is invalid. 
