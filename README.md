# parquet-notes

## How to import parquet files
- project: spud, ga4
```
SELECT * FROM `spud-og-prod.fusion.ga4` WHERE date >= "2023-07-10" AND date <= "2023-07-11"
```
- save local CSV to 10-11.csv

## File system commands
```
# Delete the "fusion" folder 
# dbutils.fs.rm("/FileStore/tables/fusion", True)
# Check that the partitions folders are created successfully
# dbutils.fs.ls("/FileStore/tables/fusion")
```
