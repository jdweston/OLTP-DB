# OLTP-DB
This project demonstrates the creation of a data platform using MySQL as the OLTP (Online Transaction Processing) database for an e-commerce company that will store the transactional data into a table titled 'sales_data'. A script is created as well to export all of the data from that table into a dump SQL file.

The project is viewable via code snippets and screenshots in the images folder, and I will explain each image and what is going on below.

In this project I am given a csv file with 6,000+ rows of OLTP data from an e-commerce site (found in the data folder). Based off of the data sample shown in "data_snippet.jpg", I created a table in my database titled 'Sales'. The SQL for the creation can be seen in "createtable.jpg". Once the table was created successfully, I imported the data from the csv file into it using phpMyAdmin. To ensure all rows were imported, I ran a query to display the row cardinality of my 'sales_data' table as shown in "salesrows.jpg". Finally, I created a bash script to run for exporting the table and its contents into a dump SQL file for replicability (found in the dump folder).
