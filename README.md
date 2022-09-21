# drill-notes
Drill Notes


Drill does not support parquet timestamp.  A conversion must be performed
> ```select CONVERT_FROM(timestamp_field, 'TIMESTAMP_IMPALA') as abc from a_table```
