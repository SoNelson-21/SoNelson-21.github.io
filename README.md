# SoNelson-21.github.io

### CS-499 Computer Science Capstone

# List Of Chapters

1. Professional Self-Assessment
2. Introduction
3. Code Review
4. Artifacts & Narratives
- 4a. Software Design and Engineering
- 4b. Algorithms and Data structure
- 4c. Databases
5. Reflection

## 1. Professional Self-Assessment



## 2. Computer Science ePortfolio Introduction

My name is Sebastian Nelson, and I have been in the Computer Science program at Southern New Hampshire University for about two years. During that time, I have learned a lot through both coursework and hands-on projects. Some of the biggest skills I've developed are programming, problem-solving, and understanding how software and algorithms work together. These experiences have helped me become more confident in building and improving software.

Through my CS 499 enhancements, I want to show how my coding, software design, and problem-solving skills have grown. My goal is to create cleaner, more efficient, and more reliable projects that reflect what I've learned throughout the program. These skills support my career goals by preparing me to design, develop, and improve software in a professional setting. They also help me continue growing as a software developer and build a strong portfolio for future opportunities.

## 3. Code Review

In this code review, I will look at three projects that I completed during the Computer Science program. For each project, I will briefly explain what it does, show how it works, review the code, and talk about improvements I plan to make for my ePortfolio.

### Software Engineering and Design
Reviewing my CS 250 TopFiveDest Application, I will explain how the application is organized, walk through the main classes and methods, point out what works well, and discuss how I can improve the design, readability, and organization of the code.

### Algorithms and Data Structures
Reviewing my CS 300 Course Planner, I will explain how the program stores and searches course information, discuss the data structures and algorithms used, and identify ways to make the code more efficient and easier to maintain.

### Databases
Reviewing my CS 360 Event Planning Application, I will show how the app stores and manages user and event information using SQLite, explain the database structure and CRUD operations, and discuss improvements to validation, security, and database organization.

To finish, I will summarize the strengths of each project and explain how the planned enhancements will make them stronger examples of my software engineering, algorithm, and database skills for my professional ePortfolio.

<a href="https://www.dropbox.com/scl/fi/zdpnhgzhs023yanx5q1mv/Milestone-One-Sebastian-Nelson.mov?rlkey=u7wd5iv9dz2uqm9dktm7eos6p&st=cta7urox&dl=0" target="_blank" rel="noopener noreferrer">
  Code Review
</a>

## 4. Artifacts & Narratives

### 4a. Software Design and Engineering

<img width="3000" height="2000" alt="image" src="https://github.com/user-attachments/assets/89b56d7e-06e0-42b1-b4ad-1ee5b846eb51" />

### Artifact and Origin

For Category One, I selected my Top Five Destinations application from CS 250: Software Development Lifecycle. This Java Swing application displays my top five travel destinations with images and descriptions. I chose this artifact because it was one of the first software projects I completed, making it a good opportunity to demonstrate how my software engineering skills have improved throughout the Computer Science program.

### Enhancement Plan

The goal of this enhancement is to improve the application's design, readability, maintainability, and reliability without changing its core functionality.

Enhancements include:
Reorganizing the code into smaller, more readable methods.
Improving formatting, method names, and overall code organization.
Adding JavaDoc comments and inline documentation.
Replacing raw collections with Java generics for better type safety.
Improving the user interface layout.
Adding error handling for missing images and resources.
Reducing repeated code to simplify future maintenance.
Testing each enhancement to ensure existing functionality remains unchanged.
These improvements make the application cleaner, easier to maintain, and more reliable while following software engineering best practices.

### Planned Enhancement Pseudocode

```
START Application

Apply system look and feel
Load destination information

Attempt to load images
IF image loads
    Display image and information
ELSE
    Display error message
END IF

Display destination list

WHEN user selects a destination
    Update image and description
END WHEN

END Application
```

### Skills Demonstrated

This enhancement demonstrates skills in software design, code refactoring, debugging, documentation, Java generics, error handling, user interface improvements, and software testing. Compared to the original project, the enhanced version reflects stronger programming practices by focusing on readability, maintainability, and reliability while preserving the original functionality. One challenge was improving the code without changing how the application worked. Careful testing after each update ensured the program continued to function correctly.

### Course Outcomes Alignment

Course Outcome 3: Demonstrates my ability to improve an existing software solution using software engineering principles, programming standards, and thoughtful design decisions.

Course Outcome 4: Demonstrates my ability to apply programming techniques and development tools to build a cleaner, more reliable, and maintainable software solution.

### Reflection

Revisiting this project showed how much my software engineering skills have grown since taking CS 250. While the original application met the project requirements, this enhancement focuses on professional coding practices, better organization, improved documentation, stronger error handling, and easier maintenance. The final version better represents the skills I have developed throughout the Computer Science program.

### 4b. Algorithms and Data Structures

<img width="2000" height="2000" alt="image" src="https://github.com/user-attachments/assets/f6bfcdb7-2f2e-41eb-ac90-9362520c6f51" />

### Artifact and Origin

For Category Two, I selected my **Course Planner** application from **CS 300: Analysis and Design**. This C++ application reads course information from a file, stores it in a map, displays courses in alphabetical order, and allows users to search for individual courses and view their prerequisites. I chose this artifact because it demonstrates my understanding of algorithms, data structures, file processing, and efficient data management. Revisiting this project gave me the opportunity to apply the skills I have developed throughout the Computer Science program to improve both the performance and maintainability of the application.

