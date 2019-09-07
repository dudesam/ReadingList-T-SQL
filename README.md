# ReadingList-T-SQL

> Reading list for T-SQL practitioners

## **T-SQL Fundamentals** by Itzik Ben-Gan

[![T-SQL Fundamentals][tsqlfundamentals]](https://amzn.to/2UBPile)

[tsqlfundamentals]:https://images-na.ssl-images-amazon.com/images/I/41HbPnGDM9L._SX408_BO1,204,203,200_.jpg "T-SQL Fundamentals"

### **Effectively query and modify data using Transact-SQL**

> Master T-SQL fundamentals and write robust code for Microsoft SQL Server and Azure SQL Database. Itzik Ben-Gan explains key T-SQL concepts and helps you apply your knowledge with hands-on exercises. The book first introduces T-SQL’s roots and underlying logic. Next, it walks you through core topics such as single-table queries, joins, subqueries, table expressions, and set operators. Then the book covers more-advanced data-query topics such as window functions, pivoting, and grouping sets. The book also explains how to modify data, work with temporal tables, and handle transactions, and provides an overview of programmable objects.

### **Microsoft Data Platform MVP Itzik Ben-Gan shows you how to**

+ Review core SQL concepts and its mathematical roots

+ Create tables and enforce data integrity

+ Perform effective single-table queries by using the SELECT statement

+ Query multiple tables by using joins, subqueries, table expressions, and set operators

+ Use advanced query techniques such as window functions, pivoting, and grouping sets

+ Insert, update, delete, and merge data

+ Use transactions in a concurrent environment

+ Get started with programmable objects–from variables and batches to user-defined functions, stored procedures, triggers, and dynamic SQL

## **T-SQL Window Functions: For data analysis and beyond** by Itzik Ben-Gan

[![T-SQL Window Functions][tsqlwf]](https://amzn.to/314OQyq)

[tsqlwf]:https://images-na.ssl-images-amazon.com/images/I/41Efz%2BZnm-L._SX406_BO1,204,203,200_.jpg "T-SQL Window Functions"

> Most T-SQL developers recognize the value of window functions for data analysis calculation. But window functions can do far more than that, and optimizations in recent versions of SQL Server have made them more powerful than ever. In T-SQL Window Functions: For Data Analysis and Beyond, renowned T-SQL expert Itzik Ben-Gan introduces breakthrough techniques for using window functions to handle many common T-SQL querying tasks with unprecedented elegance and power.

Ben-Gan first explains why window functions can often be a far better solution than traditional predicate-based approaches. Next, using extensive code examples, he guides you through each type of window function: Aggregate, Ranking, Distribution and Offset. You’ll find detailed coverage of ordered set functions (including SQL Server 2017’s STRING_AGG); plus an extensive section on optimization. The book concludes with roughly 100 pages of real T-SQL solutions using window function approaches — including techniques invented by the author and available in no other book.

## **SQL Server Execution Plans** by Grant Fritchey

[![SQL Server Execution Plans][sqlep]](https://amzn.to/2ZDrX8y)

[sqlep]:https://images-na.ssl-images-amazon.com/images/I/51uW5pKrdjL._SX404_BO1,204,203,200_.jpg "SQL Server Execution Plans"

> If a query is performing poorly, and you can't understand why, then that query's execution plan will tell you not only what data set is coming back, but also what SQL Server did, and in what order, to get that data. It will reveal how the data was retrieved, and from which tables and indexes, what types of joins were used, at what point filtering, sorting and aggregation occurred, and a whole lot more. These details will often highlight the likely source of any problem.

I wrote this book with the singular goal of teaching you how to read SQL Server Execution plans It will explain, among many other things, the following: 

+ How to capture execution plans using manual and automatic methods

+ A documented method for reading and interpreting execution plans

+ How common SQL Server objects, such as indexes, views, stored procedures, and so on, appear in execution plans

+ How to control execution plans with hints and plan guides, and why this is a double-edged sword

+ How the Query Store works with, and collects data on, execution plans

With this knowledge, you'll have everything you need to read the execution plan, for any query of your own, regardless of complexity, and understand what it does and what is causing the bad performance. It is still your job to work out how best to fix it, but your new understanding of execution plans will give a much better chance of success!
