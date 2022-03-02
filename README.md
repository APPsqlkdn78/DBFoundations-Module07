### Name:   Andrew Palmer 
### Date:   March 1, 2022
### Course: Foundations of Databases & SQL Programming
### https://github.com/APPsqlkdn78/DBFoundations-Module07

### Assignment 07

**Introduction**

This week involved an introduction to SQL functions. The following briefly discusses when functions are used, along with the differences among different function types. 

**Explain when you would use a SQL UDF**

A user defined function or “UDF” like other database objects, can be stored in a database to avoid having to rewrite code. The function can be saved to limit inputs and defined structures of the inputs and ultimate types of outputs it creates. You can also define permissions to indicate who can access and use the functions. Functions are therefore handy tools to allow database admins to provide structured tools for database users while also allowing database admins ease and security pertaining to database users access to data. 

**Explain the differences between Scalar, Inline, and Multi-Statement Functions**

A scalar function in takes one or more parameters and returns a single value. Unlike scalar functions, Inline table valued functions (ITVFs) and Multi-statement functions (MSTVFs) can retrieve multiple values although their syntax differs. With inline, your statement will read “Returns Table” and the definition of the table will be based on the function’s “Select” statement. There is no need to specify the structure of the return table. With Mulit-Statement Functions the “Returns” syntax specifies the structure of the return table. A table variable is used to store and accumulate the rows that are returned as the value of the function. In addition, ITVFs do not use the “Begin/End” syntax while MSTVFs do use it. 

**Summary**

Functions are clearly a critical tool in database administration. Using functions is an effective method of retrieving data with specific input and output parameters.
