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
4. Course Outcomes Alignment
5. Reflection

## 1. Professional Self-Assessment

Hello, and welcome to my Computer Science Capstone ePortfolio. My name is Sebastian Nelson, and I have been a student in the Computer Science program at Southern New Hampshire University for the past two years. Throughout the program, I have gained valuable experience through coursework and hands-on projects that have strengthened my skills in programming, software design, problem-solving, and algorithm development. These experiences have helped me become more confident in designing, building, and improving software.

Working through this program and creating this ePortfolio has given me the chance to look back at everything I have learned and see how much I have grown as a computer science student. Every course introduced new concepts that helped me build on what I already knew, and each project challenged me to think differently when solving problems. Looking back at my earlier work for this capstone also showed me how much my coding style, software design, and problem-solving skills have improved over time. It has reinforced my goal of pursuing a career in software development while continuing to grow my skills in data science.

Throughout the program, I learned that being a software developer is about more than writing code. Several courses gave me experience working with classmates, sharing ideas, reviewing feedback, and making decisions as a team. These experiences taught me that communication is important when different people are working toward the same goal. I also learned how to think about stakeholder requirements when designing software and how to explain technical decisions in a way that someone without the same technical background can understand. My code review for this capstone also gave me experience looking at existing software, identifying problems, and explaining why certain changes would improve the final product.

My coursework gave me a strong understanding of data structures and algorithms and how they affect the performance of software. I learned how choosing the right data structure can make an application more efficient and easier to maintain. Software engineering courses taught me how to design applications, improve existing code, test software, and write cleaner, more organized programs. I also developed database skills by designing databases, writing SQL queries, and creating applications that can store, retrieve, and manage data effectively.

Security was another important topic throughout the program. I learned that security should be considered while designing and developing software instead of only after a program is finished. Through my coursework, I gained experience with areas such as authentication, input validation, secure coding practices, and protecting stored information. I also learned to think about what could happen when a program receives unexpected or invalid input and how proper validation and error handling can reduce those risks. When improving my projects, I tried to consider these issues by validating information before it was processed or stored and by improving error handling. These experiences helped me develop a stronger security mindset and understand that software should not only work correctly but should also protect its data and users.

Other courses throughout the program also helped me develop skills beyond the three artifacts included in this portfolio. For example, in CS 465, I worked with a full-stack application using technologies such as MongoDB, Express, Angular, and Node.js. This gave me experience working with different parts of an application and understanding how the front end, back end, database, and APIs work together. Experiences like this helped prepare me to work with larger applications and strengthened my interest in software development and data science.

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

### Artifact and Origin

For Category One, I selected my Top Five Destinations application from CS 250: Software Development Lifecycle. This Java Swing application displays my top five travel destinations with images and descriptions. I chose this project because it was created earlier in my Computer Science program and gave me a good opportunity to go back and improve my original work using the skills I have learned since then.

### Enhancement Plan

For this enhancement, my main goal was to make the code cleaner, more organized, and easier to maintain without changing the main purpose of the application.

Improvements made include:

* Reorganized the TopFiveDestinationList.java file into smaller methods such as configureWindow(), createHeader(), loadDestinations(), and createDestinationList().
* Updated DefaultListModel and JList to make the code easier to understand.
* Added constants for window and image sizes instead of repeating throughout the code.
* Created a loadImage() method to handle missing image resources with fewer issues.
* Added a scaleIcon() method so destination images display at a consistent size.
* Improved the layout by adding better spacing, centering the window, and using the system look and feel.
* Made the text and icon fields in the TextAndIcon class final and removed unnecessary setter methods.
* Cleaned up imports, formatting, comments, and JavaDoc documentation.

These changes kept the original functionality of the application while making the code easier to understand and maintain.

### Enhancement Pseudocode

```text
START Application

Apply system look and feel
Configure application window
Create heading
Load destination information

FOR each destination
    Attempt to load image

    IF image exists
        Scale image
        Add destination and image to list
    ELSE
        Display error message
    END IF
END FOR

Create and display destination list
Center application window

END Application
```

### Skills Demonstrated

This enhancement helped me demonstrate stronger software engineering and design skills. Instead of only focusing on whether the program worked, I focused more on organization, readability, type safety, error handling, and maintainability. Breaking the program into smaller methods also made it easier to understand what each part of the application is responsible for.

### Reflection

