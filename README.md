# Phonebook

This is a simple Phonebook application built using Java and Swing. It allows users to add, view, search, delete, and update contacts. The application uses a graphical user interface (GUI) for managing a list of contacts and provides basic phonebook functionalities.

##Features
1. Add Contacts: Users can add new contacts by providing a name and phone number.
2. View Contacts: Displays all saved contacts, sorted alphabetically.
3. Search Contacts: Allows users to search for contacts by name.
4. Delete Contacts: Users can remove contacts from the phonebook.
5. Update Contacts: Allows editing of existing contact information.
6. Search Efficiency Analysis: Measures the time taken for searching contacts.

###Installation
Follow these instructions to run the Phonebook application on your local machine.

Prerequisites:
Java Development Kit (JDK) version 8 or higher

1. Clone the repository: git clone https://github.com/VivianK-t/Phonebook.git
2. Navigate to the project directory: cd Phonebook
3. Compile and run the program :
   javac Phonebook.java
   java Phonebook

####Usage
1. Add a Contact: Enter the name and phone number in the respective text fields and click "Add Contact".
2. View Contacts: Click the "View Contacts" button to display all saved contacts.
3. Search Contacts: Enter a name in the search field and click "Search" to find a specific contact.
4. Delete a Contact: Select a contact from the list and click "Delete Contact" to remove it.
5. Update a Contact: Select a contact, then click "Update Contact" to edit the name and/or phone number.

#####Code Overview
The project follows a modular structure:

Pseudocode: 

The pseudocode outlines the core functionality of the phonebook, including adding, viewing, searching, deleting, and updating contacts. It uses a list to store contact objects, where each contact has a name and phone number.
The pseudocode covers functions like addContact, viewContacts, searchContact, deleteContact, updateContact, and AnalyzeSearchEfficiency, which can be mapped to the corresponding functionalities in the Java code.

Java Code:

The main class Phonebook implements the phonebook functionalities using the Java Swing library for the graphical user interface (GUI).
The GUI is divided into three main panels: input (for user input), output (to display contacts), and buttons (for actions like adding, searching, deleting, and updating).
The application uses an event-driven approach to handle user interactions, such as clicking buttons to perform various operations.

######Future Enhancements
1. Sort Contacts: Add a feature to sort contacts by name or phone number.
2. Export/Import Contacts: Implement functionality to save contacts to a file and load them from a file.
3. More Search Options: Enhance search functionality to support partial matches and search by phone number.

#######License:
This project is open-source and available under the MIT License.

########Acknowledgments:
Java Swing documentation for providing guidance on building graphical user interfaces.



