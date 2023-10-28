# ticket-reservation-data-file-handling
Tour Bus Management System
Tour Bus Management System is a C++ program that allows users to manage tour buses, book tickets, and display booked tickets. It provides a simple command-line interface for performing various operations related to tour buses and ticket bookings.

Features:
>>Add a New Tour Bus: Add new tour buses with details such as bus ID, destination, time, maximum seats, and fare.
>>Show Selected Bus: Display details of a specific bus using its ID.
>>Display All Buses: View details of all available tour buses.
>>Delete a Bus: Remove a bus from the system using its ID.
>>Book a Ticket: Book a ticket for a specific destination and customer name. The system automatically updates the booked seats for the corresponding bus.
>>Display Booked Tickets: View the details of all booked tickets.
>>
How to Use:
Compile: Compile the program using a C++ compiler (e.g., g++).

Copy code:
g++ tour_bus_management.cpp -o tour_bus_management
Run: Execute the compiled program.

bash
Copy code
./tour_bus_management
Menu:

Select options from the menu to perform various operations.
Data Files
tour.dat: Stores information about tour buses.
tickets.dat: Stores information about booked tickets.
Important Notes
Make sure to provide valid inputs as per the prompts to avoid errors.
The program uses binary files (tour.dat and tickets.dat) to store data. Ensure these files have appropriate read and write permissions.
Example Usage
Adding a New Tour Bus:

Select option 1 from the menu.
Enter bus details as prompted.
Booking a Ticket:

Select option 5 from the menu.
Enter the destination and customer name as prompted.
The system will display available buses matching the destination.
Select a bus and book a ticket.
Viewing Booked Tickets:

Select option 6 from the menu to view booked tickets.
Exiting the Program:

Select option 7 from the menu to exit the program.
Authors
[Your Name]
[Your Email]


