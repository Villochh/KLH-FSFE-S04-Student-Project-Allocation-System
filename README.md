# KLH-FED-2026-StudentProjectAllocationSystem
1. Project Title
  Student Project Allocation System
A web application for listing project topics, collecting student preferences, allocating guides and displaying project assignments.

2. Team Members:

   Ashwanth    2620030405
   
   Viloch      2620030127
   
   Eshanth     2620030131

4. Supervisor:
   Mrs. Surekha

5. Abstract

The Student Project Allocation System is a web application that simplifies the allocation of academic projects in a department. When allocation is done by hand, it often leads to confusion, duplicate allocations and delays. In this system, faculty list project topics with guide details and available slots, and students submit their preferences in order of priority. The system then allocates a project and guide to each student based on their preferences and availability, without exceeding any slot limit.

The application is built using HTML for the page structure, CSS for styling and layout, and Java for handling the allocation logic and data. It has dedicated interfaces for faculty and students to view topics and allocation details. The main purpose of this project is to make project allocation faster, fairer and more transparent.

5. Objectives

- To maintain a list of project topics with guide details in an organized manner.
- To allow students to view available topics and submit their preferences online.
- To allocate projects and guides to students based on their preferences.
- To make sure no topic or guide is allocated beyond the available slots.
- To display project assignments clearly to students and faculty.
- To provide separate web interfaces for faculty and students.
- To reduce errors, duplicate allocations and delays caused by manual allocation.
- To apply HTML, CSS and Java to a real-world academic problem.

6. Features

- Separate login pages for Faculty and Students
- Faculty can add, update and remove project topics
- Each topic includes the topic title, description, guide name and available slots
- Students can view all available project topics in a table
- Students can submit project preferences in order of priority using a form
- Automatic allocation of projects and guides based on preferences and availability
- Prevention of duplicate allocation and over-allocation of slots
- Display of the final project assignment for each student
- Faculty can view the list of students allocated to them
- Simple and responsive user interface

7. Modules

Faculty Module:
- Log in through the faculty login page.
- Add, update or remove project topics using forms.
- Set the number of available slots for each topic.
- View student preferences.
- View the list of students allocated under them.

Student Module:
- Log in through the student login page.
- View the list of available project topics and guides.
- Submit project preferences in order of priority.
- View the allocated project and guide.

Allocation Module:
- Reads the student preferences one by one.
- Checks whether the preferred topic still has available slots.
- Allocates the first available preferred topic and its guide to the student.
- Moves to the next preference if a topic is already full.
- Updates the remaining slots after each allocation.

Display Module:
- Displays all project topics with guide details and remaining slots.
- Displays the final project assignments for all students.
- Displays allocation details for a particular student or guide.

8. Concepts Used

HTML:
- Page structure using headings, tables, lists and forms
- Login forms for faculty and students
- Forms for adding topics and submitting preferences
- Tables for displaying topics and allocation results
- Dropdowns for selecting project preferences

CSS:
- Styling of pages, forms, tables and buttons
- Separate colour themes for the faculty and student pages
- Flexbox / Grid layout
- Responsive design for different screen sizes

Java:
- Classes and objects (Student, Faculty, ProjectTopic, Allocation)
- Encapsulation using private fields with getters and setters
- Constructors
- Collections (ArrayList, HashMap) to store topics, preferences and allocations
- Conditional statements and loops for the allocation logic
- Methods for adding topics, submitting preferences and allocating projects
- Exception handling for invalid inputs
- File handling to save and load data

9. Technologies Used

- HTML
- CSS
- Java
- Visual Studio Code
- Git
- GitHub

10. Working Principle

1. Faculty log in and add project topics with guide names and available slots.
2. Students log in and view the list of available project topics.
3. Students submit their project preferences in order of priority using a form.
4. The system checks each student's preferences one by one.
5. If a preferred topic has an available slot, it is allocated to the student along with its guide.
6. If the topic is full, the system checks the student's next preference.
7. The remaining slots are updated after every allocation.
8. The final project assignments are displayed on the student and faculty pages.

11. Setup Instructions
Install the Java Development Kit (JDK).
Install Visual Studio Code.
Install the required Java and web development extensions in Visual Studio Code.
Clone this repository from GitHub.
Open the project folder in Visual Studio Code.
Compile and run the Java program.
Open the main HTML page in a web browser.

12. Execution Instructions
Open the project in Visual Studio Code.
Run the Java program.
Open the application in a web browser.
Choose Faculty Login or Student Login on the home page.
Faculty: add project topics, set slots and view allocated students.
Student: view topics and submit project preferences.
Run the allocation process.
The allocated project and guide are displayed for each student.
Log out to close the session.

13. Data

Sample data is used for testing and demonstrating the Student Project Allocation System.

Sample data may include student IDs, student names, faculty names, project topics, available slots and student preferences.

No sensitive or personal student information is used in the sample data.

14. Results

The application lists project topics, collects student preferences and allocates projects and guides correctly without exceeding available slots. Sample outputs and screenshots show the login pages, the faculty dashboard, the student dashboard, the preference form and the final project assignments.

15. Documentation

Project documentation includes requirements, module descriptions, page layouts, flowcharts, diagrams, algorithms and other design materials.

16. Reports

Project reports include project review documents, the project presentation and the final project report.

17. Current Phase Status

The project is currently in the development phase.

The project requirements, page design and documentation have been prepared. The implementation, testing and further improvements will be developed progressively throughout the project phases.

18. Version Control and Collaboration

Git and GitHub are used for version control and team collaboration.

Each team member contributes using their own GitHub account so that individual contributions can be verified through the Git commit history.

The project repository will be maintained throughout the project duration and will remain accessible until the final project evaluation.

19. Future Enhancements
Store data in a database such as MySQL.
Add allocation based on student CGPA or merit.
Send email or SMS notifications when projects are allocated.
Add an admin module to manage faculty and students.
Allow students to form teams and apply for projects as a group.
Generate downloadable allocation reports.
Perform further testing and improvements.

20. Project Status

Status: Development in Progress
