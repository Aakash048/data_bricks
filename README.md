Full path of data engineering and the tools that used.

Data(apis, applogs, csv, excel, iot) --> Extract the data with in the three forms (batch data and streaming data)...(Tools: kafka, apachespark, snowflake)--->store the data in the data lake(in the data lake we store the all types of data)......(Tool: aws s3)-----> transform the data with the help of sql, pyspark, pandas--------> store the data in warehouse(stores only structured data for analysise)....
to manage the this ETL pipeline we use the apache airflow where it use the DAG to provide the dependency and also handle the all steps. it also helps for scheduling the data. 
