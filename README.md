# Learning-Management-System
A learning management system or LMS is software that helps you organize, deliver, and track online training.

## Project Overview
This repository documents the requirements for a university Learning Management System.

## Stakeholders
- **Students** - Need to submit tasks, view deadlines, download materials
- **Lecturers** - Need to manage course materials and set deadlines
- **Administrators** - Need to manage user accounts and system settings

---

## Functional Requirements

| ID | Description |
|----|-------------|
| FR-01 | The system shall allow the student to view the timetable and submission deadlines for all tasks. |
| FR-02 | The system shall allow the student to upload, edit, delete and re-upload their submitted tasks. |
| FR-03 | The system shall allow the student to download course materials for offline viewing. |
| FR-04 | The system shall allow the lecturer to create, update and manage course materials or tasks. |
| FR-05 | The system shall allow the lecturer to set and update task deadlines for each course. |
| FR-06 | The system shall allow users to register and log in to the system. |
| FR-07 | The system shall allow admin to review and manage system issues. |
| FR-08 | The system shall allow admin to manage user accounts. |
| FR-09 | The system shall allow admin to manage system settings. |
| FR-10 | The system shall grant access to functions based on user role. |

---

## Non-Functional Requirements

| ID | Description |
|----|-------------|
| NFR-01 | The system must respond to user actions within 3 seconds. |
| NFR-02 | The system must be available anytime and anywhere (24/7 availability). |
| NFR-03 | The system must be able to handle up to 100 concurrent users at once. |
| NFR-04 | The system must require a minimum of 8 characters for user passwords. |

---

## MoSCoW Prioritization

| Requirement | Priority | Justification |
|-------------|----------|----------------|
| FR-01 | Should | Important for student planning |
| FR-02 | Must | Core functionality - students must submit tasks |
| FR-03 | Could | Nice to have but not essential |
| FR-04 | Must | Lecturers need to upload materials |
| FR-05 | Must | Deadlines are essential for organization |
| FR-06 | Must | Login is required for system access |
| FR-07 | Should | Important for maintenance |
| FR-08 | Must | Admin must control user accounts |
| FR-09 | Should | Settings can be hardcoded initially |
| FR-10 | Must | Role-based access is critical for security |

---

## Traceability Matrix

| Requirement | Depends On |
|-------------|------------|
| FR-01 (View deadlines) | FR-05 |
| FR-02 (Upload tasks) | FR-05, FR-04 |
| FR-03 (Download materials) | FR-04 |
| FR-04 (Manage materials) | None |
| FR-05 (Set deadlines) | None |
| FR-06 (Login) | None |
| FR-07 (Manage issues) | FR-06 |
| FR-08 (Manage accounts) | FR-06, FR-10 |
| FR-09 (System settings) | FR-06 |
| FR-10 (Role access) | FR-06 |
