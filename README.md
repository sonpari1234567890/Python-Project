# Python-Project
Library Management System
A simple Library Management System built using Python and Tkinter for the GUI and SQLite for database management. This system allows library administrators to add, update, delete, and view records of library members and the books they borrow.
Features:
•	Add Data: Allows administrators to add new members and book borrowings.
•	Show Data: Displays all library records in a table view.
•	Update Data: Enables updates to existing records.
•	Delete Data: Deletes selected records from the system.
•	Reset Form: Clears all input fields for the next entry.
•	Exit: Closes the application.
Technologies Used:
•	Python: Main programming language
•	Tkinter: GUI library for the user interface
•	SQLite: Database for storing the library records
Screenshots:
Add some screenshots here showing the interface and functionality of your application.
Installation:
1.	Clone the repository to your local machine:
2.	git clone your project linked
3.	Navigate to the project directory:
4.	cd library-management-system
5.	Install required dependencies: This project uses Python's built-in libraries, so no external packages are required for this setup.
Running the Project:
•	To run the Library Management System, execute the following command: 
•	python library_management_system.py
Usage:
•	The application opens a window where you can enter details for library members and books.
•	You can perform the following actions: 
o	Add Data: Fill in the form and click "Add Data" to save the record to the database.
o	Show Data: View all saved records in the table below the form.
o	Update Data: Select a record from the table, edit the details, and click "Update" to save the changes.
o	Delete Data: Select a record from the table and click "Delete" to remove it.
o	Reset: Clears the form fields.
o	Exit: Close the application.
Database:
The system uses a local SQLite database (library.db) to store information about the members and their borrowed books. The database table contains the following columns:
•	id: A unique identifier for each record
•	membertype: Type of the library member
•	prnno: PRN number of the member
•	firstname: First name of the member
•	lastname: Last name of the member
•	address1: First address line
•	address2: Second address line
•	postid: Postal code
•	mobile: Member’s mobile number
•	bookid: ID of the borrowed book
•	booktitle: Title of the book
•	author: Author of the book
•	dateborrowed: Date when the book was borrowed
•	datedue: Date when the book is due
•	days: Number of days the book has been borrowed
•	latereturnfine: Fine for late return
•	dateoverdue: Date the book was overdue
•	finalprice: Final price considering the late return fine
License:
This project is open-source and available under the MIT License. See the LICENSE file for more details.

Contributing:
Feel free to fork this project and submit pull requests. Issues and suggestions are also welcome.

