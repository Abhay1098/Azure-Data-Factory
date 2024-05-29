# Azure-Data-Factory
This repository contains the solutions of requirements

Requirement 1: Source file(csv file) is in blob storage account need to move it to SQL server table.

Solution: to copy the file or move it from blob storage account to sql server table, we need to create a PIPELINE through a Azure Data Factory(ADF)
We would use:-
1.	Linked Service at source side
2.	Data set at source side
3.	Copy data Activity
4.	Data set at sink side
5.	Linked Service at Sink side

Through the Linked Service at source side, we would access the source(i.e. blob storage). It acts like a KEY. 
Through the Linked Service at Sink side, we would access the Azure Account Storage(i.e. SQL server table)

