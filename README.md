# Semesterarbeit CAS BGD FS 2020 BFH
> "Semesterarbeit" for CAS BigData at BFH, Switzerland.


These GitHub project contains all Juypter Notebooks which run directly on my laptop. 

The project contains the following Notebooks
<br>
__core__
* 00_00_core.ipynb contains utility functions that are shared

__UseCase 00 "Trials"__
* 00_01_Parquet_Basics.ipynb contains code snippets that show the basics of reading and writing parquet

__UseCase 01 "BalanceSheet"__
* 01_01_Download_SEC_Data.ipynb Shows how the data can be downloaded with parallelized Spark tasks
* 01_02_Join_SEC_Data.ipynb Joins the content of the files inside a zip into one CSV file
* 01_03_Merge_To_Single_Parquet Merges all CSV files together into one single Parquet file. Joins with TickerSymbol. Defines datatypes
* 01_04_Analysis_Whole_Data conducts Some basic analysis on the whole dataset
* 01_05_Filter_And_Partition Filters the data: only use primary financial informations and data of companies traded at NASDAQ or NYSE
* 01_06_Pivot_BS_Data Pivots the BalanceSheet data from its vertical form into a horizontal form



