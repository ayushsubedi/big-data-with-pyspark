# Big Data with PySpark

# Progress

## Introducation to PySpark

### Getting to know PySpark
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/1_introduction_to_pyspark/1_getting_to_know_pyspark)

 - [x]	What is Spark, anyway?
 - [x]	Using Spark in Python
 - [x]	Examining The SparkContext
 - [x]	Using DataFrames
 - [x]	Creating a SparkSession
 - [x]	Viewing tables
 - [x]	Are you query-ious?
 - [x]	Pandafy a Spark DataFrame
 - [x]	Put some Spark in your data
 - [x]	Dropping the middle man
 
 ### Manipulating data 
 [Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/1_introduction_to_pyspark/2_manipulating_data)
 - [x]	Creating columns
 - [x]	SQL in a nutshell
 - [x]	SQL in a nutshell (2)
 - [x]	Filtering Data
 - [x]	Selecting
 - [x]	Selecting II
 - [x]	Aggregating
 - [x]	Aggregating II
 - [x]	Grouping and Aggregating I
 - [x]	Grouping and Aggregating II
 - [x]	Joining
 - [x]	Joining II

### Getting started with machine learning pipelines
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/1_introduction_to_pyspark/3_getting_started_with_machine_learning)
- [ ]	Machine Learning Pipelines
- [ ]	Join the DataFrames
- [ ]	Data types
- [ ]	String to integer
- [ ]	Create a new column
- [ ]	Making a Boolean
- [ ]	Strings and factors
- [ ]	Carrier
- [ ]	Destination
- [ ]	Assemble a vector
- [ ]	Create the pipeline
- [ ]	Test vs Train
- [ ]	Transform the data
- [ ]	Split the data

### Model tuning and selection
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/1_introduction_to_pyspark/4_model_tuning_and_selection)
- [ ]	What is logistic regression?
- [ ]	Create the modeler
- [ ]	Cross validation
- [ ]	Create the evaluator
- [ ]	Make a grid
- [ ]	Make the validator
- [ ]	Fit the model(s)
- [ ]	Evaluating binary classifiers
- [ ]	Evaluate the model

# Big Data Fundamentals with PySpark

### Introduction to Big Data analysis with Spark
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/2_big_data_fundamentals/1_introduction_to_big_data)
- [x] What is Big Data?
- [x] The 3 V's of Big Data
- [x] PySpark: Spark with Python
- [x] Understanding SparkContext
- [x] Interactive Use of PySpark
- [x] Loading data in PySpark shell
- [x] Review of functional programming in Python
- [x] Use of lambda() with map()
- [x] Use of lambda() with filter()

### Programming in PySpark RDD’s
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/2_big_data_fundamentals/2_programming_pyspark_rdd)
- [ ] Abstracting Data with RDDs
- [ ] RDDs from Parallelized collections
- [ ] RDDs from External Datasets
- [ ] Partitions in your data
- [ ] Basic RDD Transformations and Actions
- [ ] Map and Collect
- [ ] Filter and Count
- [ ] Pair RDDs in PySpark
- [ ] ReduceBykey and Collect
- [ ] SortByKey and Collect
- [ ] Advanced RDD Actions
- [ ] CountingBykeys
- [ ] Create a base RDD and transform it
- [ ] Remove stop words and reduce the dataset
- [ ] Print word frequencies

### PySpark SQL & DataFrames
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/2_big_data_fundamentals/3_pyspark_sql_and_df)
- [ ] Abstracting Data with DataFrames
- [ ] RDD to DataFrame
- [ ] Loading CSV into DataFrame
- [ ] Operating on DataFrames in PySpark
- [ ] Inspecting data in PySpark DataFrame
- [ ] PySpark DataFrame subsetting and cleaning
- [ ] Filtering your DataFrame
- [ ] Interacting with DataFrames using PySpark SQL
- [ ] Running SQL Queries Programmatically
- [ ] SQL queries for filtering Table
- [ ] Data Visualization in PySpark using DataFrames
- [ ] PySpark DataFrame visualization
- [ ] Part 1: Create a DataFrame from CSV file
- [ ] Part 2: SQL Queries on DataFrame
- [ ] Part 3: Data visualization


### Machine Learning with PySpark MLlib
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/2_big_data_fundamentals/4_ml_with_mllib)
- [ ] Overview of PySpark MLlib
- [ ] PySpark ML libraries
- [ ] PySpark MLlib algorithms
- [ ] Collaborative filtering
- [ ] Loading Movie Lens dataset into RDDs
- [ ] Model training and predictions
- [ ] Model evaluation using MSE
- [ ] Classification
- [ ] Loading spam and non-spam data
- [ ] Feature hashing and LabelPoint
- [ ] Logistic Regression model training
- [ ] Clustering
- [ ] Loading and parsing the 5000 points data
- [ ] K-means training
- [ ] Visualizing clusters


# Cleaning Data with PySpark

### DataFrame details
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/3_cleaning_data_with_pyspark/1_dataframe_details)
- [ ] A review of DataFrame fundamentals and the importance of data cleaning.
- [ ] Intro to data cleaning with Apache Spark
- [ ] Data cleaning review
- [ ] Immutability and lazy processing
- [ ] Immutability review
- [ ] Using lazy processing
- [ ] Understanding Parquet
- [ ] Saving a DataFrame in Parquet format
- [ ] SQL and Parquet

### Manipulating DataFrames in the real world
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/3_cleaning_data_with_pyspark/2_manipulating_dataframes_in_real_world)
- [ ] DataFrame column operations
- [ ] Filtering column content with Python
- [ ] Filtering Question #1
- [ ] Filtering Question #2
- [ ] Modifying DataFrame columns
- [ ] Conditional DataFrame column operations
- [ ] when() example
- [ ] When / Otherwise
- [ ] User defined functions
- [ ] Understanding user defined functions
- [ ] Using user defined functions in Spark
- [ ] Partitioning and lazy processing
- [ ] Adding an ID Field
- [ ] IDs with different partitions
- [ ] More ID tricks

### Improving Performance
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/3_cleaning_data_with_pyspark/3_improving_performance)
- [ ] Caching
- [ ] Caching a DataFrame
- [ ] Removing a DataFrame from cache
- [ ] Improve import performance
- [ ] File size optimization
- [ ] File import performance
- [ ] Cluster configurations
- [ ] Reading Spark configurations
- [ ] Writing Spark configurations
- [ ] Performance improvements
- [ ] Normal joins
- [ ] Using broadcasting on Spark joins
- [ ] Comparing broadcast vs normal joins

### Complex processing and data pipelines
[Link to Notebooks](https://github.com/ayushsubedi/big-data-with-pyspark/tree/main/notebooks/3_cleaning_data_with_pyspark/4_complex_processing_and_data_pipelines)
- [ ] Introduction to data pipelines
- [ ] Quick pipeline
- [ ] Pipeline data issue
- [ ] Data handling techniques
- [ ] Removing commented lines
- [ ] Removing invalid rows
- [ ] Splitting into columns
- [ ] Further parsing
- [ ] Data validation
- [ ] Validate rows via join
- [ ] Examining invalid rows
- [ ] Final analysis and delivery
- [ ] Dog parsing
- [ ] Per image count
- [ ] Percentage dog pixels
