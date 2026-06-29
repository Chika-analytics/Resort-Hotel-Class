# Resort Hotel Room Management System

A beginner-friendly object-oriented programming (OOP) project built with Python that simulates a simple hotel room management system. The program models hotel rooms as objects, allowing rooms to be booked, checked out, and their current status displayed.

This project was created to strengthen my understanding of classes, objects, constructors, instance attributes, and methods while demonstrating how object-oriented programming can be used to model real-world scenarios.

# Project Overview

Hotels manage numerous rooms, each with its own booking status and guest information. Instead of storing this information using multiple variables, object-oriented programming provides a cleaner and more scalable solution.

In this project, each hotel room is represented as an object of the "ResortRoom" class. Every room maintains its own room number, booking status, and guest information while exposing methods to perform common hotel operations such as booking and checkout.

# Features

- Create hotel room objects with unique room numbers
- Book available rooms
- Prevent double-booking of occupied rooms
- Check guests out of booked rooms
- Display the current status of each room
- Store room-specific information using instance attributes

# Technologies Used

- Python 3
- Jupyter Notebook

# Python Concepts Practiced

This mini project helped reinforce the following Python concepts:

- Object-Oriented Programming (OOP)
- Classes and Objects
- Constructors ("__init__")
- Instance Attributes
- Instance Methods
- Conditional Statements
- Boolean Logic
- String Formatting (f-strings)

# Project Structure

Resort_Hotel_Class.ipynb
│
├── ResortRoom class
│   ├── __init__()
│   ├── book_room()
│   ├── checkout()
│   └── display_info()
│
└── Example usage
    ├── Create room objects
    ├── Book rooms
    ├── Check guests out
    └── Display room information

# Example Workflow

room1 = ResortRoom(101)
room1.book_room("Alice")

room2 = ResortRoom(102)
room2.book_room("David")

room1.checkout()

room1.display_info()
room2.display_info()

Example Output

Room 101 booked for Alice
Room 102 booked for David

Alice has checked out from Room 101.

Room Number: 101
Guest: None
Status: Available

Room Number: 102
Guest: David
Status: Booked

# What I Learned

Building this project improved my understanding of how object-oriented programming can model real-world systems. Instead of writing repetitive code, I learned how to encapsulate both data and behavior inside a class, making programs more organized, reusable, scalable and easier to maintain.

I also gained hands-on experience with:

- Designing classes to represent real-world entities
- Managing object state using instance attributes
- Creating methods that modify object behavior
- Applying conditional logic to enforce business rules (such as preventing double-booking)

# Possible Future Improvements

Potential enhancements for this project include:

- Manage multiple rooms using a list or dictionary
- Add guest check-in and check-out dates
- Calculate accommodation costs
- Search for available rooms
- Save booking records to a file or database
- Create a menu-driven interface for continuous user interaction
- Add exception handling and input validation

# Project Purpose

This project is part of my Python learning journey, where I build practical mini projects to strengthen my understanding of programming fundamentals before progressing to more advanced software engineering and data science applications.

Each project focuses on applying core programming concepts to solve real-world problems while writing clean, readable, and maintainable code.
