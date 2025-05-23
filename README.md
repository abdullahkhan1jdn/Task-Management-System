Task Management System
A simple Java-based Task Management System that allows users to create, edit, delete, and manage tasks through a console interface.

Features
Task Management:

Add new tasks with title, description, and due date

Edit existing tasks

Delete tasks

Mark tasks as complete/incomplete

Task Viewing:

View all tasks

Filter tasks by completion status (completed/incomplete)

Filter tasks by due date

How to Run
Ensure you have Java JDK installed on your system (version 8 or higher recommended)

Clone this repository or download the TaskManagementSystem.java file

Compile the Java file:

javac TaskManagementSystem.java
Run the compiled program:

java TaskManagementSystem
Usage
When you run the program, you'll see a menu with the following options:

Add Task: Create a new task by entering title, description, and due date (YYYY-MM-DD format)

Edit Task: Modify an existing task by entering its ID and providing new details

Delete Task: Remove a task by entering its ID

Mark Task as Complete: Change a task's status to completed by entering its ID

Mark Task as Incomplete: Change a task's status to incomplete by entering its ID

View All Tasks: Display all tasks in the system

Filter Tasks by Status: View only completed or incomplete tasks

Filter Tasks by Due Date: View tasks due on a specific date

Exit: Quit the program

Code Structure
The program follows a layered architecture:

Entity Layer: Task class representing the task data model

Service Layer: TaskService class handling business logic and data operations

UI Layer: ConsoleUI class providing the user interface

Main Class: TaskManagementSystem with the entry point

Limitations
Data is not persisted between sessions (all tasks are lost when program exits)

Basic error handling (program may crash with invalid input)

Simple console interface

Future Enhancements
Add data persistence (file or database storage)

Implement more robust error handling

Add task priority levels

Add task categories or tags

Develop a graphical user interface
