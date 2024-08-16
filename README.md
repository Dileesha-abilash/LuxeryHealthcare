# Luxury Healthcare

Luxury Healthcare is a comprehensive Fullstack Project designed to streamline and automate the daily operations of a medical practice. The system comprises two applications: one for administrators and another for patients. It includes features for managing patients, drugs, appointments, and secure user authentication.

## Features

- **Patient Management:**
    
    - Add, view, update, and delete patient records.
    - Advanced patient search functionality.
    - Online queue management for appointments.
    - Detailed tracking of patient medical history and visits.
    - User registration and management.
- **Drug Management:**
    
    - Comprehensive drug inventory management.
    - Add or remove drugs from the inventory.
- **Appointment Management:** _(Ongoing Development)_
    
    - Schedule, view, and manage doctor appointments.
    - Automated reminders and notifications for appointments.
- **User Authentication:**
    
    - Secure login system for doctors, staff, and patients.
    - Role-based access control to ensure data security.

## Tech Stack

### Frontend

- **React Native**
    - **State Management:** Context API
    - **Navigation:**
        - Bottom Tabs
        - Drawer
        - Stack Navigation
    - **Data Fetching:** React Query
    - **Local Storage:** AsyncStorage
    - **Camera Access:** RN Camera

### Backend

- **Golang**
    - Authentication handling
    - File management
    - Database interactions

### Database

- **MongoDB Serverless (NoSQL)**

### Authentication

- **JWT (JSON Web Tokens)**

### Cloud Infrastructure

- **AWS**
    - **Lambda Functions:** Serverless computing
    - **API Gateway:** RESTful APIs
    - **S3:** Secure file storage

### Docker

- **Lambda Function**: Build and invoke serverless functions with Docker
