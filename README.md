# MedBook Appointment Scheduling System

MedBook is an interactive healthcare appointment-scheduling prototype created for CSCE 3444. The system is designed to make it easier for patients to schedule, view, reschedule, and cancel medical appointments.

## Interactive Prototype

[Open the MedBook Figma Prototype](https://www.figma.com/make/HmvElm9KIR6DsDfzWhnA5o/User-interface-prototype?p=f&t=JtXVq7GEm4lIG1bw-0)

> Note: MedBook is currently an interactive UI/UX prototype developed in Figma. The repository contains the project documentation, designs, diagrams, testing records, and presentation materials.

## Team Members

- Hamidat Oloko
- Nesna Prasai
- Asif Khan
- Genesis Enemuoh

## Project Purpose

MedBook was designed to:

- Simplify healthcare appointment scheduling.
- Reduce double bookings and scheduling conflicts.
- Improve communication through confirmations and reminders.
- Provide an easy-to-use interface for patients and healthcare providers.
- Allow users to manage appointments from one central location.

## Target Users

MedBook is intended for:

- Patients scheduling healthcare appointments.
- Healthcare providers managing appointments.
- Clinic staff assisting with scheduling and communication.

## Core Features

### User Authentication

- User registration
- Secure login interface
- Account access and profile management

### Appointment Scheduling

- Search for doctors or healthcare services
- Select an available appointment date and time
- Submit an appointment request
- Receive appointment confirmation

### Appointment Management

- View upcoming appointments
- View appointment details
- Reschedule an existing appointment
- Cancel an appointment
- Review appointment history

### Notifications

- Appointment confirmation notifications
- Planned 24-hour appointment reminders
- Appointment status updates

### User Profile

- View profile information
- Update contact information
- Access notification and privacy settings

## Project Requirements

The prototype was designed to satisfy the following functional requirements:

| Requirement | Implementation |
|---|---|
| User Registration | Registration interface included |
| User Login | Login interface included |
| Schedule Appointment | Interactive booking flow included |
| View Appointments | Upcoming appointment dashboard included |
| Reschedule Appointment | Appointment-management flow included |
| Cancel Appointment | Cancellation option included |
| Prevent Double Booking | Included as a system requirement and test case |
| Appointment Confirmation | Confirmation and notification interface included |
| 24-Hour Reminder | Included in the notification design |

## Technology Stack

| Technology | Purpose |
|---|---|
| Figma | UI/UX design and interactive prototyping |
| HTML | Planned frontend page structure |
| CSS | Planned styling and responsive layout |
| GitHub | Version control and project documentation |
| ChatGPT | Brainstorming, wording assistance, and documentation support |
| PowerPoint | Final project presentation |
| Draw.io or diagramming tools | System and data-flow diagrams |

## System Architecture

The proposed MedBook architecture follows a layered structure:

1. The patient interacts with the appointment-scheduling interface.
2. The interface sends appointment requests to an application server.
3. The application server validates the request and checks appointment availability.
4. User and appointment information is stored in the database.
5. The notification service sends confirmations and appointment reminders.

The current version demonstrates the frontend workflow through an interactive Figma prototype. Backend and database components are represented through architecture and design documentation.

## Proposed Database Design

The planned database would contain the following major entities:

### Users

- User ID
- First name
- Last name
- Email
- Phone number
- Password
- User role

### Doctors

- Doctor ID
- Doctor name
- Specialty
- Availability
- Contact information

### Appointments

- Appointment ID
- Patient ID
- Doctor ID
- Appointment date
- Appointment time
- Appointment status
- Reason for visit

### Notifications

- Notification ID
- User ID
- Appointment ID
- Notification type
- Message
- Date sent
- Read status

## Testing

The team conducted prototype-based functional, validation, and user-acceptance testing.

| Feature Tested | Expected Result | Status |
|---|---|---|
| User Registration | User can complete the registration flow | Passed |
| User Login | User can access the dashboard | Passed |
| Schedule Appointment | User can select and confirm an appointment | Passed |
| View Appointments | Upcoming appointments are displayed | Passed |
| Reschedule Appointment | User can select a different date or time | Passed |
| Cancel Appointment | User can cancel an appointment | Passed |
| Double-Booking Prevention | Conflicting time slots should be rejected | Design requirement verified |
| Navigation | Buttons move users to the intended screens | Passed |
| User Profile | Profile information is displayed correctly | Passed |

## Software Development Life Cycle

### Sprint 1

- Selected the project concept
- Gathered project requirements
- Identified target users
- Established team responsibilities

### Sprint 2

- Developed wireframes
- Created the initial Figma prototype
- Designed the system workflow
- Created use-case scenarios

### Sprint 3

- Updated functional and nonfunctional requirements
- Created system architecture documentation
- Developed the ERD and data-flow diagram
- Improved the user interface

### Sprint 4

- Completed prototype testing
- Updated all sprint documentation
- Prepared the final presentation
- Reviewed the project against the requirements

## Current Project Status

The current MedBook deliverable is a high-fidelity interactive Figma prototype. It demonstrates the application's proposed user interface and major appointment-management workflows.

The following components are represented as future implementation work:

- Functional backend server
- Persistent database
- Real authentication
- Email and SMS integration
- Real-time appointment availability
- Production security controls

## Future Improvements

- Develop a working web and mobile application.
- Add a persistent database.
- Implement secure user authentication.
- Add real-time doctor availability.
- Add email, SMS, and push notifications.
- Add telehealth appointments.
- Add multi-factor authentication.
- Add provider reporting and analytics.
- Add online payment support.

## Repository Contents

- `docs/` – Sprint documents, requirements, design documents, testing records, and presentation
- `screenshots/` – Screenshots of the MedBook interface
- `diagrams/` – Architecture, ERD, use-case, and data-flow diagrams
- `prototype/` – Link to the interactive Figma prototype

## Course Information

**Course:** CSCE 3444  
**Project:** Appointment Scheduling System  
**Project Name:** MedBook  
**Team:** Group 13

