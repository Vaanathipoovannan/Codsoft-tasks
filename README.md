**TASK1**

# codsoft-guessinggame

**Guessing Game**

Its an interesting guessing game with attempts.
This Java program implements a simple guessing game where the user has to guess a random number between 1 and 100. 
The game allows up to 5 attempts, providing feedback on whether the guess is too high or too low. 
After each game, the user has the option to play again.

**How to Run**

Make sure you have Java installed on your machine.
Download the Guessinggame.java file.
Open a terminal or command prompt and navigate to the directory containing the Guessinggame.java file.

**Compile the program using the command:**

      javac Guessinggame.java
      java Guessinggame
      
**Gameplay**

The program will prompt you to guess a number between 1 and 100.
You have up to 5 attempts to guess the correct number.
After each guess, the program will provide feedback if the guess is too high or too low.
If you correctly guess the number, you will be congratulated.
If you run out of attempts, the correct number will be revealed.
You will be asked if you want to play again.

**Classes**

**randomnumber:**

A class responsible for generating a random number within the specified range.

**Guessinggame:** 

The main class that implements the guessing game.
It uses the randomnumber class to generate random numbers and interacts with the user through the console.

**Enjoy the Game!**


**TASK2**
# codsoft-word-counter

Its an exciting and time saving program for easy analysis of a string or file.

**JavaFX Input Example**

This JavaFX application provides a simple user interface for inputting either a string or selecting a file. It then counts and displays the total number of words, the number of unique words, and the list of unique words.

**Features**

**User Input Options:**

Enter a string directly.
Choose a file using the file dialog.

**Count and Display Words:**

For string input, the program splits the string into words, counts the total number of words, identifies unique words, and displays the results.
For file input, it reads the file content, counts the total number of words, identifies unique words, and displays the results.

**How to Run**

Clone the repository or download the source code.

Compile and run the App class, which contains the main method.

Follow the on-screen instructions to choose between string or file input.

If choosing string input, enter the desired string when prompted.

If choosing file input, a file dialog will appear. Select a text file.

The program will display the results based on your input.

**Dependencies**

JavaFX is used for creating the graphical user interface.

**TASK 3**

# Student Management System

The Student Management System is a simple console-based Java program that allows users to manage a list of students. It provides functionalities such as adding a new student, removing a student, searching for a student, and displaying all students.

**Getting Started**

**Prerequisites**

Java Development Kit (JDK) installed on your system.
A Java IDE (Integrated Development Environment) or a text editor for compiling and running Java programs.

**Running the Program**

Clone or download the project to your local machine.
Open the project in your preferred Java IDE or text editor.
Compile and run the StudentManagementSystemApp.java file to start the application.
Follow the on-screen menu to interact with the Student Management System.

**Features**

Add a new student: Enter details such as name, roll number, grade, and comment to add a new student to the system.

Remove a student: Remove a student by providing their roll number.

Search for a student: Search for a student by entering their roll number.

Display all students: View a list of all students currently in the system.

**File Persistence**

The program uses file-based persistence to store student data. The student information is saved to a file (students.dat) when the program exits and loaded from the file when the program starts.

**File Structure**

Student.java: Defines the Student class.
StudentManagementSystem.java: Defines the StudentManagementSystem class with functionalities to manage students.
StudentManagementSystemApp.java: Contains the main method and menu for interacting with the system.

**Contributing**

Feel free to contribute to the project by creating issues or pull requests. Any feedback or suggestions are also welcome.










