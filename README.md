# KLH-FED-2026-BusReservationSimulator
1. Project Title
  Intercity Bus Reservation Simulator
A Java based console application to view intercity buses, reserve seats and calculate fares.

2. Team Members
   Tony Sainipun  <Roll No>
   Viloch         <Roll No>
   S. Satvik      <Roll No>

3. Supervisor
   Mrs. Mamatha

4. Abstract

The Intercity Bus Reservation Simulator is a Java-based console application designed to provide a simple and organized way to view available buses and reserve tickets for intercity journeys. The system maintains important bus details such as bus name, route, number of available seats and ticket price. It allows the user to select a bus, enter the number of tickets, check seat availability and get the final fare automatically, making the booking process faster and reducing errors that may occur during manual calculation.

The application uses various Java programming concepts, including variables, data types, operators, conditional statements, switch-case, loops, arrays and methods to process and manage reservation information. Based on the number of tickets entered, the system calculates the total amount, applies a 10% discount when 5 or more tickets are booked, and displays the final amount. After a successful reservation, the remaining seats for the selected bus are updated automatically.

The main purpose of this project is to make bus ticket reservation simple, accurate and easy to manage through a clear, menu-driven experience. It provides a structured way to view bus information and complete a booking in one system. The project also demonstrates how fundamental Java programming concepts can be applied to solve a practical real-world problem in the travel and transport domain.

5. Objectives

- To store bus details such as names, routes, seats and prices in an organized manner.
- To display all available buses and their route information.
- To allow the user to select a bus and reserve tickets.
- To check seat availability before confirming a reservation.
- To calculate the ticket fare and apply discounts automatically.
- To update the remaining seats after a successful reservation.
- To reduce errors caused by manual fare calculation.
- To apply Java programming concepts to a real-world problem.

6. Features

- Menu-driven console interface (View Buses, Reserve Tickets, Exit)
- Display of all available buses with routes, seats and prices
- Ticket reservation for a selected bus
- Input validation for menu choice and ticket quantity
- Seat availability check before booking
- Automatic fare calculation (tickets x price)
- 10% discount for bookings of 5 or more tickets
- Automatic update of remaining seats after booking
- Display of reservation confirmation details

7. Java Concepts Used

- Variables and data types (int, double, String)
- Arithmetic, assignment and relational operators
- if-else statements for validating ticket quantity and seat availability
- switch-case with break and default for menu selection
- for loop to display all buses
- do-while loop to repeat the menu until the user chooses Exit
- Arrays (busNames, routes, seats, prices) to store data for multiple buses
- Methods (displayBuses(), reserveTicket()) to keep the code organized
- Scanner class for user input

8. Technologies Used

- Java
- Visual Studio Code
- Git
- GitHub

9. Working Principle

1. Store bus data – Bus names, routes, seats and prices are stored in arrays.
2. Display menu – The user chooses an operation from the menu.
3. Show buses – All buses and their details are listed using a loop.
4. User input – The user enters the bus number and number of tickets.
5. Validate booking – The program checks the input and seat availability.
6. Calculate fare – Total = tickets x price; 10% discount for 5 or more tickets.
7. Update seats – Booked seats are subtracted from the available seats.
8. Confirm – Reservation details and the final amount are displayed.
These steps run every time a passenger books, and the menu repeats until the user chooses Exit.

10. Setup Instructions
Install the Java Development Kit (JDK).
Install Visual Studio Code.
Install the required Java extensions in Visual Studio Code.
Clone this repository from GitHub.
Open the project folder in Visual Studio Code.
Navigate to the src folder.
Open the main Java file.
Compile and run the program.

11. Execution Instructions
Open the project in Visual Studio Code.
Navigate to the src folder.
Open the main Java program.
Run the program.
Choose option 1 to view the available buses.
Choose option 2 to reserve tickets.
Enter the bus number and the number of tickets.
The program validates the input and checks seat availability.
The total amount, discount and final fare are displayed as the output.
Choose option 3 to exit the program.

12. Data

The data folder contains sample data used for testing and demonstrating the Intercity Bus Reservation Simulator.

Sample data may include bus names, routes, number of available seats and ticket prices.

No sensitive or personal passenger information is used in the sample data.

13. Results

The results folder contains the outputs generated by the Intercity Bus Reservation Simulator.

This includes sample program outputs and screenshots demonstrating the bus list display, ticket reservation, fare and discount calculation, seat update and invalid input handling.

14. Documentation

The docs folder contains project-related documentation, including requirements, flowcharts, diagrams, algorithms and other design materials.

15. Reports

The reports folder contains project review documents, the project presentation and the final project report.

16. Current Phase Status

The project is currently in the development phase.

The initial project structure, documentation and core Java logic for viewing buses, reserving tickets and calculating fares have been created. Testing, documentation and further improvements will be developed progressively throughout the project phases.

17. Version Control and Collaboration

Git and GitHub are used for version control and team collaboration.

Each team member contributes using their own GitHub account so that individual contributions can be verified through the Git commit history.

Team contributions:
- Tony Sainipun – Information Gathering
- Viloch – Presentation (PPT)
- S. Satvik – Code

The project repository will be maintained throughout the project duration and will remain accessible until the final project evaluation.

18. Future Enhancements
Build an interactive web interface using HTML, CSS and JavaScript.
Add seat-wise selection with a visual seat layout.
Add passenger details and ticket cancellation.
Store bus and booking data in files or a database.
Add more detailed input validation.
Generate printable tickets and booking history.
Perform further testing and improvements.

19. Project Status

Status: Development in Progress
