Car-rental website is a car rental platform, supplier-oriented, with a backend for managing car fleets and bookings, as well as a frontend for renting cars.                  
 Car-rental is designed to work with multiple suppliers. Each supplier can manage his car fleet and bookings from the backend. BookCars can also work with only one supplier and can be used as a car rental aggregator.
 From the backend, admins can create and manage suppliers, cars, locations, customers and bookings.
 When new suppliers are created, they receive an email prompting them to create an account in order to access the backend and manage their car fleet and bookings.
![image](https://github.com/user-attachments/assets/865b1edf-6ced-4709-8103-3fd63ea45b7c)
# Table of Content
* Requirements
* Installation
* Database
* Table
* Car listing Page
* Demo
# Requirements
* XAMPP is required to run the project.
* The project will be hosted on a localhost server.
# Installation
* Install XAMPP.
* Open XAMPP and click on the Start button of Apache and MySQL.
* Clone the project to the root of the XAMPP server.
* Open the project in XAMPP.
* Import SQL file from database folder to the XAMPP server.
* Open Browser and navigate to localhost:8080.
* Hurray! The project is now running.
# Database
* The database is stored in a folder called carrental.
* The database is named as carrental.sql.
* The database is stored in the root of the XAMPP server.
* The database is imported to the XAMPP server.
* Database used is MySQL.
# Table
* The table is named as carrental.
* The table has the following columns:
* id: INTEGER PRIMARY KEY AUTO_INCREMENT
* user_email: VARCHAR(100)
* vechile_id: int(11)
* FromDate: varchar(20)
* ToDate: varchar(20)
* message: varchar(255)
* Status: int(11)
# Car listing Page
* The car listing page will have a search bar and a car listing table.
* The search bar will have a search button.
* The search button will search for the car based on the search bar input.
* The car shown only on the car listing page will be the car that is available.


