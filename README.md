# National Health Mission (NHM) Database Management System

This project is a Database Management System (DBMS) developed in context of **National Health Mission (NHM)** of India. The system is designed to manage hospital operations and immunization records, supporting public health initiatives. It centralizes data storage and management for healthcare services, including patient records, healthcare workers, vaccinations, and hospital inventory.

## Project Overview

The **National Health Mission (NHM)** is a public health initiative by the Government of India, aimed at providing affordable and quality healthcare, particularly to underserved areas. This DBMS project focuses on two main components:

- **Hospital Management**: Storing patient records, managing treatments, and overseeing hospital resources.
- **Immunization Management**: Tracking vaccination schedules, vaccine inventories, and healthcare worker assignments.

For this project, we are taking **Assam** as the case study. The database has been designed after gathering insights and suggestions from officials working for NHM Assam. The structure has been tailored to meet the specific needs and challenges faced by healthcare facilities in Assam, ensuring that it aligns with real-world practices in the region.

## Features

- **Patient Management**: Manage patient data, including demographics, medical history, and treatments.
- **Healthcare Worker Management**: Track healthcare worker details, designations, and hospital assignments.
- **Hospital Resource Management**: Oversee hospital information, including inventory and resources.
- **Immunization Tracking**: Record vaccination details, doses, and vaccination centers.
- **Inventory Management**: Manage hospital inventory, restocking schedules, and expiry dates.

## Database Structure

The database consists of several key tables, each serving a specific purpose:

1. **baby_child**: Stores details of babies and children, including their mother’s ID, name, date of birth, and gender.
2. **healthcare_workers**: Records healthcare worker information such as worker ID, name, designation, contact details, and hospital assignments.
3. **hospitals**: Contains information about hospitals, including names, types, locations, and contact details.
4. **inventory**: Manages hospital inventory items such as supplies, quantities, restocking dates, and expiry dates.
5. **medical_records**: Tracks patient treatment history, including diagnoses, prescriptions, and consultation details.
6. **mothers**: Stores information related to mothers, including personal and pregnancy details.
7. **patients**: Contains patient details, such as Aadhar ID, enrollment date, and demographic information.
8. **treatments_consultations**: Manages patient consultations, diagnoses, treatments, and hospital/worker details.
9. **vaccination_centres**: Records vaccination center details, including locations and contact information.
10. **vaccinations**: Tracks vaccinations administered, doses, healthcare workers, and center details.
11. **vaccines**: Stores information about vaccines, including dosage, age group, and administration method.

## ER Diagram

The Entity-Relationship (ER) diagram provides a visual representation of the relationships between the tables in the database. This diagram is essential for understanding how the different entities in the system are interconnected.

![ER Diagram](https://github.com/user-attachments/assets/e623a5bf-a2b4-43e0-b3c7-98e8de583779)

## How This Database Helps

This database serves as an efficient solution for managing healthcare data under the NHM. By centralizing patient, hospital, and vaccination information, the system ensures smoother operations and real-time data accessibility. The database simplifies the management of immunization schedules, medical records, and hospital resources, improving the overall efficiency of the healthcare system.

## Future Scope

Potential future enhancements for this system include:

- **Predictive Analytics**: Incorporating data analytics to forecast resource needs and track health trends.
- **Integration with Government Systems**: Expanding the system to connect with national health databases for improved data sharing.
- **Mobile Application Development**: Allowing healthcare workers to update records in real-time via mobile devices.
- **Disease Surveillance**: Adding features to track disease outbreaks and improve rapid response efforts.
