# Big Data with PySpark

# Progress

# Feature Engineering with PySpark

### Exploratory Data Analysis

- [x] Where to Begin
- [x] Where to begin?
- [x] Check Version
- [x] Load in the data
- [x] Defining A Problem
- [x] What are we predicting?
- [x] Verifying Data Load
- [x] Verifying DataTypes
- [x] Visually Inspecting Data / EDA
- [x] Using Corr()
- [x] Using Visualizations: distplot
- [x] Using Visualizations: lmplot

### Wrangling with Spark Functions

- [x] Dropping data
- [x] Dropping a list of columns
- [x] Using text filters to remove records
- [ ] Filtering numeric fields conditionally
- [ ] Adjusting Data
- [ ] Custom Percentage Scaling
- [ ] Scaling your scalers
- [ ] Correcting Right Skew Data
- [ ] Working with Missing Data
- [ ] Visualizing Missing Data
- [ ] Imputing Missing Data
- [ ] Calculate Missing Percents
- [ ] Getting More Data
- [ ] A Dangerous Join
- [ ] Spark SQL Join
- [ ] Checking for Bad Joins

### Feature Engineering

- [ ] Feature Generation
- [ ] Differences
- [ ] Ratios
- [ ] Deeper Features
- [ ] Time Features
- [ ] Time Components
- [ ] Joining On Time Components
- [ ] Date Math
- [ ] Extracting Features
- [ ] Extracting Text to New Features
- [ ] Splitting & Exploding
- [ ] Pivot & Join
- [ ] Binarizing, Bucketing & Encoding
- [ ] Binarizing Day of Week
- [ ] Bucketing
- [ ] One Hot Encoding

### Building a Model

- [ ] Choosing the Algorithm
- [ ] Which MLlib Module?
- [ ] Creating Time Splits
- [ ] Adjusting Time Features
- [ ] Feature Engineering Assumptions for RFR
- [ ] Feature Engineering For Random Forests
- [ ] Dropping Columns with Low Observations
- [ ] Naively Handling Missing and Categorical Values
- [ ] Building a Model
- [ ] Building a Regression Model
- [ ] Evaluating & Comparing Algorithms
- [ ] Understanding Metrics
- [ ] Interpreting, Saving & Loading
- [ ] Interpreting Results
- [ ] Saving & Loading Models
- [ ] Final Thoughts

# Machine Learning with PySpark

### Introduction

- [ ] Machine Learning & Spark
- [ ] Characteristics of Spark
- [ ] Components in a Spark Cluster
- [ ] Connecting to Spark
- [ ] Location of Spark master
- [ ] Creating a SparkSession
- [ ] Loading Data
- [ ] Loading flights data
- [ ] Loading SMS spam data

### Classification

- [ ] Data Preparation
- [ ] Removing columns and rows
- [ ] Column manipulation
- [ ] Categorical columns
- [ ] Assembling columns
- [ ] Decision Tree
- [ ] Train/test split
- [ ] Build a Decision Tree
- [ ] Evaluate the Decision Tree
- [ ] Logistic Regression
- [ ] Build a Logistic Regression model
- [ ] Evaluate the Logistic Regression model
- [ ] Turning Text into Tables
- [ ] Punctuation, numbers and tokens
- [ ] Stop words and hashing
- [ ] Training a spam classifier

### Regression

- [ ] One-Hot Encoding
- [ ] Encoding flight origin
- [ ] Encoding shirt sizes
- [ ] Regression
- [ ] Flight duration model: Just distance
- [ ] Interpreting the coefficients
- [ ] Flight duration model: Adding origin airport
- [ ] Interpreting coefficients
- [ ] Bucketing & Engineering
- [ ] Bucketing departure time
- [ ] Flight duration model: Adding departure time
- [ ] Regularization
- [ ] Flight duration model: More features!
- [ ] Flight duration model: Regularisation!

### Ensembles & Pipelines

