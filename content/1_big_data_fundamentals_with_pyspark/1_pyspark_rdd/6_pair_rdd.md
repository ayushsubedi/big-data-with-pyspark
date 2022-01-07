# RDD of key value pairs

- most real data are key/value
- each row mapa to one or more value
- pair RDD is a special data structure
- create from key-val tuple
- create from regular RDD

# Transformation
## reduceByKey()
- transformation combines values with the same key
- runs parallel
- transformation and not action

## sortByKey()
- operations orders pair RDD by kjey

## groupByKey()
- groups all values with the same key

## join()
- joins two pair RDD based on key
