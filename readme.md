This project is an implementation of a Food Warehouse Management System as part of the Systems Programming – Assignment #1 for Fall 2024. The system simulates the operation of a warehouse that processes and delivers food orders using volunteers. The program follows object-oriented design principles in C++, incorporating memory management techniques and efficient data structures.

Program Features
Order Management: Customers place orders, which are processed by volunteers.
Volunteers: Two types: Collectors & Drivers, with special variations (Limited Collectors & Limited Drivers).
Simulation: Step-by-step execution of warehouse operations.
Command-line Actions: Supports various commands like order, customer, volunteerStatus, simulateStep, log, and close.
Logging: Maintains an action history.

Memory Management
Ensure proper handling of dynamic memory allocation and avoid memory leaks by:
Using smart pointers where applicable.
Implementing correct destructors in classes.
Following RAII (Resource Acquisition Is Initialization) principles.
