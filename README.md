# Database-for-Hospital-management-system
This SQL code builds a structured hospital database system to manage essential hospital data, including information on patients, doctors, appointments, diagnoses, medications, test results, and billing.
# Hospital Management Database

This repository contains SQL code for creating a relational database designed to manage hospital information. It includes tables for patients, doctors, appointments, diagnoses, medications, test results, and billing records, providing a structured approach to handle various aspects of hospital operations.

## Database Structure

The database consists of the following tables:

- **Patient**: Stores patient information such as name, date of birth, gender, and contact details.
- **Doctor**: Maintains records of doctors, including their specialization, contact number, and email.
- **Appointment**: Links patients and doctors, storing appointment dates, reasons, and status (e.g., scheduled, completed).
- **Diagnosis**: Logs diagnoses for patients, including the doctor who made the diagnosis and a brief description.
- **Medication**: Tracks prescribed medications, dosages, frequency, and duration.
- **TestResult**: Records test results for patients, detailing the test name and outcome.
- **Billing**: Stores billing details related to appointments, including total amount and payment status.

## Sample Data

The script includes sample data for each table to help demonstrate the database’s functionality and query potential. For example, sample patients, doctors, and their respective appointments are inserted to facilitate testing and understanding of table relationships.

## Queries

Several SQL queries are provided to perform common data retrieval tasks:
1. Count completed appointments.
2. Show doctors and their specializations.
3. Retrieve patient details for a specific appointment.
4. List all appointments with doctor details.
5. Find patients with diagnosis details.
6. List test results with patient names.
7. Display billing details for unpaid appointments.
8. List all medications prescribed by a specific doctor.

## Getting Started

To set up this database, run the SQL script in your preferred database management system. The tables and data will be created, allowing you to test and extend the database as needed.
