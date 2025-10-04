# E-Hospital-Management-System
## Overview
A Database Management System (DBMS) project developed to digitalize hospital operations and enhance efficiency. This system integrates Java (Swing GUI) with Oracle SQL Database to manage patients, doctors, appointments, and billing in a unified and automated platform. It ensures accuracy, data security, and smooth workflow across hospital departments.
## Technologies Used
Java (Swing): For building the graphical user interface (GUI).

Oracle Database (SQL): For secure and reliable data storage.

JDBC (Java Database Connectivity): For communication between Java and Oracle Database.
## Methodology
### Frontend Development:
Developed using Java Swing for user-friendly and interactive forms.

### Backend Development:
Connected with Oracle Database using JDBC to perform CRUD operations.

### Integration:
Ensures real-time synchronization between modules like Patients, Doctors, Appointments, and Billing.

### Testing & Validation:
Verified data integrity, error handling, and transaction accuracy through sample test cases.
## Key Features
Patient Management: Add, update, and view patient details.

Doctor Management: Store doctor profiles and specialization details.

Appointment Scheduling: Book appointments with specific doctors.

Billing System: Generate and manage billing records.

Secure Login: Access control for different user roles.

Database Connectivity: Reliable integration with Oracle Database using JDBC.
## Database Design
### Main Tables
Patients: Stores patient details.

Doctors: Contains doctor information.

Appointments: Records patient appointments with doctors.

Billing: Handles financial transactions and payment details.
### Entity Relationship
Patients → Appointments: One-to-Many

Doctors → Appointments: One-to-Many

Patients → Billing: One-to-One
