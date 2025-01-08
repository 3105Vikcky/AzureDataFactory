This is Azure Data Factory-related practice. 
Here I have created the following:
1. Pipeline for copying data Activity from the source to the sink.
2. Created Integration Runtime:
            a) Azure Integration Runtime.
            b) Self-Hosted Integration Runtime.
            c) SSIS Integration Runtime.
3. Created Data flow for the transformation of the data complete ETL process:
           a) Create Data Flow:
           b) Add Source/ Create Source two or more files
           c) The data transformation technique is applied using GUI code-free Azure services. I used here to join the two datasets which have a similar ID column
           d) Then I created a Source dataset for loading the transform data.
           e) Create and execute a data flow pipeline to group all activities.
           f) The ETL process is done along with monitoring.

4. Started new ETL for employee-related information:
           a) Create data flow name employeeDataflow
           b) Add source/ Create source for 3 files.
           c) Transform data using the aggregate function count and clause group to remove duplicate data.
           d) Then load the data to the destination container for future processing.
           f) Create and run the pipeline for employeeDataFlow and trigger the pipeline.
           g) Monitor the pipeline.
