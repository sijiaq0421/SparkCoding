# SparkCoding
Best practices for performance

https://medium.com/teads-engineering/spark-performance-tuning-from-the-trenches-7cbde521cf60

tips - ensure sufficient partitioning exists, 
reduce the amount of shuffling that occurs by using filters early, 
use parquet files for predicate pushdown and faster access, 
use caching and broadcast variables to a good extent
