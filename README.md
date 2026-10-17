# CS-300-Data-Structures-and-Algorithms
Data structures and algorithms portfolio showcasing runtime analysis and custom sorting implementations.

# Computer Science Portfolio Reflection

## Project Overviews
*   **Project One Artifact:** Data Structure Run-Time and Memory Analysis Document
*   **Project Two Artifact:** Alphanumeric Course Sorting and Printing Program

---

## Reflection

### 1. What was the problem you were solving in the projects for this course?
In these projects, the goal was to develop an efficient academic advising system capable of managing, sorting, and printing a comprehensive list of Computer Science courses. The system required handling data parameters seamlessly while ensuring fast lookup times and structured outputs so advisors and students could view course schedules in a logical, alphanumeric format.

### 2. How did you approach the problem? Consider why data structures are important to understand.
I approached the problem by evaluating how different data structures manage information behind the scenes. Understanding data structures is vital because picking the wrong one can lead to severe performance bottlenecks as data scales. 
* For **Project One**, I analyzed how different data structures impact memory and processing footprints (e.g., Vectors, Hash Tables, and Binary Search Trees).
* For **Project Two**, I implemented a structure—such as a Binary Search Tree—and paired it with a sorting algorithm to ensure the system could print the courses in perfect alphanumeric order efficiently.

### 3. How did you overcome any roadblocks you encountered while going through the activities or project?
During development, I hit a roadblock when handling edge cases like empty data inputs and parsing prerequisite files correctly. I overcame this by breaking the problem into smaller, testable modules. I used debugging tools to trace variable states, added verbose console logs, and referenced documentation to isolate the exact logical breakdown before refactoring the code.

### 4. How has your work on this project expanded your approach to designing software and developing programs?
This work has shifted my focus from simply writing code that *works* to writing code that is *efficient*. I now actively design software with algorithmic complexity (Big-O notation) in mind from the very beginning. Instead of choosing the easiest data structure to implement, I select data structures based on the expected scale of the data and the frequency of specific operations, like search vs. insertion.

### 5. How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
It reinforced the extreme value of clean coding standards, logical modular design, and robust documentation. By breaking functions down into single-responsibility components and naming variables intentionally, I ensured the codebase remains highly readable. This modular design makes the application adaptable; for instance, if the university decides to switch the underlying data storage from a local file to a live database, the core sorting and rendering logic will remain intact with minimal modifications.
