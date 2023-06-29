# TecPlix
TecPlix is a command-line program that allows users to manage and search for movies and series. It provides various menus with different functionalities, including displaying movies and series, searching for movies and series by name or genre, and rating and commenting on movies and series.

### Skills Used in the Code
Inheritance: The code demonstrates the use of inheritance by creating a series class that inherits from the videos class. This allows the series class to inherit the properties and methods of the videos class.

File Handling: The program utilizes file handling to read and write data to CSV files. It opens and closes the series.csv and movies.csv files, reads data from them, and updates the files when ratings or comments are added.

Error Handling: The code includes error handling mechanisms to handle file opening failures. If the program fails to open the required CSV file, it displays an error message and terminates.

User Input Validation: The program validates user input to ensure that only valid options and values are accepted. It checks for input range and data type validation to prevent invalid input.

Function Overrides: The code overrides certain functions in the base class to provide specific functionality for the series and movies classes. For example, the display() function is overridden in the series class to display series-specific information.

### Program Description
The TecPlix program offers the following menus:

Main Menu: Upon starting the program, the user is presented with a main menu. The main menu allows the user to access the Display Menu, Search Menu, Rate Menu, or exit the program.

Display Menu: The Display Menu provides options to display all movies, all series, or both. Selecting an option from this menu will display a table with information about the movies and series, including their ID, name, genre, duration, rating, and comments.

Search Menu: The Search Menu allows the user to search for movies or series by name or genre. The user can enter a search term, and the program will display the matching movies or series. If no matches are found, an appropriate message is displayed.

Rate Menu: The Rate Menu enables the user to rate and comment on movies or series. The user can choose to either add a comment or rate a movie or series using a star rating system.

The program ensures proper navigation between menus and provides the option to go back to the main menu or exit the program at appropriate points.

The code is organized using classes, functions, and control structures to provide a structured and modular approach to the program's functionalities.
