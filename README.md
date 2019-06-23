The purpose of this project was to create a way for Sparkify to utilize the data they have been collecting
for song play analysis.
To do this, we utilized a star schema where a fact table and dimension tables were created. We use this
because dimension tables allow for understanding how the data provided affects the fact tables. This helps
with creating various sql queries.
For the python scripts, we first created the sql queries to create the datatables. Then from there, we started 
to create the ETL processes by retrieving the data from song_data and log_data. Finally we launched the etl pipeline for the remainder of the files that were collected in both data sets. 