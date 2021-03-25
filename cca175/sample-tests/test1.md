## Problem 1
You have been given an input parquet data with HDFS link `/raw_zone/covid19/tmp/cert/data1/parquet`

<b>Output requirements:</b>

Place the result data in the HDFS directory `/gold_zone/cert/<your_username>/problem1`

Use text format for the output files.

The output should contains `total_cases` and `total_deaths` each `Location` on 1 Jan. 2021.

Sample output:

|Location   |total_cases   |total_deaths   |
|---|:---:|---:|
|Vietnam   | 1474  | 35  | 
