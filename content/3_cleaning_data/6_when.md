# When

```
# Add a column to voter_df for a voter based on their position
voter_df = voter_df.withColumn('random_val',
    when(voter_df.TITLE == 'Councilmember', F.rand())
    .when(voter_df.TITLE == 'Mayor', 2)
    .otherwise(0))

# Show some of the DataFrame rows
voter_df.show()

# Use the .filter() clause with random_val
voter_df.filter(voter_df.random_val==0).show()
```
