---
layout: default
title: "CS410: Advanced Databases"
course_description: "An advanced study of topics in database systems, including query optimization, concurrency, data warehouses, object-oriented extensions, and XML."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Advanced SQL** <span id="1"></span> 
*In this unit, we will look at SQL DML commands beyond the basic
“select,“join,” and “group by,” as you will sometimes find it useful to
filter a group using a having clause and/or to perform subqueries, which
can be used to compare two results set in special ways.  We will also
study the self-join as well as several set-theoretic operators.*

**Unit 1 Time Advisory**  
This unit should take you 13 hours to complete.  
  
 ☐    Subunit 1.1: 2 hours  
  
 ☐    Subunit 1.2: 2 hours  
  
 ☐    Subunit 1.3: 3 hours  
  
 ☐    Subunit 1.4: 2 hours  
  
 ☐    Subunit 1.5: 2 hours  
  
 ☐    Subunit 1.6: 2 hours

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:
-   Demonstrate an understanding of how to use the more advanced
    filtering SQL commands.
-   Illustrate how subqueries can be used to compare the results in
    separate groups.
-   Describe the properties of set-theoretic operators.

**1.1 Relational Algebra Review and Join Commands** <span
id="1.1"></span> 
-   **Lecture: Gonzaga University: Shawn Bowers’ “Relational Algebra and
    Complex SQL”**
    Link: Gonzaga University: Shawn Bowers’ “[Relational Algebra and
    Complex
    SQL](http://www.cs.gonzaga.edu/%7Ebowers/courses/cpsc421-f09/)”
    (PDF)  
      
     Instructions: On this webpage, scroll down to “Lecture 3” for an
    introduction to Relational Algebra and an introduction to the Join
    Commands in SQL.  Click on the hyperlink for “Lecture 3” to open the
    PDF document, and read slides 3 through 33 (pages 2-17).  This
    lecture covers subsection 1.1.  As you read this lecture be sure to
    think of how the necessary mathematical operations are likely to
    affect the outcome of your database actions.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**1.2 Additional Join Operations** <span id="1.2"></span> 
-   **Lecture: Gonzaga University: Shawn Bowers’ “Relational Algebra and
    Complex SQL”**
    Link: Gonzaga University: Shawn Bowers’ “[Relational Algebra and
    Complex
    SQL](http://www.cs.gonzaga.edu/%7Ebowers/courses/cpsc421-f09/)”
    (PDF)  
      
     Instructions: On this webpage, scroll down to “Lecture 4” for
    advanced topics in Relational Algebra and more advanced join
    commands.  Click on the hyperlink for “Lecture 4” to open the PDF
    document, and read slides 3 through 48 (pages 3-24).  This lecture
    covers section 1.2, 1.3, and the inclusive sub-subsections.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**1.2.1 SELF Join** <span id="1.2.1"></span> 
-   **Reading: TutorialsPoint.com: “SQL SELF JOINS”**
    Link: TutorialsPoint.com: “[SQL SELF
    JOINS](http://www.tutorialspoint.com/sql/sql-self-joins.htm)”
    (HTML)  
      
     Instructions: Please read the entirety of this webpage for a solid
    overview of the SELF JOINS command and how it is used to join a
    table.  Practice utilizing the SQL commands using MySQL or another
    available SQL database.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2.2 FULL Joins** <span id="1.2.2"></span> 
-   **Reading: TutorialsPoint.com: “SQL FULL JOINS”**
    Link: TutorialsPoint.com: “[SQL FULL
    JOINS](http://www.tutorialspoint.com/sql/sql-full-joins.htm)”
    (HTML)  
      
     Instructions: Please read the entirety of this webpage for a solid
    overview of the FULL JOINS command and how it is used to achieve a
    full join of the left and right outer joins of a table. Practice
    utilizing the SQL commands using MySQL or another available SQL
    database.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.3 Set-Theoretic Operators** <span id="1.3"></span> 
-   **Reading: Tom Jewett’s Database Design with UML and SQL, 3rd
    Edition: “Union and Minus”**
    Link: Tom Jewett’s *Database Design with UML and SQL, 3<sup>rd</sup>
    Edition:* “[Union and
    Minus](http://www.tomjewett.com/dbdesign/dbdesign.php?page=setops.php#maincontent)”
    (HTML)  
      
     Instructions: Please read this webpage in its entirety for an
    overview of using the Union, Union All, Minus, and Intersect
    operators in SQL.  This material covers section 1.4 and its
    subsections.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.3.1 Union** <span id="1.3.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.3.*

**1.3.2 Minus** <span id="1.3.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.3.*

**1.3.3 Intersect** <span id="1.3.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.3.*

**1.4 The HAVING Clause** <span id="1.4"></span> 
-   **Lecture: Gonzaga University: Shawn Bowers’ “Complex SQL”**
    Link: Gonzaga University: Shawn Bowers’ “[Complex
    SQL](http://www.cs.gonzaga.edu/%7Ebowers/courses/cpsc421-f09/)”
    (PDF)  
      
     Instructions: On this webpage, scroll down to “Lecture 5” for
    advanced topics in Relational Algebra and more advanced join
    commands.  Click on the hyperlink for “Lecture 4” to open the PDF
    document, and read slides 3 through 31 (pages 3-16).  This lecture
    covers section 1.4, 1.5, and the inclusive sub-subsections.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

-   **Reading: TutorialsPoint.com: “SQL HAVING Clause”**
    Link: TutorialsPoint.com: “[SQL HAVING
    Clause](http://www.tutorialspoint.com/sql/sql-having-clause.htm)”
    (HTML)  
      
     Instructions: Please read the entirety of this webpage for a solid
    overview of the basics of using the HAVING clause command in SQL. 
    Practice utilizing the SQL commands using MySQL or another available
    SQL database.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.5 Subqueries** <span id="1.5"></span> 
*Note:  This subunit is covered by the reading assigned beneath subunit
1.4 titled Complex SQL.*

**1.5.1 The IN Operator** <span id="1.5.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.4.  Practice using the In Operator using MySQL or another available
SQL database.*

**1.5.2 The EXISTS Operator** <span id="1.5.2"></span> 
 *Note: This subunit is covered by the reading assigned beneath subunit
1.4.  Practice using the EXISTS Operator using MySQL or another
available SQL database.*

**1.5.3 Correlated Subqueries** <span id="1.5.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.4.  Practice using the Correlated Subqueries using MySQL or another
available SQL database.*

**1.5.4 When to Use Subqueries vs. Joins** <span id="1.5.4"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.4. * *Compare results from Subqueries versus Joins using MySQL or
another available SQL database.*

**1.6 Views** <span id="1.6"></span> 
-   **Reading: Tom Jewett’s Database Design with UML and SQL, 3rd
    Edition: “SQL Technique: Views and Indexes”**
    Link: Tom Jewett’s *Database Design with UML and SQL, 3rd Edition:*
    “[SQL Technique: Views and
    Indexes](http://www.tomjewett.com/dbdesign/dbdesign.php?page=views.php)”
    (HTML)  
      
     Instructions: Please read this webpage in its entirety for an
    overview of views and indexes in SQL.  This material covers section
    1.6 and all of its subsections.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.6.1 Definition** <span id="1.6.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.6.*

**1.6.2 Roles** <span id="1.6.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.6.*

**1.6.3 Indexes** <span id="1.6.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
1.6.*


