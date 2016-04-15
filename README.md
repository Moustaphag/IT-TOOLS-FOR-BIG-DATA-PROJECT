# IT-TOOLS-FOR-BIG-DATA-PROJECT


-----------------------------------
---
-----------------------------------------------
---------------------------
--
## ABOUT THE PROJECT:


This project is an execution of 'IT Tools in Big Data' performed at ENSAI, Rennes.

The project includes the following code files:


1. script_weather_data: python script to scrape online weather data from forecast io.

2. code_for_queries_hive.hql: Hive script to load and aggregate the data, and store it in a tabular format onto HDFS.





## INSTRUCTIONS FOR PROJECT EXECUTION:


Please follow the below mentioned instructions to execute the project:


1. Install a Hadoop distribution on your local machine (for example, Hortonnworks HDP)

2. Save copies of the project data (3 csv files each for catalogue, customer, order, and product reference) on a local hdfs.For run the different queries you should take care about the directory.

3. install python, Download and Run the script_weather_data.py script to donwload Online Weather Data, and Create a local copy.

4. For run the schedulling with oozie run the command : $ oozie job-config job.xml-run
   more detail in the folder oozie.
