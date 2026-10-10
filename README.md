

# Bus Booking System

## Overview
The Bus Booking System is a Java-based desktop application developed using Java Swing and NetBeans. It allows users to log in, search for bus journeys, select seats, enter passenger details, and complete a simulated payment using a UPI ID.

The project demonstrates the use of Java GUI components, event handling, input validation, and multiple interconnected screens.

## Features
- **Login:** User login interface.
- **Bus Search:** Search for buses based on journey details.
- **Seat Selection:** Select seats for the journey.
- **Passenger Details:** Enter passenger information.
- **Payment:** Enter and validate a UPI ID.
- **Ticket Generation:** Display a booking confirmation ticket after simulated payment.

## Technologies Used
- Java
- Java Swing
- Apache NetBeans IDE
- Git and GitHub

## Application Workflow
1. Login
2. Search for a Bus
3. Select Seats
4. Enter Passenger Details
5. Enter UPI ID and Confirm Payment
6. Display the Booking Ticket

## Project Structure
```text
Bus-Booking-System/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── mycompany/
│                   └── bus/
│                       ├── LoginFrame.java
│                       ├── SearchFrame.java
│                       ├── SeatFrame.java
│                       ├── PassengerFrame.java
│                       └── BookingsFrame.java
├── nbproject/
├── pom.xml
└── README.md
```

*Note: The folder structure may vary depending on your NetBeans project setup.*

## How to Run
1. Clone or download this repository.
2. Open Apache NetBeans IDE.
3. Select **File → Open Project**.
4. Choose the downloaded project folder.
5. Allow NetBeans to load the project.
6. Run the main login frame or the configured main class.

## Payment Disclaimer
The payment feature is a demonstration only. It validates the format of the entered UPI ID and simulates payment confirmation. It does not process real payments or connect to a payment gateway.

## Future Improvements
- Integrate a real payment gateway.
- Store bookings in a database.
- Display available buses and fares dynamically.
- Generate unique booking IDs and complete tickets.
- Add booking history and cancellation features.

## Author
Developed as a Java Swing project to demonstrate desktop application development and bus booking workflow.
