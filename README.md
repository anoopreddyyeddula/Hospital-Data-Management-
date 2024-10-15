# Hospital Data Management System

## Overview

The **Hospital Data Management System** is designed to efficiently manage various aspects of hospital operations, including patients, doctors, appointments, medical tests, prescriptions, admissions, and billing. The system leverages **PostgreSQL** as the relational database management system (RDBMS) and **Python** for data processing and cleaning. The project streamlines hospital operations by maintaining well-structured relational database tables, performing data queries, and extracting insights to improve patient care and hospital management.

## Features

- **Patients Management**: Stores comprehensive details such as patient ID, contact information, date of birth, blood group, and insurance details.
- **Doctors Management**: Manages doctor information, including their specialties and contact details.
- **Appointments Tracking**: Tracks patient appointments with doctors, including reasons for visits and scheduled times.
- **Medical Tests**: Logs medical tests, including the type of test, results, and the date it was conducted.
- **Prescriptions**: Manages prescriptions issued to patients, recording details like dosage, medication name, and frequency.
- **Admissions and Room Management**: Handles patient admissions, room allocations, and attending doctor assignments.
- **Insurance and Billing**: Manages insurance and billing details for appointments, tests, and admissions.

## Technologies Used

- **PostgreSQL**: The system uses a PostgreSQL relational database to manage various tables for patients, doctors, appointments, tests, and billing.
- **Python (Pandas, NumPy)**: Python is used to clean and process raw datasets, particularly using libraries like Pandas for data manipulation and NumPy for handling numerical data efficiently.
- **Data Cleaning**: Processes such as removing extra spaces, handling missing values, converting data types, and resetting indices were automated using Python for maintaining clean and accurate data.

## Database Schema

The following database tables were designed to manage hospital operations:

1. **Patients Table**: Stores patient information such as name, contact info, blood group, and insurance details.
2. **Doctors Table**: Maintains doctor records including their ID, specialization, and contact details.
3. **Appointments Table**: Tracks patient appointments with doctors, including time, date, and reason for the visit.
4. **Medical Tests Table**: Logs medical tests such as the name of the test, results, and dates of tests.
5. **Prescriptions Table**: Manages patient prescriptions, including medication details, dosage, and frequency.
6. **Admissions Table**: Records patient admissions, room details, and attending doctor information.
7. **Insurance and Billing Table**: Manages billing and insurance information for patient visits, tests, and admissions.

## Data Cleaning and Processing

Data cleaning was performed using the **Pandas** library to prepare the data for analysis and management. The process involved:

- Removing extra spaces in column names.
- Dropping rows with missing or incomplete data.
- Converting data types to ensure consistency.
- Resetting indices and saving cleaned data back to CSV files for future use.

## Sample Queries

Some common queries executed in the system include:

- Retrieving all patients scheduled for appointments with a specific doctor.
- Calculating the number of patients who visited the hospital each month.
- Determining the most commonly prescribed medications.
- Identifying patients who haven't visited in the last six months.
- Listing patients who underwent specific tests, such as MRI scans.
