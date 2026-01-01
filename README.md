### Capstone Table of Contents
-[Full Project Code Review (Binary Search Tree & MongoDB Dashboard)](#code-review-for-cs-499-capstone-artifact-enhancements)<br>
-[Enhancement One](#enhancement-one)<br>
-[Enhancement Two](#enhancement-two)<br>
-[Enhancement Three](#enhancement-three)<br>
-[Course Outcome Completion](#course-outcome-completion)<br><br>

### Project Description
The project requires 3 enhancements of artifacts from the software engineering program at Southern New Hampshire University. <br>
The artifacts chosen must be enhanced to meet: 
1. Software Engineering & Design
2. Data Structures & Algorithms
3. Databases

The artifacts must also meet the course outcomes:
1.  Employ strategies for building collaborative environments that enable 
diverse audiences to support organizational decision-making in the field of 
computer science.  

2.	Design, develop, and deliver professional-quality oral, written, and 
visual communications that are coherent, technically sound, and appropriately 
adapted to specific audiences and contexts.  

3.	Design and evaluate computing solutions that solve a given problem 
using algorithmic principles and computer science practices and standards 
appropriate to its solution while managing the trade-offs involved in design 
choices.  

4.	Demonstrate an ability to use well-founded and innovative techniques, 
skills, and tools in computing practices for the purpose of implementing computer 
solutions that deliver value and accomplish industry-specific goals.

5.	Develop a security mindset that anticipates adversarial exploits 
in software architecture and designs to expose potential vulnerabilities, 
mitigate design flaws, and ensure privacy and enhanced security of data and 
resources.<br><br>
[Course Outcome Completion](#course-outcome-completion)<br><br>

Two artifacts were chosen to perform these enhancements:
1. Binary Search Tree conversion into an AVL self-balancing tree with added user functionality
2. Animal Shelter Dashboard using MongoDB and Python script conversion to SQLite

### Code Review for CS-499 Capstone Artifact Enhancements
The code review will explain the purpose of both original artifacts, showcasing the code and its functionality.  
It will also assess the code for vulnerabilities or flaws, reviewing concepts such as structure, documentation/readability, variables/naming conventions, arithmetic operations, loops, branches, and defensive/secure programming.  
Then the enhancements are explained, forming a relationship between the skills used and the outcomes achieved for the course by the artifact enhancements.
<br><br>
[Full Project Code Review (Binary Search Tree & MongoDB Dashboard)](https://www.youtube.com/embed/KDOPncTitjU)

### ENHANCEMENT ONE
#### Software Engineering & Design
This enhancement takes the original Binary Search Tree program, which is designed to load courses from a 
.csv file and push them into a binary search tree data structure (this makes search time complexity O(log n)).
The enhancement performed allows a user to create a custom course from the menu options as well as delete a course
from the Binary Search Tree list.
<br> <br>
[Binary Search Tree Enhancement One](https://github.com/AnthonyBaratti/EnhancementOne)
<br> <br>
====Enhancement One Contents==== <br>
- Original BinarySearchTree C++ Program <br>
- Enhanced BinarySearchTree C++ Program with user functionality <br>
- README file <br>
- Artifact Enhancement Narrative


### ENHANCEMENT TWO
#### Data Structures & Algorithms
This enhancement takes the Binary Search Tree one step further. The added user functionality could
destabilize the tree (making it unbalanced, or "heavy"), degrading the search time complexity from 
O(log n) to O(n). Creating self-balancing algorithms helps maintain the search time complexity at O(log n)
while deletes and inserts are being performed.
<br> <br>
[Binary Search Tree Enhancement Two](https://github.com/AnthonyBaratti/EnhancementTwo)
<br><br>
====Enhancement Two Contents==== <br>
- Original BinarySearchTree C++ Program <br>
- Enhanced BinarySearchTree C++ Program with self-balancing algorithms <br>
- README file <br>
- Artifact Enhancement Narrative


### ENHANCEMENT THREE
#### Databases
This enhancement takes a user dashboard for filtering animal types and displaying them in a data table with a selectable  
row. The filtered data is also displayed in a pie chart as well as a geo-location interactive map. The original artifact  
uses CRUD operations with MongoDB via two python scripts, one for the CRUD operations and one for the Dash layout. The  
enhancement will convert the database from online MongoDB to offline local storage using SQLite 3.
<br> <br>
[Animal Shelter Dashboard Enhancement Three](https://github.com/AnthonyBaratti/EnhancementThree)
<br> <br>
====Enhancement Three Contents==== <br>
- Original AnimalShelterArtifact Python Program using MongoDB <br>
- Enhanced AnimalShelterArtifact Python Program using SQLite3 with main.exe <br>
- README file<br>
- Artifact Enhancement Narrative<br>
- Grazioso Salvare Application v1.0 (dist.zip)<br>

### Course Outcome Completion
[Review Course Outcome List](#project-description)
#### Enhancement One - Binary Search Tree User Functionality
**====Course Outcomes Achieved====**<br>
(1). Being able to articulate  the features advantages and disadvantages (such as search time complexity vs. overhead) between the data structures (BST vs. AVL) can help support decision-making in the computer science field. For example, an AVL tree requires more overhead (extra resources due to more work being performed), and is useful if there are a lot of adding and deleting of nodes, whereas a standard BST is useful for quick searches if it is prebalanced and will not be modified (adding or deleting nodes). Since we will be adding user functionality to accomodate usefulness, these comparisons must be addressed.<br><br>
(3). Understanding the design and implementation of search trees is vital for determining when to develop specific structures. Moreover, the trade-offs are case-appropriate. For example, if we are going to populate the tree once and never modify it, then an AVL tree may not be the best solution. If our data is extrememly unbalanced (an example would be that the first "root" node is last in an alphabetical list, then all proceeding nodes will be down the left branch with no right branch) a BST would not be the proper solution. Understanding the case allows us to evaluate and design a solution to solve the given problem using the appropriate algorithmic standards. <br><br>
(4). Understanding and planning are important skills to possess. Being able to create universal pseudocode that can be modified to fit any programming language is a great way to showcase using well-founded and innovative techniques that can help accomplish industry-specific goals. <br><br>
(5). Validating user input to ensure that it is accurate (or denying it when it is not) is one of many solutions concerning security. Ensuring that proper input has been received (such as ensuring that the courses object has at LEAST a name and ID) can help prevent out of bounds access of objects in the tree. With data validation techniques, we can demonstrate security awareness to reduce vulnerabilities. Encapsulating data is also a skill that is helpful (such as wrapping many private functions in a few accessible public functions) in keeping the logic hidden, only exposing what is necessary to the public facing side of the application. This helps reduce potential exploitation of the code, keeping variables in their appropriate scope so that the data is not exposed or accessed unnecessarily (intentionally or not).

#### Enhancement Two - Conversion from BST to Self-balancing AVL Tree
**====Course Outcomes Achieved====**<br>
(1). Building the appropriate algorithm structure can provide ogranizational decision-making. Knowing when and how to implement a specific data structure can help provide the best solution. For example, using an AVL tree is best when there will be frequent inserts and deletes. But if a pre-balanced data set is going to be used, and there won't be many (or any) inserts or deletes, a BST is the best choice. Providing evidence allows stakeholders to make informed decisions. <br><br>
(2). Communicating these data designs (such as portability, use case, and time/space complexity), as well as the trade-offs, can be shown through oral presentations and visual representations. <br><br>
(3). Evaluating which solution is best, how it is properly implemented, and the practices behind the solutions can be presented. This ensures that all available options are reviewed, while applying practical solutions (i.e., BST vs. AVL).<br><br>
(4). Properly applying the techniques for the scenario (many inserts and deletes with a self-balancing algorithm) can achieve industry-specific goals (O(log n) search time complexity). Using well-founded methods can deliver precision accuracy (such as testing and debugging), increasing the value of the program. <br><br>
(5). Encapsulating functionality within private methods can hide the inner workings of the program. This can help reduce vulnerabilities by restricting unnecessary access to functionality. Adding a dependency check ensures that classes that are prerequisites to other classes are not deleted, which adds to the integrity of the application through secure coding measures.

#### Enhancement Three - Animal Shelter Dashboard Conversion from MongoDB to SQLite3
**====Course Outcomes Achieved====**<br>
(1). Refactoring code to SQLite allows for the database to be run locally and stay lightweight, which can help reduce overhead and requires minimal setup for functionality. This helps to foster a collaborative environment where diverse audiences can easily operate and manage the program.<br><br>
(3). By redesigning the CRUD operations for SQLite, we can manage small and agile local applications via a web browser with an HTML graphical user interface. While this would not be ideal for multiple locations, it would work perfectly for strictly single on-site locations. Evaluating requirements is a crucial step towards designing and implementing appropriate computing solutions while managing their trade-offs.<br><br>
(4). By combining Dash libraries and extensions with Python, SQLite, and HTML coding, we have utilized tools to increase efficiency to achive the goals of the system. <br><br>
(5). By scripting the SQL clause format into CRUD operations appropriately (such as “?” as value placeholders), we can mitigate any potential for SQL injection. While the data being entered is predefined (i.e., radio buttons prevent users from directly inputting text), the appropriate security measure of using placeholders to build the initial table showcases security awareness. Furthermore, keeping the database localized (saved as a .db file), we can restrict access from external sources. This achieves a security mindset for SQLite3 conversion. Also, a test script has been provided to ensure the CRUD operations work as intended, testing the application for complete functionality of the read function on the dashboard. This helps reveal and fix any bugs using the errors and callbacks developer tab (in the web browser), as well as monitoring the GET/POST procedures revealed in the command window during operation.<br><br>
