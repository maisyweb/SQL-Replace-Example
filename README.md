# SQL-Replace-Example
An example of how to find and replace strings with SQL Server

UPDATE tableName
SET URL = replace(URL,'xxxxx.co.uk','xxxxx.com')
WHERE 1 =1 
