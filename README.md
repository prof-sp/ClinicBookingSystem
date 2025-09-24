
🏥 Clinic Booking System – Database Schema
📘 Overview
This project defines a relational database schema for a Clinic Booking System. It manages patients, doctors, appointments, treatments, and medical specializations. 
The schema is designed to support efficient scheduling, treatment tracking, and doctor-patient relationships.

🗂️ Database Structure
📌 Tables Included:
Specializations: Medical fields (e.g., Cardiology, Pediatrics).

Doctors: Registered medical professionals.

Patients: Individuals receiving medical care.

Appointments: Scheduled meetings between patients and doctors.

Treatments: Medical procedures or prescriptions linked to appointments.

🔗 Relationships
Relationship Type	Description
One-to-Many	One doctor can have many appointments.
One-to-Many	One patient can have many appointments.
One-to-Many	One appointment can have multiple treatments.
Many-to-One	Many doctors can share one specialization.

🛠️ SQL Features Used
PRIMARY KEY for unique identification of records.

FOREIGN KEY constraints to enforce relationships.

NOT NULL to ensure required fields are populated.

UNIQUE constraints for fields like email to prevent duplicates.

AUTO_INCREMENT for automatic ID generation.

📂 File Contents
The .sql file includes:

CREATE DATABASE ClinicBookingSystem;

CREATE TABLE statements for all entities.

Relationship constraints using FOREIGN KEY.

🚀 Getting Started
To set up the database:

Open your SQL client (e.g., MySQL Workbench).

Run the .sql file to create the schema.

Begin inserting data or building application logic on top.

📈 Future Enhancements
Add user authentication for doctors and patients.

Include billing and invoice tracking.

Support appointment status (e.g., Scheduled, Completed, Cancelled).

Add indexing for faster query performance.