- [ ] Pipeline
- [ ] Flight duration model: Pipeline stages
- [ ] Flight duration model: Pipeline model
- [ ] SMS spam pipeline
- [ ] Cross-Validation
- [ ] Cross validating simple flight duration model
- [ ] Cross validating flight duration model pipeline
- [ ] Grid Search
- [ ] Optimizing flights linear regression
- [ ] Dissecting the best flight duration model
- [ ] SMS spam optimised
- [ ] How many models for grid search?
- [ ] Ensemble
- [ ] Delayed flights with Gradient-Boosted Trees
- [ ] Delayed flights with a Random Forest
- [ ] Evaluating Random Forest
- [ ] Closing thoughts

# Building Recommendation Engines with PySpark

### Recommendations Are Everywhere

- [ ] Why learn how to build recommendation engines?
- [ ] See the power of a recommendation engine
- [ ] Power of recommendation engines
- [ ] Recommendation engine types and data types
- [ ] Collaborative vs content-based filtering
- [ ] Collaborative vs content based filtering part II
- [ ] Implicit vs explicit data
- [ ] Ratings data types
- [ ] Uses for recommendation engines
- [ ] Alternate uses of recommendation engines.
- [ ] Confirm understanding of latent features

### How does ALS work?

- [ ] Overview of matrix multiplication
- [ ] Matrix multiplication
- [ ] Matrix multiplication part II
- [ ] Overview of matrix factorization
- [ ] Matrix factorization
- [ ] Non-negative matrix factorization
- [ ] How ALS alternates to generate predictions
- [ ] Estimating recommendations
- [ ] RMSE as ALS alternates
- [ ] Data preparation for Spark ALS
- [ ] Correct format and distinct users
- [ ] Assigning integer id's to movies
- [ ] ALS parameters and hyperparameters
- [ ] Build out an ALS model
- [ ] Build RMSE evaluator
- [ ] Get RMSE

### Recommending Movies

- [ ] Introduction to the MovieLens dataset
- [ ] Viewing the MovieLens Data
- [ ] Calculate sparsity
- [ ] The GroupBy and Filter methods
- [ ] MovieLens Summary Statistics
- [ ] View Schema
- [ ] ALS model buildout on MovieLens Data
- [ ] Create test/train splits and build your ALS model
- [ ] Tell Spark how to tune your ALS model
- [ ] Build your cross validation pipeline
- [ ] Best Model and Best Model Parameters
- [ ] Model Performance Evaluation
- [ ] Generate predictions and calculate RMSE
- [ ] Interpreting the RMSE
- [ ] Do recommendations make sense

### What if you don't have customer ratings?

- [ ] Introduction to the Million Songs Dataset
- [ ] Confirm understanding of implicit rating concepts
- [ ] MSD summary statistics
- [ ] Grouped summary statistics
- [ ] Add zeros
- [ ] Evaluating implicit ratings models
- [ ] Specify ALS hyperparameters
- [ ] Build implicit models
- [ ] Running a cross-validated implicit ALS model
- [ ] Extracting parameters
- [ ] Overview of binary, implicit ratings
- [ ] Binary model performance
- [ ] Recommendations from binary data
- [ ] Course recap

## Introduction to PySpark

