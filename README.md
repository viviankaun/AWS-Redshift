# AWS Redshift Project Overview
![This is an image](https://github.com/viviankaun/AWS-Redshift/blob/main/img/Redshift001.jpeg)
# Reporing from User 
1. stagingsongs : distkey : artist_id
2. stagingevents: distkey : user_id
3. Face Table: songplays -> distkey: user_id
# Justify dataschema design and ETL pipeline
sql_queries.py   --> All of SQL statements, SQL scripts. 
create_tables.py --> It usually runs one time after the project is released. functions call each sql statements to run
etl.py --> We usually set up a schedule to run it.
# User analysis 
![This is an image](https://github.com/viviankaun/AWS-Redshift/blob/main/img/Redshift_O1.png)
![This is an image](https://github.com/viviankaun/AWS-Redshift/blob/main/img/Redshift_O2.png)
![This is an image](https://github.com/viviankaun/AWS-Redshift/blob/main/img/Redshift_O3.png)

