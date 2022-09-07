
## Print Schema of dataframe
demand_df.printSchema()

## Get all distinct values for a column in a dataframe
demand_data.select('line_item_status').distinct().show()

## Select specific columns in DF
demand_df.select("line_item_id", "demand_type", "cost_type").show()



