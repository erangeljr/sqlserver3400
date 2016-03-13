          +====================================+
          |      DATABASE SYSTEMS PROJECT      |
          |              Phase  V:             |
          |       Graphics User Interface      |
          |      Design and Implementation     |
          +====================================+

Phase V of database system class is the last phase, and will be
use to replace the final exam. Students will hand in the complete
project document including the final and previous phases.

Phase V: Design and implement a graphics user interface for your
	 database project in Java or C# with MS Visual Studio .net.

         An example C# UGI program is available at
		www.cs.csubak.edu/~wang/CS342/Gradebook_Nov_23_05.zip

         An example Java GUI program will be given later.

1. General Description

    In this phase, the student will

   1. List operations for each group (or type) of your database project
      users. The operations are based on your investigations in phase I.
      In addition to add/remove/update, the operations such as generating
      /viewing (daily, monthly and yearly) reports, filling out sales/orders
      (using existing products, items), assigning students/emplyoees to
      classs/probjects and etc. should be more important than the trivial
      operations.
   2. Pick the requested operations for ONE group of users, design a user
      interface with little coding at this step. However, some operation,
      picked to implement, should involve multiple tables. For example,
      enrolling a student into a class will use student and course
      tables, and add record into rollment relationship table.
   3. Create views for each group, and/or stored subprogram that will
      simplify the front-end coding, and or to avoid sending SQL statements
      from front-end to DMBS server, and to void make SQL statements directly
      based on base table(s).
   4. Implement your GUI program using selected GUI development
      environment. Using existing records in some tables, and adding new
      record into relationship table based on the existing records is
      important. Generating the daily, weekly, and/or monthly report are
      encouraged.
   5. Hand in the final phase and the entire project documentation on 
      the final exam period. The project documentation should includ
      all phases including previous phases and final phase.

2. General Guidelines

   1. Use menu, toolbar with tool tip, and status bar and try to
      avoid to use button in the main interface. Make sure your system
      should not require use ID nor password to run the program for
      the major user group interface.
   2. Put the similar funcationalities into one submenu.
   3. Make toolbar buttons for the most frequently used menu items.
   4. Use different form/window or tab control/component for displaying
      different data and for data insertion.
   5. Reports built on data in the database are important parts for
      any business, and should be part of your design and implementation.
	

3. In your report,

   The following must be included:

   1. Description of Daily acitivities of the uer group. Group
      the functionalities for each user group and itemize the groups
      and the functionalities requested within each group. Reporting,
      filing records using existing records, are important daily
      activities than simple insertion/deletion/update for many
      businesses.
   2. Relations, views and subprograms related to the activities.
   3. Screen shots of your menu and display, and descriptions about
      the screen shots.
   4. Description of your code:(DON'T make a copy of your entire code)
	-- Major steps of designing a user interface.
	-- Descriptions of major classes such as database connection, 
	   data adapter, command object, data table, data sets.
	   The description for each class includes
		-- purposes
		-- major data and function members
	-- Major features of your GUI program
	-- How do you about learning a new development tool and writing
	   code in new language.
   5. Describe the major steps of designing and implementing a database
      applicatoin including what you do in each step and what you have
      learnt in each step.
   6. The documentation and code implementations are equally important
      when the final phase is graded.

   7. (Added Fall 2012) Enbedded Questions (Important! Please make sure that
       you have answers for the following questions.

        In this course, in what degree do you think you have the achieved
	each of following 4 outcomes? Your answer is between 1 (lowest)
        and 10 (highest). Each member of the team should have his/her
        own answers.
   8. Zipe your code/programs and send written file and zipped code together.

        ------------------------------------------------------+------------------
    							      |  Members' 
	Outcome	                                              |  Answers
    							      |  btw 1 & 10 
        ------------------------------------------------------+------------------
    							      | 
    							      |  member 1's answer
	(3b) An ability to analyze a problem, and identify and|
	define the computing requirements and specifications  |------------------
	appropriate to its solution.			      |  member 2's answer
							      |
        ------------------------------------------------------+------------------
    							      | 
	(3e) An ability to design, implement and evaluate a   |
	computer-based system, process, component, or         |
	program to meet desired needs. An ability to	      |------------------
	understand the analysis, design, and implementation   |
        of a computerized solution to a real-life problem.    |
							      | 
        ------------------------------------------------------+------------------
    							      | 
	(3f) An ability to communicate effectively with a     |
	range of audiences. An ability to write a technical   |
	document such as a software specification white       |------------------
	paper or a user manual.				      |
    							      | 
        ------------------------------------------------------+------------------
    							      | 
	(3j) An ability to apply mathematical foundations,    |
	algorithmic principles, and computer science theory   |
	in the modeling and design of computer-based systems  |------------------
	in a way that demonstrates comprehension of the       |
	tradeoffs involved in design choices.                 |
    							      | 
        ------------------------------------------------------+-------------------