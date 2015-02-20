---
layout: default
title: "CS410: Advanced Databases"
course_description: "An advanced study of topics in database systems, including query optimization, concurrency, data warehouses, object-oriented extensions, and XML."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Stored Procedures and Triggers** <span id="2"></span> 
*Much of the work of database retrieval can be done on the server side
as opposed to the client side.  The server can execute commands more
efficiently and is capable of sending only the result set back to the
client, rather than sending the entire data set back and forth between
client and server.  In this unit, we will look at stored procedures, or
blocks of code stored and executed on the server.  We will also look at
triggers, which are blocks of code that execute on the server when
certain events occur, such as the addition or deletion of data from a
table.  Lastly, we will study rights when running a stored procedure.*

**Unit 2 Time Advisory**  
This unit should take you 9 hours to complete.  
  
 ☐    Subunit 2.1: 3 hours  
  
 ☐    Subunit 2.3: 3 hours  
  
 ☐    Subunit 2.4: 3 hours

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Describe how to use stored procedure in Relational Database
    Management Systems.
-   Illustrate how stored functions can be used in Relational Database
    Management Systems.
-   Describe the properties of constraints and triggers in SQL.
-   Explain the difference between Definer versus Invoker Rights.

**2.1 Stored Procedures and Their Usage in Relational Database
Management Systems** <span id="2.1"></span> 
-   **Reading: College of San Mateo: Bob Timlin’s “Chapter 18: Stored
    Procedures, Functions & Chapter 17: Prepared Statements”**
    Link: College of San Mateo: Bob Timlin’s “[Chapter 18: Stored
    Procedures, Functions & Chapter 17: Prepared
    Statements](http://www.timlin.net/csm/cis363/)” (PDF)  
      
     Instructions: Please scroll down to week 3/8/2011 with the pdf file
    titled “Chapter 18: Stored Procedures, Functions & Chapter 17:
    Prepared Statements.”  Click on the appropriate link to open the PDF
    file.  Please read this document in its entirety (42 pages).  This
    reading will provide and appropriate overview of using Stored
    Procedures and Functions in MySQL Server.  This reading covers
    topics outlined in sections 2.1, 2.2, and 2.3 of this course.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Duke University: Oracle MySQL Reference Manual 5.1:
    “18.1: Stored Procedures and the Grant Table”**
    Link: Duke University: *Oracle MySQL Reference Manual 5.1:* “[18.1:
    Stored Procedures and the Grant
    Table](http://www.cs.duke.edu/csl/docs/mysql-refman/stored-procedures.html#stored-procedure-privileges)”
    (HTML)  
      
     Instructions: Please read the entirety of sections 18.1 and 18.2
    for an overview of stored procedures and stored procedure syntax in
    RDMS.  This material covers sections 2.1, 2.2, and all corresponding
    subsections.  As you read please keep in mind the effects that
    stored procedures are likely to have on the Database System.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**2.2 Stored Procedures** <span id="2.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.1.*

**2.2.1 Structure of a Procedure** <span id="2.2.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.1.  
*

**2.2.2 Calling a Procedure** <span id="2.2.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.1.  
*

**2.2.3 Examples** <span id="2.2.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.1.*

**2.3 Stored Functions** <span id="2.3"></span> 
-   **Reading: Duke University: Oracle MySQL Reference Manual 5.1:
    “18.3: Stored Procedures, Functions, Triggers, and
    LAST\_INSERT\_ID()”**
    Link: Duke University: *Oracle MySQL Reference Manual 5.1:* “[18.3:
    Stored Procedures, Functions, Triggers, and
    LAST\_INSERT\_ID()”](http://www.cs.duke.edu/csl/docs/mysql-refman/stored-procedures.html#stored-procedure-last-insert-id)”
    (HTML)  
      
     Instructions: Please read the entirety of sections 18.3 through
    18.5 for an overview of stored functions, triggers, and definer and
    invoker rights in RDMS.  This material covers sections 2.3, 2.4,
    2.5, and all corresponding subsections.  As you read compare and
    contrast the results that can be obtained utilizing Stored Functions
    in a Database System.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.3.1 Differences between a Function and Procedure** <span
id="2.3.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunits
2.1 and 2.3.  
*

**2.3.2 Calling a Function** <span id="2.3.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunits
2.1 and 2.3*  
 **

**2.3.3 Examples** <span id="2.3.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunits
2.1 and 2.3.*

**2.4 Constraints and Triggers** <span id="2.4"></span> 
-   **Reading: Connexions: Nguyen Kim Anh’s “Structured Query
    Language”**
    Link: Connexions: Nguyen Kim Anh’s [“Structured Query
    Language”](http://cnx.org/content/m28255/latest/) (PDF)  
      
     Instruction: This reading gives an overview of SQL, including
    constraints in SQL, which are used to ensure database data
    integrity.  
      
     Reading this article and taking notes should take approximately 1
    hour.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution 3.0
    License](http://creativecommons.org/licenses/by/3.0/). It is
    attributed to Connexions, and the original version can be
    found [here](http://cnx.org/content/m28255/latest/).

-   **Reading: w3resource: “SQL Constraints”**
    Link: w3resource: [“SQL
    Constraints”](http://www.w3resource.com/sql/creating-and-maintaining-tables/creating-table-constraint.php)
    (PDF)  
      
     Instruction: This article gives SQL syntax and examples for
    constraints.  
      
     Reading of the linked material and taking notes should take
    approximately 1 hour.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US).
    It is attributed to w3resource, and the original version can be
    found [here](http://www.w3resource.com/sql/creating-and-maintaining-tables/creating-table-constraint.php).

-   **Reading: Toad World: Oracle Community Wiki: “Triggers – Tutorial”
    (HTML) and “Trigger Development – Example”**
    Link: Toad World: Oracle Community Wiki: [“Triggers –
    Tutorial”](http://www.toadworld.com/platforms/oracle/w/wiki/2203.tutorial.aspx)
    (HTML) and [“Trigger Development –
    Example”](http://www.toadworld.com/platforms/oracle/w/wiki/2223.trigger-development-example-trgt3.aspx)
    (HTML)  
        
     Instruction: A trigger consists of code that is executed when a
    predefined event occurs at the database, schema, view, or table
    level. Constraints are simpler than triggers, and are defined at the
    column or table level, and only check for data integrity. The first
    article illustrates constraints and triggers supported by Oracle.
    The  second article provides a trigger example.  
        
     Reading of the linked materials and taking notes should take
    approximately 1 hour.  
        
     Terms of Use: These resources are licensed under a [Creative
    Commons Attribution-NonCommercial-ShareAlike 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US).
    They are attributed to DBPedia, and the original versions can be
    found [here](http://dbpedias.com/wiki/Oracle:Triggers_-_Tutorial)
    and
    [here](http://dbpedias.com/wiki/Oracle:Trigger_Development_-_Example).

**2.4.1 Purpose** <span id="2.4.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.4.*

**2.4.2 Constraints in SQL** <span id="2.4.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.4.*

**2.4.3 Structure of a Trigger** <span id="2.4.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.4.*

**2.5 Definer vs. Invoker Rights** <span id="2.5"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
2.3.  
*


