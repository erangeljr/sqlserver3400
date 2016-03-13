          +======================================+
          |      DATABASE SYSTEMS PROJECT        |
          |               Phase I:               |
          |  Fact-Finding, Infomration Gethering |
          |     and Conceptual Database Design   |
          +======================================+

     In the database system class, each student in the class will
work on a database application project. The project will design and
implement the software for a business or a enterprise he/she choose.

     The project will divided into several phases. Each student will
document the entire project with code writing, and present the project 
present the project to the class during the process of implementation
of the project.

     The project for this course is divided into serveral steps/phases including

	1. Fact-finding and data gethering: The data views and
	   operations on data collected and documented, and
	   are organized by user groups in this phase.
	2. Conceptual database design: Using E-R Modeling format the
	   information gethered in step 1.
	3. Logical Database Design: Convert a conceptual E-R DB to
	   relational database.
	4. Creation of Database with Oracle DBMS System: Create tables
	   indexes, views, triggers, stored procedures and etc. Load data.
	5. Interfaces for User Group(s): Design and implement end user
	   program(s) for specific group(s) of users in C#. The interface
           could be window-based local application or web-based internet
           application 

    For this phase, you will complete two things

        1.1 Information finding
        1.2 Conceptual database design.

    Study, conduct and documnent information finding and conceptual database
design. The detailed requiremts for what need to be documented are described
section 1.1 and 1.2. 

	1.1 Fact-Finding Techniques and Information Gethering

       Brief generate desciption of sections from 1.1.1 to 1.1.5

	   1.1.1   Introduction to Enterprise/Organization: Description on the
               business; what the business is doing, and its activities.
	   1.1.2 Description Fact-Fining Techniques; Describe the fact-finding
               methods you have used to gether the data, and the operations
               on data such as who entering what data, and what reports will
               be generated from the database.
	   1.1.3 The part of enterprise you are designing conceptual database
               for. Your database may not cover the entire enterprise.
               Describe major entity set and relationship sets that you will
               include in your database.
       1.1.4 Itemized descriptions of Entity sets and relationship sets: 
               including their names, meaning, attribute names and detail
               properties of each attributes, cardialities and participation
               constraints of relationship.
	   1.1.5  User Groups, Data views and Operations: Types of users who will
               use the database, which part of database a group of users can
               access. Which operations (add, remove, and change, reporting)
               are allowed for each of user groups.
              You can do 1.1.5 in final phase.


	1.2 Conceptual Database Design

       Brief generate desciption of sections from 1.2.1 to 1.2.3.

	   1.2.1 Entity Set Desciption

		Entity UVW:
			* name (use intuitive name
			* description: what is the purpose of the entity
			  type, what information are held in the entities
			  of the relationship type, and other information
			  about the entities in the set (such the frequencies
			  of insertion, deletions, and updates).
			* Attribute description
				- name
				- descriptin
				- domain/type
				- value-range
				- default value
				- null value allowed or not?
				- unique?
				- single or multiple-value
				- Simple of Composite
				
			* candidate keys:
			* primary key:
			* Strong/Weak Entity
			* Fields to be indexed

	 	Entity XYZ:
			...

	   1.2.2 Relationship Set Description

		Relationship ...:
			* Name (use intuitive name)
			* description: What is the relationship type for, the
			   purpose of relations, what are the entities involved,
			   meaning of each descriptive data field. Multiplicities
			   and mapping cardinality.
			* Entity set involved
			* Mapping cardinality
			* Desciptive field
			* Participation Constraint:
				Partial/optional or total/mandatory

	   1.2.3 Related Entity Set

	       Describe the following and point out entity types and relationships
	       that are derived with the specialization/generalization process.

		* Specialization/Generalization Relationships(is-A)
		   	Participation constraint
			Disjoint constraint
		* Aggregation/has-relationship
			Composite
		
	   1.2.4 E-R Diagram

		Label the entity types with attributes, relationship types,
		multiplicities.