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