Revisiting this project showed me how much my approach to programming has changed since taking CS 250. When I originally created the application, I was mainly focused on getting everything to work. During the enhancement, I paid more attention to how the code was organized and how easy it would be for someone else to understand or update later.

One challenge I faced was improving the code without changing how the application worked. Testing the application as I made changes helped me make sure I did not break any of the original functionality. Overall, I think the enhanced version is cleaner, easier to understand, and better represents the software development skills I have gained throughout the program.

### 3b. Algorithms and Data Structures

### Artifact and Origin

For Category Two, I selected my Course Planner application from CS 300: Analysis and Design. This C++ program reads course information from a file, stores the information, displays courses in alphabetical order, and allows the user to search for a specific course and view its prerequisites. I chose this artifact because it demonstrates my understanding of algorithms, data structures, searching, and file processing.

### Enhancement Plan

For this enhancement, I focused on making the program more organized, reliable, and easier to use while keeping its original purpose.

Improvements made include:

* Created a CoursePlanner class to keep the course data and related functions together.
* Continued using a map to store and retrieve courses by their course codes efficiently.
* Used vectors to manage prerequisite information.
* Added a parseCourse() function to better organize how course information is read from the file.
* Added validation for missing course codes and titles.
* Added checks for duplicate course codes.
* Added prerequisite validation to identify prerequisites that do not exist in the loaded course data.
* Added trim() and toUpper() functions to make user input and course searches more consistent.
* Improved error handling for invalid files, menu choices, and course searches.
* Used find() when searching the map for a course.
* Added a sample CSV file to make testing the program easier.
* Cleaned up comments, formatting, variable names, and menu messages.

These changes made the program more reliable while also showing a better understanding of how algorithms and data structures can be used to organize and retrieve information.

### Enhancement Pseudocode

```text
START Program

Create Course Planner

Ask user to load course file

FOR each line in file
    Parse course information
    Validate course code and title

    IF course is valid
        Check for duplicate course
        Store course in map
    ELSE
        Skip invalid course
    END IF
END FOR

Validate course prerequisites

Display menu

IF user selects course list
    Display courses in alphabetical order
END IF

IF user searches for course
    Clean and convert input to uppercase
    Search map

    IF course exists
        Display course and prerequisites
    ELSE
        Display course not found
    END IF
END IF

Repeat until user exits

END Program
```

### Skills Demonstrated

This enhancement demonstrates my ability to use algorithms and data structures to improve an existing program. The map provides an organized way to store and search for courses, while vectors are used to manage prerequisite lists. I also improved the way the program validates, searches, and processes its data.

The project helped me understand that choosing the right data structure is important not only for performance but also for keeping a program organized and easier to maintain.

### Reflection

Revisiting this project showed me how much my understanding of algorithms and data structures has improved since taking CS 300. When I originally completed the project, I was mainly focused on meeting the requirements and getting the correct results. During the enhancement, I focused more on how the information was organized, searched, and validated.

One challenge I faced was adding improvements without changing the main functionality of the program. Testing different files, searches, and menu options helped me make sure the program continued to work correctly. Overall, this enhancement helped me better understand how the right data structures and algorithms can make a program more efficient, organized, and reliable.

### 3c. Databases

### Artifact and Origin

For Category Three, I selected my Event Planning App from CS 360: Mobile Architecture and Programming. This Android application allows users to register, log in, and manage events using a local SQLite database. I chose this project because it gave me a good opportunity to demonstrate my database skills while also showing how a database can be connected to a complete mobile application.

### Enhancement Plan

For this enhancement, I focused on improving the database structure and making the stored event information more useful.

Some of the improvements I made include:

* Expanded the events table to store an event title, date, description, and priority.
* Updated the ItemModel class to support the new event information.
* Organized database names, table names, and column names using constants in DatabaseHelper.kt.
* Increased the database version and added support for upgrading the database structure.
* Separated the creation of the users and events tables into their own methods.
* Improved CRUD functionality so users can create, view, edit, and delete events.
* Added an edit feature so users can update information for an existing event.
* Added a confirmation before deleting an event.
* Added searching to help users find specific events.
* Added priority filtering.
* Added date sorting.
* Added a date picker and priority selection when creating or editing events.
* Updated the interface to display the event title, date, priority, and description.
* Added an empty message when there are no events to display.
* Updated MainActivity, ItemModel, ItemAdapter, and the layout files to work with the database changes.

