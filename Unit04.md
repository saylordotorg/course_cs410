**Unit 4: Concurrency and Recovery** <span id="4"></span> 
*Database management systems must be able to support concurrency—that
is, they must be able to support multiple users and processes accessing
the same records in a table.  Modern database management systems handle
concurrency in a variety of ways, including through the use of locking
and versioning mechanisms.   Database management systems must also be
able to ensure transaction consistency and recover from catastrophic
failures.  In this unit, we will look at methods of ensuring that
systems are capable of concurrency and recovery.*

**Unit 4 Time Advisory**  
This unit should take you 13 hours to complete.  
  
 ☐    Subunit 4.1: 4 hours  
  
 ☐    Subunit 4.2: 0.5 hour  
  
 ☐    Subunit 4.3: 4 hours  
  
 ☐    Subunit 4.7: 4.5 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Describe the stages and properties of transactions.
-   Explain the concepts involved with serializability and the
    serializability theorem.
-   Demonstrate an understanding of the actions involved in concurrency
    control.

**4.1 Transactions and the ACID Property of Transactions** <span
id="4.1"></span> 
-   **Reading: Yale University: Avi Silberschatz, et al.’s “15:
    Transactions”**
    Link: Yale University: Avi Silberschatz, et al.’s “[15:
    Transactions](http://codex.cs.yale.edu/avi/db-book/db4/slide-dir/index.html)”
    (PDF or PPT)  
      
     Instructions: Click on the link above, scroll down to “Part 5:
    Transaction Management,” and click on the "PPT" or “PDF” hyperlink
    for the section labeled “15. Transactions.”   Please view the entire
    lecture slides (46 slides total) that cover transaction properties
    and serializability.  The selected slides cover sections 4.1 and
    4.2.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of the Pacific: Michael Doherty’s
    “Transactions and Serializability”**
    Link: University of the Pacific: Michael Doherty’s “[Transactions
    and
    Serializability](http://www1.pacific.edu/~mdoherty/comp163/lectures/index.htm)”
    (PDF or PowerPoint)  
      
     Instructions: Click on the link above, scroll down to Chapter 17,
    and click on the “PDF” or “PPT” hyperlink for the section labeled
    “Transactions and Serializability.”   Please view the entire lecture
    slides (39 total) for an additional understanding of transaction
    properties and serializability.  The selected slides cover sections
    4.1 and 4.2.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**4.2 Serializability and the Serializability Theorem** <span
id="4.2"></span> 
-   **Reading: Carnegie Melon University: Gregory Kesden’s “Lecture
    16”**
    Link:  Carnegie Mellon University: Gregory Kesden’s “[Lecture
    16](http://www.andrew.cmu.edu/course/15-446/applications/ln/lecture16.html)”
    (HTML)  
        
     Instructions: Please read through the entire webpage for lecture
    notes on serializability.  Be sure to grasp a good understanding of
    the subcomponents that make up the serializability theorem. 
    Determine the factors that are likely to affect the outcome of the
    schedule.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.3 Two-Phase Locking** <span id="4.3"></span> 
-   **Reading: Yale University: Avi Silberschatz, et al.’s “16:
    Concurrency Control”**
    Link: Yale University: Avi Silberschatz, et al.’s “[16: Concurrency
    Control](http://codex.cs.yale.edu/avi/db-book/db4/slide-dir/index.html)”
    (PDF or PowerPoint)  
      
     Instructions: Click on the link above, scroll down the webpage to
    “Part 5: Transaction Management,” and click on the “PDF” or “PPT”
    hyperlinks to download the section labeled “16. Concurrency
    Control.”  Please view the entire lecture slides (79 slides total)
    that cover two-phase locking timestamps, deadlocks, and multiversion
    concurrency control.  The selected slides cover sections 4.3 through
    4.6 and all appropriate subsections.  As you read this lecture
    please be sure to gain a detailed understanding of the mechanism and
    locks that affect concurrency control.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**4.3.1 Aggressive and Conservative Schedulers** <span
id="4.3.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.3.2 Basic Two-Phase Locking** <span id="4.3.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.3.3 Locking Performance** <span id="4.3.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.4 Timestamps** <span id="4.4"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.5 Deadlocks** <span id="4.5"></span> 
**4.5.1 Definition of a Deadlock** <span id="4.5.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.5.2 Deadlock Prevention** <span id="4.5.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.5.3 Deadlock Avoidance** <span id="4.5.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.6 Multiversion Concurrency Control** <span id="4.6"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.3.  *

**4.7 Recovery** <span id="4.7"></span> 
-   **Reading: Yale University: Avi Silberschatz et al.’s “17: Recovery
    System”**
    Link: Yale University: Avi Silberschatz, et al.’s “[17: Recovery
    System](http://codex.cs.yale.edu/avi/db-book/db4/slide-dir/index.html)”
    (PDF or PowerPoint)  
      
     Instructions: Click on the link above, scroll down to “Part 5:
    Transaction Management,” and select the “PDF” or “PPT” link for the
    section labeled “17. Recovery System.”  Please view the entire
    lecture slides (81 slides total) that cover two-phase locking
    timestamps, and deadlocks.  The selected slides cover section 4.7
    and all appropriate subsections (4.7.1 through 4.7.4).   As you read
    through this lecture please be sure to determine the components that
    are likely to affect the recovery of a database systems.  Reading
    this lecture should give you a detailed understanding of the types
    of failures that can occur and how they can be corrected.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above

**4.7.1 Types of failures** <span id="4.7.1"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.7.*

**4.7.2 Checkpoints** <span id="4.7.2"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.7.*

**4.7.3 Undo/Redo** <span id="4.7.3"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.7.*

**4.7.4 Rollforward/Rollback** <span id="4.7.4"></span> 
*Note: This subunit is covered by the reading assigned beneath subunit
4.7.*


