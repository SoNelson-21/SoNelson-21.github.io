# SoNelson-21.github.io
### Sebastian Nelson
### CS-499 Computer Science Capstone

# List Of Chapters

1. Professional Self-Assessment
2. Code Review
3. Artifacts & Narratives
- 3a. Software Design and Engineering
- 3b. Algorithms and Data structure
- 3c. Databases
4. Reflection

## 1. Professional Self-Assessment

Hello, and welcome to my Computer Science Capstone ePortfolio. My name is Sebastian Nelson, and I have been a student in the Computer Science program at Southern New Hampshire University for the past two years. Throughout the program, I have gained valuable experience through coursework and hands-on projects that have strengthened my skills in programming, software design, problem-solving, and algorithm development. These experiences have helped me become more confident in designing, building, and improving software.

Working through this program and creating this ePortfolio has given me the chance to look back at everything I have learned and see how much I have grown as a computer science student. Every course introduced new concepts that helped me build on what I already knew, and each project challenged me to think differently when solving problems. Looking back at my earlier work for this capstone also showed me how much my coding style, software design, and problem-solving skills have improved over time. It has reinforced my goal of pursuing a career in software development while continuing to grow my skills in data science.

Throughout the program, I learned that being a software developer is about much more than writing code. Several courses involved working with classmates, which helped me improve my teamwork and collaboration skills. I learned how to communicate ideas, listen to feedback, and work together to complete projects successfully. I also gained experience communicating with stakeholders by designing applications around user requirements and explaining technical decisions in a way that was easy to understand.

My coursework gave me a strong understanding of data structures and algorithms and how they affect the performance of software. I learned how choosing the right data structure can make an application more efficient and easier to maintain. Software engineering courses taught me how to design applications, improve existing code, test software, and write cleaner, more organized programs. I also developed database skills by designing databases, writing SQL queries, and creating applications that can store, retrieve, and manage data effectively.

Another important topic throughout the program was security. I learned about user authentication, input validation, and secure coding practices that help protect applications and user data. These experiences helped me understand that good software should not only work correctly but should also be reliable, secure, and easy to maintain.

Creating this ePortfolio helped bring everything together. Instead of simply collecting past assignments, I revisited previous projects and found ways to improve them using the knowledge I have gained throughout the program. This process helped me recognize areas where I had grown and gave me more confidence in my ability to evaluate, improve, and maintain software.

This portfolio includes three enhanced artifacts that represent the main areas of computer science covered throughout the program: Software Engineering and Design, Algorithms and Data Structures, and Database Design and Development. Each artifact includes the original project, the enhanced version, a narrative explaining the improvements I made, and a reflection on what I learned during the enhancement process.

The Software Engineering and Design artifact demonstrates my ability to improve software structure, organization, and maintainability. The Algorithms and Data Structures artifact highlights my ability to solve problems more efficiently by selecting better algorithms and organizing data effectively. The Database Design and Development artifact demonstrates my understanding of creating and improving databases that support reliable and efficient applications. Together, these artifacts show how the different areas of computer science work together to create software that is functional, efficient, and easier to maintain.

Overall, this ePortfolio reflects the knowledge and experience I have gained throughout my time at Southern New Hampshire University. It demonstrates not only the technical skills I have developed but also my growth as a problem solver and software developer. As I begin my career, I plan to continue learning new technologies, improving my skills, and building software that makes a positive impact. I hope this portfolio reflects both the progress I have made throughout the Computer Science program and my commitment to continuing to grow as a computer science professional.

## 2. Code Review

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

## 3. Artifacts & Narratives

### 3a. Software Design and Engineering

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

- Demonstrates my ability to improve an existing software solution using software engineering principles, programming standards, and thoughtful design decisions.

- Demonstrates my ability to apply programming techniques and development tools to build a cleaner, more reliable, and maintainable software solution.

### Reflection

Revisiting this project showed how much my software engineering skills have grown since taking CS 250. While the original application met the project requirements, this enhancement focuses on professional coding practices, better organization, improved documentation, stronger error handling, and easier maintenance. The final version better represents the skills I have developed throughout the Computer Science program.

### 3b. Algorithms and Data Structures

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

- Demonstrates my ability to design and evaluate computing solutions by improving an existing application using algorithmic principles, efficient data structures, and thoughtful design decisions.

- Demonstrates my ability to apply programming techniques and development tools to build a more efficient, reliable, and maintainable software solution.

### Reflection

Revisiting this project showed how much my understanding of algorithms and data structures has grown since taking CS 300. While the original application successfully met the project requirements, this enhancement focuses on writing cleaner, more efficient, and maintainable code. Improving data validation, search functionality, documentation, and program organization helped create a stronger application that better represents the skills I have developed throughout the Computer Science program.


### 3c. Databases

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

- Demonstrates my ability to improve a computing solution through better database design, data organization, and application architecture.

- Demonstrates my ability to apply mobile development tools and database techniques to create a more reliable, efficient, and maintainable application.

- Demonstrates a security mindset by improving data validation, strengthening database interactions, and helping ensure user information is managed safely and reliably.

### Reflection

Revisiting this project showed how much my database and mobile development skills have grown since taking CS 360. While the original application successfully met the project requirements, this enhancement focuses on creating a more organized, reliable, and user-friendly database solution. Expanding the database, improving CRUD functionality, adding search and filtering features, and refining the overall code structure helped create a stronger application that better represents the database and software development skills I have developed throughout the Computer Science program.

## 4. Reflection

Putting this ePortfolio together gave me the chance to look back at everything I have learned throughout the Computer Science program and see how much I have improved. Going back to my older projects showed me how much my coding style, problem-solving, and overall approach to software development have changed since I first started. It was rewarding to take projects I completed earlier in the program and make them cleaner, more efficient, and easier to maintain.

The three enhanced artifacts highlight the areas I have grown the most in: software engineering, algorithms and data structures, and databases. Together, they show the skills I have developed throughout the program and the progress I have made as a programmer. Completing this portfolio has given me more confidence in my abilities and has prepared me for the next step after graduation. I know there is still a lot to learn, but I am excited to continue building my skills and begin my career in software development and data science.
