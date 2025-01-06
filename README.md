This is Azure Data Factory-related practice. 
Here I have created:
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
           e) Create a data flow pipeline for grouping all activities and execute it.
           f) The ETL process is done. Just Monitor it.
