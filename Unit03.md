---
layout: default
title: "CS410: Advanced Databases"
course_description: "An advanced study of topics in database systems, including query optimization, concurrency, data warehouses, object-oriented extensions, and XML."
next: ../Unit04
previous: ../Unit02
---
**Unit 3: Query Optimization** <span id="3"></span> 
*Queries written in SQL do not always run efficiently.  However, there
are a number of techniques that you can use to optimize them.  In this
unit, we will first look at indexes.  When tables are indexed on certain
fields, the relational database management system can take advantage of
quicker retrieval time when searching through the table.  Once you have
a firm understanding of indexes, please move on to the discussion of
query optimization.*

**Unit 3 Time Advisory**  
This unit should take you 13 hours to complete.  
  
 ☐    Subunit 3.1: 3 hours  
  
 ☐    Subunit 3.2: 3 hours  
  
 ☐    Subunit 3.3: 4 hours  
  
 ☐    Subunit 3.4: 3 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Describe the stages of Query Processing.
-   Explain the various types of Query Processing algorithms available
    in Database Management.
-   Understand the fundamentals of Query-Based Optimization techniques.

**3.1 Stages in Query Processing** <span id="3.1"></span> 
-   **Lecture: YouTube: Indian Institute of Technology Bangladore: S.
    Srinath’s “Lecture 14: Query Processing and Optimization I**
    Link: YouTube: Indian Institute of Technology Bangladore: S.
    Srinath’s “[Lecture 14: Query Processing and Optimization
    I](http://www.youtube.com/watch?v=GYQZpYEaNvk)” (YouTube)  
      
     Instructions: Please view the following presentation in its
    entirety (56:41 minutes) for a detailed understanding and
    introduction to query processing and optimization.  This lesson
    covers sections 3.1 and inclusive subsections (3.1.1 through
    3.1.4.).  As you view this lecture please be sure to take notes
    outlining the differences between the various aspects of the Query
    Plan Language.  Determine the strengths and weaknesses between the
    Logical and Physical Query Plan and languages.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.1.1 Logical and Physical Query Plan** <span id="3.1.1"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.1.*

**3.1.2 Intermediate Query Plan Language** <span id="3.1.2"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.1.*

**3.1.3 Physical Query Plan Language** <span id="3.1.3"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.1.*

**3.1.4 One-Pass Algorithms** <span id="3.1.4"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.1.*

**3.2 Query Processing Algorithms** <span id="3.2"></span> 
-   **Lecture: YouTube: Indian Institute of Technology Bangladore: S.
    Srinath’s “Lecture 15: Query Processing and Optimization II”**
    Link: YouTube: Indian Institute of Technology Bangladore: S.
    Srinath’s “[Lecture 15: Query Processing and Optimization
    II](http://www.youtube.com/watch?v=FqUPoZzU834)” (YouTube)  
      
     Instructions: Please view the following presentation in its
    entirety (56:55 minutes) for a detailed understanding and
    introduction to query processing and optimization with a focus on
    various algorithms that can be used.  This lesson covers sections
    3.2 and inclusive subsections (3.2.1 through 3.2.5.).  As you view
    this lecture please be sure to understand the differences between
    the various query processing and optimizing algorithms.  Determine
    which scenarios would be optimal for using a single-pass versus a
    multi-pass algorithm, etc.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.2.1 Single-pass Algorithms and Limitations** <span
id="3.2.1"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.2.*

**3.2.2 Multi-pass Algorithms** <span id="3.2.2"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.2.*

**3.2.3 Sort Based Algorithms** <span id="3.2.3"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.2.  
*

**3.2.4 Hash Based Algorithms** <span id="3.2.4"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.2.  
*

**3.2.5 Index Based Algorithms** <span id="3.2.5"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.2.*

**3.3 Query Plan Execution** <span id="3.3"></span> 
-   **Lecture: YouTube: Indian Institute of Technology Bangladore: S.
    Srinath’s “Lecture 16: Query Processing and Optimization III**
    Link: YouTube: Indian Institute of Technology Bangladore: S.
    Srinath’s “[Lecture 16: Query Processing and Optimization
    III](http://www.youtube.com/watch?v=HaDe3ILXfSY)” (YouTube)  
      
     Instructions: Please view the following presentation in its
    entirety (57:19 minutes) for a detailed understanding and
    introduction to query processing and optimization with a focus Query
    plan execution.  This lesson covers sections 3.3 and inclusive
    subsections (3.3.1 through 3.3.3).  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.3.1 Index Based Algorithm Details** <span id="3.3.1"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.3.*

**3.3.2 Rewriting Parse Trees** <span id="3.3.2"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.3.*

**3.3.3 Cost Estimation and Heuristics** <span id="3.3.3"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.3.*

**3.4 Cost-Based Query Optimization** <span id="3.4"></span> 
-   **Lecture: Gonzaga University: Shawn Bowers’ “Query Optimization
    Lecture 18”**
    Link: Gonzaga University: Shawn Bowers’ “[Query Optimization Lecture
    18](http://www.cs.gonzaga.edu/%7Ebowers/courses/cpsc421-f09/)”
    (PDF)  
      
     Instructions: On this webpage, scroll down to “Lecture 18” on Query
    Optimization.  Click on the hyperlink for “Lecture 18” to open the
    PDF document, and read slides 3 through 20 (pages 2-10) for a
    detailed overview on cost-based query optimization techniques.  This
    lecture covers subsection 3.4.1 and 3.4.2.  As you read this lecture
    be sure to understand the importance of utilizing the statistical
    methods for query optimization.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**3.4.1 Statistics** <span id="3.4.1"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.4. *

**3.4.2 Histograms and Wavelets** <span id="3.4.2"></span> 
*Note: This subunit is covered by the lecture assigned beneath subunit
3.4.  Slide 12 begins the introduction for this sub-subunit.*


