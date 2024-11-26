# Tour-Package-Management
A Tour Package Management Project in Object-Oriented Programming in Java (OOPJ) is designed to simulate the operations of a travel agency. The project incorporates core OOP concepts like classes, objects, inheritance, polymorphism, encapsulation, and abstraction to manage tour packages effectively.
A Tour Package Management Project in Object-Oriented Programming in Java (OOPJ) is designed to simulate the operations of a travel agency. The project incorporates core OOP concepts like classes, objects, inheritance, polymorphism, encapsulation, and abstraction to manage tour packages effectively. Below is a basic description of the project:

Objective
To develop a console-based Java application to manage tour packages, including adding, updating, viewing, and deleting packages, while providing users with the ability to search for suitable travel options.

Key Features
Package Management:

Add new tour packages (destination, duration, price, details, etc.).
Update details of an existing tour package.
Delete a tour package.
View all available packages.
Customer Management:

Add customer details (name, contact, preferences, etc.).
Book a tour package for a customer.
View all customers and their booked packages.
Search Functionality:

Search tour packages by destination, price range, or duration.
Reports:

Generate a summary of all booked packages.
Display top destinations based on bookings.
Class Design
TourPackage:

Attributes: packageId, destination, duration, price, details.
Methods: addPackage(), updatePackage(), deletePackage(), viewPackage().
Customer:

Attributes: customerId, name, contact, email, bookedPackage.
Methods: addCustomer(), viewCustomerDetails().
Booking:

Attributes: bookingId, customer, tourPackage, bookingDate.
Methods: createBooking(), viewBookingDetails().
Main (Driver Class):

Menu-driven interface to interact with the system.
