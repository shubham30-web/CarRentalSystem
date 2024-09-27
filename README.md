# CarRentalSystem
Overview
The Car Rental System is a simple Java application that simulates a basic car rental service. Users can rent and return cars, and the system stores their rental information in a file for persistence. This project includes basic file handling to save rental details, ensuring that data persists even after the application is closed.

Features

Add Cars: The system allows cars to be added with unique IDs, brands, models, and rental prices per day.
Rent a Car: Customers can rent available cars for a specific number of days.
Return a Car: Customers can return rented cars, and the system updates the car’s availability status.
File Handling: Rental information is saved to a file when cars are rented and returned, ensuring data is available after program execution.
Menu-Driven Interface: The system offers a simple menu for users to choose between renting, returning cars, and exiting the program.

How It Works

Car Rental: The user selects a car to rent by entering the car ID and rental duration. If the car is available, the system calculates the total cost and stores the rental information.
Return a Car: The user enters the car ID of the rented vehicle, and the system marks the car as returned. The return details are then stored in a file.
File Persistence: All rental and return information is written to files (rental_records.txt), allowing users to review past transactions.

Project Structure

Car Class: Manages the car’s details (ID, brand, model, base price) and its availability status.
Customer Class: Stores customer information, including their name and a unique customer ID.
Rental Class: Handles the rental transaction, including which car was rented, by whom, and for how many days.
CarRentalSystem Class: Acts as the main system controller, managing car rentals, returns, and interaction with users via the console menu.

Example
Renting a Car:

The system displays available cars.
After selecting a car and confirming rental details, the system stores this information and marks the car as rented.
Returning a Car:

The user enters the car ID of the rented car, and the system processes the return.
Return details are saved to the file, and the car is available for rent again.

Future Improvements

Implement a search feature for customers and cars.
Add functionality to edit car and customer details.
Implement more complex pricing models (e.g., discounts for longer rentals).
