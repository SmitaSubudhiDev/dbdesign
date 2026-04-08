# 🏥 Clinic Appointment and Diagnostics Platform – ER Diagram

This project contains a database design for a modern clinic system. The goal is to organize clinic operations digitally, including managing doctors, patients, appointments, consultations, diagnostic tests, reports, and payments.

## 📌 Objective

Design an ER diagram for a clinic that supports appointment booking, doctor consultations, diagnostic tests, report generation, and payment tracking. The system should remain simple and focused on clinic-level operations.

## 🧩 Entities Included

The ER diagram contains the following main entities:

* **Doctors** – Stores doctor details and specialization
* **Doctor Departments** – Department information
* **Doctor Specializations** – Medical specialties
* **Patients** – Patient personal and medical details
* **Appointments** – Booking information and status
* **Appointment Type** – Types of appointments
* **Consultations** – Actual patient visits with doctor
* **Tests** – Diagnostic tests prescribed during consultation
* **Reports** – Test reports generated later
* **Payments** – Payment transaction records

## 🔗 Workflow Design

The database follows this clinic workflow:

Patient → Appointment → Consultation → Tests → Reports
↘
Payments

* A patient can book multiple appointments
* An appointment may result in a consultation
* A consultation can prescribe multiple tests
* Each test generates a report
* Payments are linked to appointments

## 🎯 Design Considerations

* Appointment and consultation are separate entities
* One patient can have multiple visits
* One doctor can attend many patients
* One consultation can have multiple tests
* Reports are generated after tests
* Doctor specialization is stored separately
* The structure avoids redundant data and keeps normalization

## 📊 Questions Supported by Design

This ER diagram can answer:

* Who are the doctors and their specialties?
* Which patient booked which appointment?
* What was the appointment status?
* Did the appointment result in consultation?
* Were diagnostic tests prescribed?
* What reports were generated?
* Can one patient have multiple visits?
* Can one doctor attend multiple patients?
* Can one consultation lead to multiple tests?
* How payments are connected to appointments?

## 🚀 Scope

This design is intended for:

* Small to medium clinics
* Appointment-based consultation systems
* Diagnostic test tracking
* Report management
* Basic clinic payment handling

The schema is kept simple, normalized, and scalable for future enhancements.
