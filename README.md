# LockedMe
LockedMe.Com - Virtual Key for Repositories

Simple Java Console based program to allows user to input menu options for 

* Displaying File in a Directory. 
* Search for File in a Directory.
* Add a File in a Directory.
* Delete a File From a Directory.

## View project locally

To try out the project in your local machine:

* clone this repository using `git clone `
* Open the folder from Eclipse/IntelliJ 
* Open mainScreen.java (chanage the path of the directory to be seacrched in FileOperations.java) and Run.


## Component Hierarchy

| File    |  Description           |
|-----------------|-------------------         |
| `mainScreen.java` | This component contains the Main method. It Displays the menu options, take user input and call the method from FileOperations accordingly. It's the entry point of the program. |
| `FileOperations.java` | This component defines all the operations required for displaying, searching, deleting and adding files and contains  methods for handling different options from user input  |



To track below deliverables - 

    Specification document - Product's capabilities, appearance, and user interactions

    Java concepts being used in the project 

    Data Structures where sorting and searching techniques are used. 

    Generic features and operations available: 

      1)  Retrieving the file names in an ascending order

      2)  Business-level operations:

            Option to add a user specified file to the application

            Option to delete a user specified file from the application

            Option to search a user specified file from the application

            Navigation option to close the current execution context and return to the main context

      3)  Option to close the application


Code designed to display the welcome screen. It displays:

* Application name and the developer details 

* The details of the user interface such as options displaying the user interaction information 

* Features to accept the user input to select one of the options listed 

* The first option returns the current file names in ascending order. The root directory can be either empty or contain few files or folders in it.

* The second option returns the details of the user interface such as options displaying the following:

    * Add a file to the existing directory list

    * Delete a user specified file from the existing directory list

    * Search a user specified file from the main directory

    * Option to navigate back to the main context

* There is a third option to close the application.

Implemented the concepts such as exceptions, collections, and sorting techniques for source code optimization and increased performance 
