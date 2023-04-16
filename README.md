# Hotel-Management-System

It is a hotel management tool that can be used for managing activities like storing customer details, booking four different types of rooms, ordering food for a particular room, booking rooms, and showing bills. It can also be used to view various room features and room availability. It is a menu-driven program and it runs till the user exits. File handling has been used to store the current status of the hotel (customer details, rooms booked, food orders) in a file after the program exits so that when we restart the program, the old details are not lost. Go. The program reads the file when it restarts to know the previous state of the hotel. The writing of the file is done in a separate thread because it can be done parallely. A user defined exception is thrown if the user tries to book an already allocated room. Exception handling is done properly to deal with any kind of unexpected exception.

Topics Covered-
Classes and Objects, File Handling with Objects,  Inheritance, ArrayList, implementing Interface, User defined exception and Exception handling.
