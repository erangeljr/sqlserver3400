          +====================================+
          |      DATABASE SYSTEMS PROJECT      |
          |              Phase III:            |
          | Oracle Database Management System  |
          +====================================+

     When you hand me this phase or later of the project, always attach updated
previous phased to it.

Phase III: Create Logical and Physical Database with Oracle DBMS.

1.  Normalization of Your Relations

     (1) Read the chapter on normalization of relation, and ducument the followings

	 a. What is the normallization.
         b. Definitions of the First, Second, Third, and Boyce-Codd Normal Forms.
         c. Describe the problems or Modification Anomalies if relations are not normalized.

     (2) Check your relations

         a. Which normal forms are they in?
         b. Any modification anomaly exists?
         c. Based on your database, make one relation that is on in the first and second
            normal form, but not in the third or Boyce-Codd NF. List the possible anomalies
            regarding the relation you have or you made.

2.  Use Oracle/SQL*PLUS to create, load and query your database. The
following commands should be used or practiced in this phase:

     (1). CREATE TABLE table_name ...;
     (2). CREATE VIEW view_name ...;
     (3). CREATE INDEX idx_name ...;
     (4). INSERT INTO ...
     (5). DROP TABLE ... PURGE;
     (6). DROP VIEW ... ;
     (7). Purge RECYCLEBIN;
     (8). COMMIT;
     (9). ROLLBACK;
     (10). SELECT
     (11). DESC
     (12). System tables such as user_objects, user_indexes, user_tables,
	   tab, col,
     (13). CREATE or REPLACE  FUNCTION ...
     (14). CREATE or REPLACE  PROCEDURE ..
     (15). CREATE or REPLACE  TRIGGER ...
     (16). DROP PROCEDURE | FUNCTION ...
     (17). Read DataLoader.java program, and edit your records based on the
	   format that DataLoader required. Compile (javac DataLoader.java)
	   and run the program (java DataLoader) to load the records into
	   tables. 
     (18). Run the following SQl statements to see what you see:
		select * from tab;
		seelct * from user_objects;
		select * from user_constraints;
     (19). When you see strange table name after you type "select * from tab",
           run command "purge recyclebin" in sqlplus to get rid of them.	   
Notice that: The following may be important for generating the major part
of your report for this assignment.

   (1)	When you create table and define primary or unique key (not foreign
 	key), Oracle creates indexes for the primary key contraints.
	You must put all primary, unique and non-unique indexex in the
       tablespace cs342index.
	To store the primary key and unique key indexes into an designated
	tablespace, use "USING INDEX TABLESPACE" clause in your create table 
	statement.
       To create non-unique indexes and stored index into designated table
       space, use CREATE INDEX command with TABLESPACE clause.
   (2). You may type command interactively first. If there are some
	errors, use command EDIT, and save the corrected command in a file
	using line-mode command "WRITE file_name".
   (3). Use "SPOOL filename" and SPOOL OUT to save all the queries and the
	results on both screen and a file. Document your statement by
	editing the output file. The comments are preceded with two dashes.

3.  Answer all queries listed in phase II.

   Beside the queries listed in phase II, you need to add serveral queries,
   each of them will have one or more of the following features:
	(1) with Aggregate functions.
	(2) with GROUP_BY clause without HAVING clause,
	(3) GROUP_BY clause with HAVING clause,
	(4) with ORDER_BY,
	(5) Arithmetic operators: +, -, *, is NULL, IS NOT NULL
	(6) with outer join.
 	(7) Use SQL*PLUS features such as Title, column formating,
	    break on, set pagesize, save queries results and etc.
	(8) Outer join,
	(9) Subquery

   Use the LIST sqlplus command to display the query in the buffer (
the command you just ran).

4. In your report,

  (1). Normalization of Relations
	1.1 What is normalization? What the 1NF, 2ND, 3NF and BCNF.
       What are the update anormalies? What is the relationship between Normalizations
       and update anormalies? 
       Give or make some some relations in your database which are not normalized, and
       show the possible anomalies that will occur in your data. 
	1.2 Check and document each of every relations to see if it is in the 3rd or
	    Boyce-Codd normal form. 
        List orginal relation and updated relation that were not in the 3rd or BCNF.
  (2). Describe the main purpose of SQL*PLUS and funcationality provided
       by SQL*PLUS.
  (3). Describe schema objects allowed in Oracle DBMS; what are they, and
	the purposes of those object. Also list the schema objects
	that you have created in your project. Descibe the syntax of statements
        for creating database schema objects. Group those statements into
        subsections.
  (4). For each relation, list its relation schema and its contents (relation
       instance), using DESC and SELECT commands to show the relation schema
       and the SELECT statement to show the contents of the relation.
  (5). Write queries designed in previous phase in SQL language. Save the
	SQL statement in a file. Run each if the files to generat the
       report.
       The following SQL features will be used in some of your
       queries (if not, add more new queries to the previious phase):
		- IS [not] NULL,
		-[NOT] EXISTS,
		- GROUP BY and Having,
		- aggregate functions,
		- sub-select statement,
		- create a new table from existing table(s)
		  using CREATE TABLE .... AS SELECT ...
		- outer join.
  (6). Data Loader
	-- Description of Data loading methods: INSERT INTO ... VALUES(...),
	   INSERT INTO ... query , and special programs or DMBS tools for
	   importing data of different format(text mostly) into the database,
	   and exporting database data to files with differnet format.
	-- Description of Java DataLoader Program. Add additional features
	   into the program to make it more user friendly.
	-- Document the features that you have added into the original
	   DataLoader Program.

5. Create a subdirectory with your first initial plus at 5 charaters of
   last name, and other subdirectories to store your SQL statements.

					cs342

		/
	      JDoe 		....
          
	/           \    
   CRT_LD      	  QUERY
     |         	    |
 files for     	All queries
insertions,
creations.