[Certificate](https://www.datacamp.com/statement-of-accomplishment/course/4f60910c39332bd0cad02155c50d018b08456f9c)

### Getting to know PySpark

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

- [x]	Machine Learning Pipelines
- [x]	Join the DataFrames
- [x]	Data types
- [x]	String to integer
- [x]	Create a new column
- [x]	Making a Boolean
- [x]	Strings and factors
- [x]	Carrier
- [x]	Destination
- [x]	Assemble a vector
- [x]	Create the pipeline
- [x]	Test vs Train
- [x]	Transform the data
- [x]	Split the data

### Model tuning and selection

- [x] What is logistic regression?
- [x] Create the modeler
- [x] Cross validation
- [x] Create the evaluator
- [x] Make a grid
- [x] Make the validator
- [x] Fit the model(s)
- [x] Evaluating binary classifiers
- [x] Evaluate the model

# Big Data Fundamentals with PySpark

[Certificate](https://www.datacamp.com/statement-of-accomplishment/course/06530532e301ebca7a6b5507637918b1d61592b9)

### Introduction to Big Data analysis with Spark

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

- [x] Abstracting Data with RDDs
- [x] RDDs from Parallelized collections
- [x] RDDs from External Datasets
- [x] Partitions in your data
- [x] Basic RDD Transformations and Actions
- [x] Map and Collect
- [x] Filter and Count
- [x] Pair RDDs in PySpark
- [x] ReduceBykey and Collect
- [x] SortByKey and Collect
- [x] Advanced RDD Actions
- [x] CountingBykeys
- [x] Create a base RDD and transform it
- [x] Remove stop words and reduce the dataset
- [x] Print word frequencies

### PySpark SQL & DataFrames

- [x] Abstracting Data with DataFrames
- [x] RDD to DataFrame
- [x] Loading CSV into DataFrame
- [x] Operating on DataFrames in PySpark
- [x] Inspecting data in PySpark DataFrame
- [x] PySpark DataFrame subsetting and cleaning
- [x] Filtering your DataFrame
- [x] Interacting with DataFrames using PySpark SQL
- [x] Running SQL Queries Programmatically
- [x] SQL queries for filtering Table
- [x] Data Visualization in PySpark using DataFrames
- [x] PySpark DataFrame visualization
- [x] Part 1: Create a DataFrame from CSV file
- [x] Part 2: SQL Queries on DataFrame
- [x] Part 3: Data visualization


### Machine Learning with PySpark MLlib

- [x] Overview of PySpark MLlib
- [x] PySpark ML libraries
- [x] PySpark MLlib algorithms
- [x] Collaborative filtering
- [x] Loading Movie Lens dataset into RDDs
- [x] Model training and predictions
- [x] Model evaluation using MSE
- [x] Classification
- [x] Loading spam and non-spam data
- [x] Feature hashing and LabelPoint
- [x] Logistic Regression model training
- [x] Clustering
- [x] Loading and parsing the 5000 points data
- [x] K-means training
- [x] Visualizing clusters


# Cleaning Data with PySpark

[Certificate](https://www.datacamp.com/statement-of-accomplishment/course/4a9d2b3a3b3481f9736e402d5e945e3c9c00ebaf)

### DataFrame details

- [x] A review of DataFrame fundamentals and the importance of data cleaning.
- [x] Intro to data cleaning with Apache Spark
- [x] Data cleaning review
- [x] Defining a schema
- [x] Immutability and lazy processing
- [x] Immutability review
- [x] Using lazy processing
- [x] Understanding Parquet
- [x] Saving a DataFrame in Parquet format
- [x] SQL and Parquet

### Manipulating DataFrames in the real world

- [x] DataFrame column operations
- [x] Filtering column content with Python
- [x] Filtering Question #1
- [x] Filtering Question #2
- [x] Modifying DataFrame columns
- [x] Conditional DataFrame column operations
- [x] when() example
- [x] When / Otherwise
- [x] User defined functions
- [x] Understanding user defined functions
- [x] Using user defined functions in Spark
- [x] Partitioning and lazy processing
- [x] Adding an ID Field
- [x] IDs with different partitions
- [x] More ID tricks

### Improving Performance

- [x] Caching
- [x] Caching a DataFrame
- [x] Removing a DataFrame from cache
- [x] Improve import performance
- [x] File size optimization
- [x] File import performance
- [x] Cluster configurations
- [x] Reading Spark configurations
- [x] Writing Spark configurations
- [x] Performance improvements
- [x] Normal joins
- [x] Using broadcasting on Spark joins
- [x] Comparing broadcast vs normal joins

### Complex processing and data pipelines

- [x] Introduction to data pipelines
- [x] Quick pipeline
- [x] Pipeline data issue
- [x] Data handling techniques
- [x] Removing commented lines
- [x] Removing invalid rows
- [x] Splitting into columns
- [x] Further parsing
- [x] Data validation
- [x] Validate rows via join
- [x] Examining invalid rows
- [x] Final analysis and delivery
- [x] Dog parsing
- [x] Per image count
- [x] Percentage dog pixels


