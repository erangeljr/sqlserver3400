          +====================================+
          |      DATABASE SYSTEMS PROJECT      |
          |              Phase IV:             |
          | Oracle Database Management System  |
          |          PL/SQL Component          |
          +====================================+

     When you hand me this phase, attach updated E-R diagram and relational
schema with it..

Phase IV: Stored Subprograms, Packages and Triggers.

1. General Description

  In this phase, you are going to study Oracle PL/SQL, discuss what are
stored procedures and functions, how to create package, and trigger, and
what are the purposes of those types of object in DBMS. You are also asked
to write some stored subprograms and triggers.

  SQL/Plus is the interface to created stored procedures, functions, triggers
and packages. SQL/Plus is not an interface that will give you very helpful
error when you create some schema objects. Make sure you type a couple of lines
of code each time, and compile it.

  The "SHOW ERRORS" command can will give more detailed information when errors
occur.  The syntax or show-errors commands is

	SHOW ERRORS [ { FUNCTION | PROCEDURE | PACKAGE | PACKAGE BODY |
			TRIGGER | VIEW | TYPE | TYPE BODY | DIMENSION |
			JAVA SOURCE | JAVA CLASS } [schema.]name]

2. Coding Requirements

   A. Write the following stored procedure or function in Oracle PL/SQL:

	(1) Create three stored procedures or functions

       -- A stored procedure for inserting a new record into
	      one of your tables. The field values are passed to the
	   procedure through the input parameters.
	   -- A stored procedure for deleting a existing record
	      based on the primary key of your selected table.
	   -- A stored function which returns average of a numerical
	      fields of highest or lowest N records where N is the
	      parameter for the function.

    (2) Write three triggers

        One for deletion and update, one "instead of" trigges which
        implement at least two to three level cascaded update and deletions.
        
        Given two tables, Department and Employee, the DID in employee table
        is the foreign key indiating which departmen a employee is working
        for. 

        -- Define a "before update DID trigger on department table to 
           update DID in employee table to new DID to.
        -- Create a delete trigger for cascaded deletion also. Make sure you
           backup your data.
        -- Create a view involved two to three tables, and define a "INSTEAD OF"
           trigger so that when you update the view, the update will be perform by
           trigger, and the updates will be performed on base table.
    (3) Put all stored procedures, functions and trigger into one package.

2. In your report,

	The following is the list of contents that you will have in your
report for phase IV. You must organize the contents into sections and
subsections and number them.

   A. Oracle PL/SQL

    - What is PL/SQL, stored procedures/functions, and purposes
      and benefits of using stored procedures over sending SQL statements
      from front-end/client software to DBMS server.
	- PL/SQL program structure, control statements, cursors,
	- What is a stored procedure and Syntax of creating a
	  stored procedure.
	- What is a stored function and Syntax of creatoing a
	  stored function.
	- What is a package and Syntax of creatoing a package.
	- What is a trigger and Syntax of creatoing a trigger.
		  
   B. Oracle PL/SQL Subprograms
	
    Test codes done in 1, and show your results of your codes.
    Document your code and the experiences of writing stored procedures.

   C. PL/SQL-Like Tools in Microsoft SQL Sever and MySQL DBMS

     - Use internet or libarary resources to find out what are Microsoft SQL
       Server'(Transact-SQL) and MySQL's ways of writing stored procedures.
	 - Study and report the similarities and differenences of creating Stored
       procedures/functions among those three DBMS (Oracle, MS SQL Server and MySQL)
       regarding to their syntax of selective-statements, repetitive-statements,
       subprogram structures, and parameter passing methods.