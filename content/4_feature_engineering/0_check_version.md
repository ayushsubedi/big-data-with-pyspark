# Check version

```
# Return spark version
print(spark.version)

# Return python version
import sys
print(sys.version_info)
```
# Load data

```
# Read the file into a dataframe
df = spark.read.parquet('Real_Estate.parq')
# Print columns in dataframe
print(df.columns)
```
# EDA

```
# Select our dependent variable
Y_df = df.select(['SALESCLOSEPRICE'])

# Display summary statistics
Y_df.describe().show()
```

# Validation
```
def check_load(df, num_records, num_columns):
  # Takes a dataframe and compares record and column counts to input
  # Message to return if the critera below aren't met
  message = 'Validation Failed'
  # Check number of records
  if num_records == df.count():
    # Check number of columns
    if num_columns == len(df.columns):
      # Success message
      message = "Validation Passed"
  return message

# Print the data validation message
print(check_load(df, 5000, 74))
```