### Enhancement Plan

The goal of this enhancement is to improve the efficiency, reliability, and organization of the program while maintaining its original functionality.

Enhancements include:
Improving data validation when loading course information.
Enhancing prerequisite validation to ensure referenced courses exist.
Optimizing search and retrieval using the existing map data structure.
Improving sorting and display of course information.
Refactoring the code into smaller, more maintainable functions.
Improving comments and overall documentation.
Adding stronger input validation and error handling for invalid files and user input.
Testing each enhancement to verify the original functionality remains intact.
These improvements make the application more reliable, easier to maintain, and better demonstrate the effective use of algorithms and data structures.

### Planned Enhancement Pseudocode

```
START Program

Load course file

FOR each course
    Validate course information
    Validate prerequisites
    Store course in map
END FOR

Sort and display courses

IF user searches for a course
    Search map
    IF found
        Display course information and prerequisites
    ELSE
        Display "Course not found"
    END IF
END IF

Repeat until user exits

END Program
```

### a. Skills Demonstrated

This enhancement demonstrates my ability to apply algorithms and data structures to improve an existing application. I strengthened the program by improving data validation, search functionality, code organization, documentation, and error handling while maintaining the original behavior. The project also reinforced the importance of selecting appropriate data structures to improve efficiency, readability, and long-term maintainability.

One of the biggest challenges was improving the program without changing its core functionality. Careful testing throughout the enhancement process ensured that each improvement increased reliability while preserving the original user experience.

### b. Course Outcomes Alignment

Course Outcome 3: Demonstrates my ability to design and evaluate computing solutions by improving an existing application using algorithmic principles, efficient data structures, and thoughtful design decisions.

Course Outcome 4: Demonstrates my ability to apply programming techniques and development tools to build a more efficient, reliable, and maintainable software solution.

### Reflection

Revisiting this project showed how much my understanding of algorithms and data structures has grown since taking CS 300. While the original application successfully met the project requirements, this enhancement focuses on writing cleaner, more efficient, and maintainable code. Improving data validation, search functionality, documentation, and program organization helped create a stronger application that better represents the skills I have developed throughout the Computer Science program.


### 4c. Databases

<img width="2000" height="2000" alt="image" src="https://github.com/user-attachments/assets/dae38a97-6768-4c43-8065-6364e111efc0" />

### Artifact and Origin

For Category Three, I selected my **Event Planning App** from **CS 360: Mobile Architecture and Programming**. This Android application allows users to register, log in, and manage events using a local SQLite database. The app stores user and event information, allowing data to be created, viewed, updated, and deleted throughout the application. I chose this artifact because it best demonstrates my database design and management skills while showing how I can integrate a database into a complete mobile application. Revisiting this project allowed me to apply the knowledge I have gained throughout the Computer Science program to improve the application's functionality, organization, and usability.

### Enhancement Plan

The goal of this enhancement is to improve the application's database structure, data management, and overall user experience while maintaining its original functionality.

Enhancements include:
Expanding the database by adding event date, description, and priority fields.
Improving CRUD (Create, Read, Update, Delete) functionality.
Adding search, filtering, and date-sorting features for stored events.
Improving database organization and data retrieval.
Strengthening input validation and error handling.
Refactoring database code to improve readability and maintainability.
Testing all database operations to ensure existing functionality remains intact.
These enhancements make the application more organized, reliable, and practical while demonstrating stronger database design and management skills.

### Planned Enhancement Pseudocode

```
START Application

Open database connection

IF user creates an event
    Validate event information
    Save event to database
END IF

IF user views events
    Retrieve events
    Sort or filter results
    Display event list
END IF

IF user searches for an event
    Search database
    IF event found
        Display event details
    ELSE
        Display "No results found"
    END IF
END IF

Repeat until user exits

END Application
```

### Skills Demonstrated

This enhancement demonstrates my ability to design, improve, and maintain a database-driven application. I strengthened the application by expanding the database structure, improving CRUD operations, enhancing search and filtering capabilities, and organizing database interactions more effectively. The project also reinforced the importance of integrating a well-designed database with a user-friendly interface while maintaining clean, reliable, and maintainable code.

One of the biggest challenges was updating the database structure without affecting the rest of the application. Careful testing throughout the enhancement process ensured that all database operations continued to function correctly after each improvement.

### Course Outcomes Alignment

Course Outcome 3: Demonstrates my ability to improve a computing solution through better database design, data organization, and application architecture.

Course Outcome 4: Demonstrates my ability to apply mobile development tools and database techniques to create a more reliable, efficient, and maintainable application.

Course Outcome 5: Demonstrates a security mindset by improving data validation, strengthening database interactions, and helping ensure user information is managed safely and reliably.

### Reflection

Revisiting this project showed how much my database and mobile development skills have grown since taking CS 360. While the original application successfully met the project requirements, this enhancement focuses on creating a more organized, reliable, and user-friendly database solution. Expanding the database, improving CRUD functionality, adding search and filtering features, and refining the overall code structure helped create a stronger application that better represents the database and software development skills I have developed throughout the Computer Science program.


## 5. Reflection



