## 
# Read Me

All the files used for make the scheduling in oozie are stored in this Directory.



The list of files are

1. query_oozie.hql
      file containing all the queries, with the names and path of external table modify in variable. this file
      contain all query for process the product and customer data and store them in result folder on HDFS.
  
2. weather_oozie
      file containing the python code for fetch the weather data from forecast.io.
      For run this code for the schudiling, we assume that there are already one file containing the precedent weather and we
      append the new ones

3. job
      Setting up the different configuration files, according to variable names a value (for directory and table), 
      and all the parameter (namenode, jobtraker) and others...
      
4. workflow
          present the order of the workflow, which operation should after another
          
5. controller
          conrol the global work, and assign the time of the code excution.



Execution Instruction

All the file should be put in a unique folder on the HDFS expect the **job** that should be put on the local system.

For start the oozie job run the following command from the terminal, where the job file is located
    
          $ oozie job-config job.xml-run
