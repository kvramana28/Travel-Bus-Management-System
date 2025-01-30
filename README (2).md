# Travel-Bus-Management-System

# Introduction

The Travel Bus Management System is a C-based program that helps manage and track bus operations. It allows the admin to view bus statuses and manage bus bookings for passengers. The system provides functionalities such as:

Admin can view buses' running status, buses under repair, and buses in other depots.

Passengers can book seats on buses running on specific routes.

The system tracks seat bookings for buses and handles both running and non-running buses.

# Table of Contents:

# 1.Features

# 2.DSA Topics Used

# 3.Data Structures Involved

# 4.Algorithms Used

# 5.Conclusion

# Features:

# Admin Section:

Admin login with username and password.

View total buses running, not running, under repair, and in other depots.

View the total number of buses in the depot.

# Passenger Section:

View buses running on a specific route with details such as bus number, start time, reach time, and available seats.

Book seats on a bus, updating the availability.

# Bus Management:

Manage buses with unique bus numbers, routes, statuses (running, not running, under repair, or in another depot), and seat availability.

# DSA Topics Used:

# 1.Linked Lists:

A singly linked list is used to store and manage buses dynamically.

Operations such as adding new buses, counting buses based on status, and viewing buses on a route are implemented using linked lists.

# 2.Arrays:

Used for static data such as routes or bus numbers. However, the core data is managed through the linked list structure.

# 3.Strings:

String manipulation is used for bus routes, start and reach times, and user input.

Functions like strcmp are used to compare strings and check routes and user credentials.

# 4.Searching Algorithms:

Linear search is used to find buses based on bus numbers or routes. This is a simple search algorithm suitable for this linked list-based structure.

# 5.Time Complexity Analysis:

Basic operations such as adding a bus and searching through the linked list have O(n) time complexity where n is the number of buses in the list.

# Data Structures Involved:

# 1.Singly Linked List:

Each bus is represented as a node in the linked list with attributes such as bus number, route, status, available seats, etc. This allows dynamic memory allocation as new buses are added or removed.

# 2.Strings:

Strings are used to store textual data such as bus routes, start and reach times, and user input for routes and credentials.

# Algorithms Used:

# 1.Linear Search:

This algorithm is used to search for a bus by its bus number or route. It operates in O(n) time where n is the number of buses in the system.

# 2.Insertion Algorithm for Linked List:

The addBus function uses this algorithm to add a new bus to the end of the linked list. The time complexity for insertion is O(n) as it requires traversing the list.

# 3.String Comparison:

String comparison using functions like strcmp is used to check if a bus is running on a specific route or to authenticate the admin.

# 4.Seat Booking Logic:

The system ensures that seat bookings are handled efficiently, updating the available seats and booked seats dynamically.

# Conclusion:

The Travel Bus Management System provides an efficient way to manage bus operations, seat bookings, and route tracking. By utilizing linked lists to store and manage buses, the program offers flexibility and dynamic memory allocation for a scalable solution. The integration of basic searching algorithms and string manipulation allows for a user-friendly experience. With this system, both admins and passengers can easily track buses, manage bookings, and handle operations effectively. This project demonstrates key Data Structures and Algorithms (DSA) concepts, providing a practical implementation of real-world bus management needs.