These improvements made the application more useful while also demonstrating stronger database design and management skills.

### Enhancement Pseudocode

```text
START Application

Open SQLite database

IF user creates event
    Collect title, date, description, and priority
    Validate information
    Save event to database
END IF

Retrieve stored events

IF user searches
    Filter events based on search
END IF

IF user selects priority
    Filter events by priority
END IF

IF user sorts by date
    Sort events by date
END IF

IF user edits event
    Load existing information
    Allow user to make changes
    Update database record
END IF

IF user deletes event
    Ask for confirmation

    IF confirmed
        Delete event from database
    END IF
END IF

Display updated event list

END Application
```

### Skills Demonstrated

This enhancement demonstrates my ability to design and improve a database-driven application. I expanded the database structure, improved CRUD operations, and added searching, filtering, and sorting features that make the stored information more useful.

It also helped me better understand how database changes affect other parts of an application. Updating the database meant I also had to make changes to the models, activities, adapters, and layouts so everything continued to work together.

### Reflection

Revisiting this project showed me how much my database and programming skills have grown since taking CS 360. When I originally created the application, I was mainly focused on getting the database and basic features to work. During the enhancement, I focused more on how the data was structured, how users could interact with it, and how the database connected with the rest of the application.

One challenge I faced was changing the database structure while making sure the rest of the application continued to work correctly. Adding the new event fields meant I also had to update several other parts of the project. This helped me better understand how connected each part of an application can be.

Overall, the enhanced version is more complete and useful than the original. It gave me more experience with SQLite, database design, CRUD operations, searching, filtering, and sorting. I think the final version does a better job of showing the database and software development skills I have gained throughout the Computer Science program.

## 4. Course Outcomes Alignment

Throughout my ePortfolio, the three enhanced artifacts and my professional self-assessment work together to demonstrate the five Computer Science program course outcomes.

Course Outcome 1 – Collaborative Environments

My professional self-assessment demonstrates this outcome through my experiences working with classmates, sharing ideas, responding to feedback, and considering stakeholder requirements. These experiences helped me understand how communication and collaboration support better decisions during software development.

Course Outcome 2 – Professional Communication

My ePortfolio demonstrates this outcome through the organization and presentation of my artifacts, narratives, code review, reflections, and technical documentation. I also improved comments, JavaDoc, naming, and code organization within my projects to make the technical information easier for others to understand.

Course Outcome 3 – Algorithms and Computing Solutions

My CS 300 Course Planner enhancement strongly demonstrates this outcome. I used a map to efficiently organize and search course information, vectors to manage prerequisites, and additional validation and searching techniques to make the program more reliable. The enhancement also helped me evaluate how the choice of data structures affects organization, efficiency, and maintainability.

Course Outcome 4 – Computing Techniques, Skills, and Tools

All three enhancements demonstrate this outcome. I used Java and Java Swing to improve the Top Five Destinations application, C++ and appropriate data structures to improve the Course Planner, and Android development with SQLite to improve the Event Planning App. These enhancements demonstrate my ability to use different programming languages, tools, and development techniques to improve existing software.

Course Outcome 5 – Security Mindset

My professional self-assessment and enhancements demonstrate my growing security mindset through input validation, error handling, authentication concepts, and protecting application data. The Course Planner includes validation for invalid or missing information, while the Event Planning App uses validation and more organized database interactions. During my enhancements, I also looked for areas where unexpected input could cause errors or create potential vulnerabilities. I added checks to make sure information is validated before being processed or stored. These improvements helped reduce potential bugs, improve reliability, and better prepare the applications for future changes.

## 5. Reflection

Putting this ePortfolio together gave me the chance to look back at everything I have learned throughout the Computer Science program and see how much I have improved. Going back to my older projects showed me how much my coding style, problem-solving, and overall approach to software development have changed since I first started. It was rewarding to take projects I completed earlier in the program and make them cleaner, more efficient, and easier to maintain.

The three enhanced artifacts highlight the areas I have grown the most in: software engineering, algorithms and data structures, and databases. Together, they show the skills I have developed throughout the program and the progress I have made as a programmer. Completing this portfolio has given me more confidence in my abilities and has prepared me for the next step after graduation. I know there is still a lot to learn, but I am excited to continue building my skills and begin my career in software development and data science.
