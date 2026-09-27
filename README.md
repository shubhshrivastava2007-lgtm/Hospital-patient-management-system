# Hospital-patient-management-system
# 🏥 Hospital Patient Management System

## 📌 Project Overview

The **Hospital Patient Management System** is a basic Python project designed to manage different activities of a hospital.
This project is developed using **basic Python concepts only**. It does not use SQL, SQLite, Streamlit, or any external libraries.
The system provides different modules for managing patients, doctors, rooms, appointments, admissions, medicines, payments, and hospital reports.
---

## 🎯 Objectives

The main objectives of this project are:

- To maintain patient information.
- To manage doctors and their specializations.
- To check room availability.
- To assign rooms to patients.
- To manage patient admission and discharge.
- To book and view appointments.
- To maintain medicine records.
- To generate patient bills.
- To manage payments.
- To display basic hospital reports.
- To practice fundamental Python programming concepts.

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Level:** Beginner / Basic Python
- **Database:** None
- **External Libraries:** None
- **Interface:** Console / Terminal

### Python Concepts Used

- Variables
- Lists
- Dictionaries
- Functions
- `if`, `elif`, `else`
- `for` loops
- `while` loops
- User input
- Basic calculations
- Global variables
- Searching through lists

---

## 📂 Project Modules

### 1. 👤 Patient Management

This module manages patient information.

**Features:**

- Add a new patient
- View all patients
- Search for a patient
- Update patient information
- Delete patient information

**Patient Information:**

- Patient ID
- Name
- Age
- Gender
- Phone number
- Address
- Health problem
- Assigned doctor
- Assigned room
- Admission status

---

### 2. 👨‍⚕️ Doctor Management

This module manages hospital doctors.

**Features:**

- View doctors
- View doctor specializations
- Assign a doctor to a patient

Example specializations:

- General Physician
- Cardiologist
- Orthopedic
- Dermatologist

---

### 3. 🛏️ Room Management

This module manages hospital rooms.

**Features:**

- View all rooms
- Check available rooms
- Assign a room
- Release a room

**Room Types:**

- General
- Private
- ICU

Each room can have one of two statuses:

```text
Available
Occupied

### 4. 📅 Appointment Management

This module manages patient appointments.

**Features:**

- Book an appointment
- View appointments

**Appointment Information:**

- Appointment ID
- Patient ID
- Patient name
- Doctor
- Date
- Time

---

### 5. 🏥 Admission & Discharge

This module manages patient admission and discharge.

**Admission Process:**

1. Enter the patient ID.
2. Select an available room.
3. The room becomes occupied.
4. The patient's admission status becomes `True`.

**Discharge Process:**

1. Enter the patient ID.
2. Find the patient's assigned room.
3. The room becomes available.
4. The patient's admission status becomes `False`.

---

### 6. 💊 Medicine Management

This module manages medicines given to patients.

**Features:**

- Add medicine
- View medicine records
- Calculate medicine cost

**Medicine Information:**

- Patient ID
- Patient name
- Medicine name
- Quantity
- Price per unit
- Total medicine cost

**Calculation:**

```text
Total Medicine Cost = Quantity × Price

## 7. 💰 Payment & Billing

This module manages hospital bills and payments.

### Features

- Generate bill
- Calculate total bill
- Make payment
- View payment history

### Bill Components

```text
Consultation Fee
Room Charges
Medicine Charges
Other Charges

=============================================================
                 HOSPITAL REPORT
=============================================================

Total Patients: 10
Total Doctors: 4
Total Rooms: 7
Occupied Rooms: 3
Available Rooms: 4
Total Appointments: 8
Total Paid Revenue: 12500

