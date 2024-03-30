# Restaurant Reservation System

Welcome to the Restaurant Reservation System repository! This project was developed as a full stack application, focusing on reservation management for fine dining restaurants. The system is designed to be used exclusively by restaurant personnel for handling reservation requests received via phone calls.

## Purpose

The Restaurant Reservation System aims to streamline the reservation process for fine dining establishments, providing restaurant managers with the tools they need to efficiently manage incoming reservation requests, seat guests, and maintain accurate records of reservations. By digitizing and automating reservation management tasks, the system enhances the overall dining experience for both customers and restaurant staff.

## Functionality and User Cases

### Reservation Creation and Management

- **Create Reservation**: Restaurant managers can create new reservations when customers call to request a booking. They can input details such as customer name, mobile number, reservation date, time, and party size.
  
- **View Reservations**: The system allows managers to view all reservations for a specific date on the dashboard. Reservations are sorted by time, and managers can navigate through different dates using next, previous, and today buttons.

- **Seat Reservation**: Upon arrival, managers can assign a reservation to a specific table, indicating whether the table is occupied or free. 

- **Edit Reservation**: Managers have the ability to modify existing reservations if customers call to change or cancel their booking. This includes updating reservation details or marking a reservation as cancelled.

### Validation and Error Handling

- **Validation**: The system validates reservation inputs to ensure data integrity and accuracy. It checks for constraints such as valid reservation dates, future reservation times, and available seating capacity.

- **Error Handling**: Error messages are displayed to users when validation constraints are violated or when errors occur during the reservation process. These messages provide informative feedback to guide users in correcting their inputs.

### Search Functionality

- **Search by Phone Number**: Restaurant managers can search for reservations by entering a customer's phone number (partial or complete). The system retrieves matching records from the database, allowing managers to quickly access customer reservations.

### Reservation Status Management

- **Reservation Status**: Each reservation is assigned a status (booked, seated, or finished) to indicate its current state in the reservation lifecycle. Managers can track the status of reservations and take appropriate actions based on their status.
