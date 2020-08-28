# Semesterarbeit CAS BGD FS 2020 BFH
> "Semesterarbeit" for CAS BigData at BFH, Switzerland.


These GitHub project contains all Juypter Notebooks which run directly on my laptop. 

The project contains the following Notebooks
<br>
__core__
* 00_00_core.ipynb contains utility functions that are shared

__Trials__
* 00_01_Parquet_Basics.ipynb contains code snippets that show the basics of reading and writing parquet

__Preprocessing__
* 01_01_Download_SEC_Data.ipynb shows how the data can be downloaded with parallelized Spark tasks
* 01_02_Join_SEC_Data.ipynb merges the content of the files inside a zip into one CSV file
* 01_03_Merge_To_Single_Parquet merges all CSV files together into one single Parquet file. Joins with TickerSymbol. Defines datatypes
* 01_04_Filter_And_Partition filters the data: only use primary fin

__Analysis__
* 02_01_Analysis_Whole_Data conducts some basic analysis on the whole dataset

