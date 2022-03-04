# Big Data with PySpark

# Building Recommendation Engines with PySpark

### Recommendations Are Everywhere

- [x] Why learn how to build recommendation engines?
- [x] See the power of a recommendation engine
- [x] Power of recommendation engines
- [x] Recommendation engine types and data types
- [x] Collaborative vs content-based filtering
- [x] Collaborative vs content based filtering part II
- [x] Implicit vs explicit data
- [x] Ratings data types
- [x] Uses for recommendation engines
- [x] Alternate uses of recommendation engines.
- [x] Confirm understanding of latent features

### How does ALS work?

- [x] Overview of matrix multiplication
- [x] Matrix multiplication
- [x] Matrix multiplication part II
- [x] Overview of matrix factorization
- [x] Matrix factorization
- [x] Non-negative matrix factorization
- [x] How ALS alternates to generate predictions
- [x] Estimating recommendations
- [x] RMSE as ALS alternates
- [x] Data preparation for Spark ALS
- [x] Correct format and distinct users
- [x] Assigning integer id's to movies
- [x] ALS parameters and hyperparameters
- [x] Build out an ALS model
- [x] Build RMSE evaluator
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
- [x] Filtering numeric fields conditionally
- [x] Adjusting Data
- [x] Custom Percentage Scaling
- [x] Scaling your scalers
- [x] Correcting Right Skew Data
- [x] Working with Missing Data
- [x] Visualizing Missing Data
- [x] Imputing Missing Data
- [x] Calculate Missing Percents
- [x] Getting More Data
- [x] A Dangerous Join
- [x] Spark SQL Join
- [x] Checking for Bad Joins

### Feature Engineering

- [x] Feature Generation
- [x] Differences
- [x] Ratios
- [x] Deeper Features
- [x] Time Features
- [x] Time Components
- [x] Joining On Time Components
- [x] Date Math
- [x] Extracting Features
- [x] Extracting Text to New Features
- [x] Splitting & Exploding
- [x] Pivot & Join
- [x] Binarizing, Bucketing & Encoding
- [x] Binarizing Day of Week
- [x] Bucketing
- [x] One Hot Encoding

### Building a Model

- [x] Choosing the Algorithm
- [x] Which MLlib Module?
- [x] Creating Time Splits
- [x] Adjusting Time Features
- [x] Feature Engineering Assumptions for RFR
- [x] Feature Engineering For Random Forests
- [x] Dropping Columns with Low Observations
- [x] Naively Handling Missing and Categorical Values
- [x] Building a Model
- [x] Building a Regression Model
- [x] Evaluating & Comparing Algorithms
- [x] Understanding Metrics
- [x] Interpreting, Saving & Loading
- [x] Interpreting Results
- [x] Saving & Loading Models
- [x] Final Thoughts

# Machine Learning with PySpark

[Certificate](https://www.datacamp.com/statement-of-accomplishment/course/4a9d2b3a3b3481f9736e402d5e945e3c9c00ebaf)

### Introduction

- [x] Machine Learning & Spark
- [x] Characteristics of Spark
- [x] Components in a Spark Cluster
- [x] Connecting to Spark
- [x] Location of Spark master
- [x] Creating a SparkSession
- [x] Loading Data
- [x] Loading flights data
- [x] Loading SMS spam data

### Classification

- [x] Data Preparation
- [x] Removing columns and rows
- [x] Column manipulation
- [x] Categorical columns
- [x] Assembling columns
- [x] Decision Tree
- [x] Train/test split
- [x] Build a Decision Tree
- [x] Evaluate the Decision Tree
- [x] Logistic Regression
- [x] Build a Logistic Regression model
- [x] Evaluate the Logistic Regression model
- [x] Turning Text into Tables
- [x] Punctuation, numbers and tokens
- [x] Stop words and hashing
- [x] Training a spam classifier

### Regression

- [x] One-Hot Encoding
- [x] Encoding flight origin
- [x] Encoding shirt sizes
- [x] Regression
- [x] Flight duration model: Just distance
- [x] Interpreting the coefficients
- [x] Flight duration model: Adding origin airport
- [x] Interpreting coefficients
- [x] Bucketing & Engineering
- [x] Bucketing departure time
- [x] Flight duration model: Adding departure time
- [x] Regularization
- [x] Flight duration model: More features!
- [x] Flight duration model: Regularisation!

### Ensembles & Pipelines

- [x] Pipeline
- [x] Flight duration model: Pipeline stages
- [x] Flight duration model: Pipeline model
- [x] SMS spam pipeline
- [x] Cross-Validation
- [x] Cross validating simple flight duration model
- [x] Cross validating flight duration model pipeline
- [x] Grid Search
- [x] Optimizing flights linear regression
- [x] Dissecting the best flight duration model
- [x] SMS spam optimised
- [x] How many models for grid search?
- [x] Ensemble
- [x] Delayed flights with Gradient-Boosted Trees
- [x] Delayed flights with a Random Forest
- [x] Evaluating Random Forest
- [x] Closing thoughts



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


