# Udacity_Capstone_Project
## Scope

1. Data: The scope of this project, is to gather immigration data based on state level, to count how many immigration happened for 2016 in each month, and provide the possibility to analyze how the number is related to the state population/ household size/ median age etc.
2. End solution: I collected data using pyspark as it is a big data set, and then do data cleansing+transformation using pyspark dataframe. After that, I uploaded the datasets to AWS S3 to store the data, and then I copied the data from S3 to AWS Redshift, to have clean data structure on a data warehouse, and the data would be ready to use to perform analysis.
3. Tools included: Spark, AWS EMR cluster, S3 and Redshift.
