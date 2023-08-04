# Hospital-Management-System-SQL

## Project Description
This project implements a basic Hospital Management System using SQL. The system is created using MySQL and demonstrates a variety of SQL skills including creating tables, inserting values, and defining relationships between tables.

## Database Schema
The database consists of the following tables:

1. **Doctors**: Stores details about each doctor including their ID, first name, last name, specialty, contact information, and availability.
2. **Patients**: Stores information about each patient including their ID, first name, last name, date of birth, gender, and contact information.
3. **Appointments**: Holds information about each appointment including the appointment ID, doctor ID, patient ID, date, time, and a brief description.
4. **Medical Records**: Contains medical records for each patient including the record ID, patient ID, doctor ID, visit date, diagnosis, prescribed medication, and any additional notes.
5. **Billing**: Maintains billing information including the bill ID, patient ID, bill date, amount due, due date, and payment status.

Each table is related to one another with foreign keys to create relationships between the data.

## Setup
To set up this project on your local machine:

1. Install MySQL or any SQL database you prefer.
2. Create a new database and use it.
3. Execute the SQL scripts to create the tables.
4. Insert the provided sample data into the tables.

## Code
SQL scripts for creating the tables and inserting sample data can be found in the repository.

## Use Cases
This system can be used to manage a hospital's operations including managing doctors, patients, appointments, medical records, and billing information. For example, you can run queries to find a patient's medical history, check a doctor's availability, or determine the payment status of a bill.

## Future Improvements
The current system is a basic implementation and can be further improved. Some potential improvements include adding more tables such as for hospital departments, adding more complex queries, or developing a front-end interface to interact with the database.
