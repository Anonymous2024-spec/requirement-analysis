# Requirement Analysis in Software Development
This repository explores the concept, process, and importance of Requirement Analysis in the Software Development Lifecycle (SDLC). It includes definitions, types, key activities, and practical diagrams and examples related to a booking management system.

## What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, and defining what a software system should do and what constraints it must operate under. It forms the foundation of the software development lifecycle by clarifying what the stakeholders need from the system.

It helps bridge the gap between users and developers, ensuring a shared understanding of the expected functionality and constraints before design or development begins.

## Why is Requirement Analysis Important?

1. **Reduces Misunderstandings:** It ensures all stakeholders have a shared understanding of the software’s functionality.

2. **Saves Time and Cost:** Catching requirement issues early prevents costly changes during development or testing.

3. **Improves Quality:** Clear requirements lead to better design, fewer bugs, and improved user satisfaction.

## Key Activities in Requirement Analysis

- **Requirement Gathering**: Collecting initial needs from stakeholders using surveys, interviews, and observations.

- **Requirement Elicitation**: Actively engaging stakeholders to draw out hidden needs, constraints, and expectations.

- **Requirement Documentation**: Writing clear and structured requirement documents like SRS (Software Requirements Specification).

- **Requirement Analysis and Modeling**: Analyzing and structuring requirements using models such as use cases, flowcharts, and data models.

- **Requirement Validation**: Ensuring the requirements are complete, feasible, and aligned with business goals through reviews and sign-offs.

## Types of Requirements

### Functional Requirements
These define what the system should do — the features and functions.

**Examples for Booking Management System:**
- A user can book an appointment online.
- Admin can view all bookings.
- Users can cancel or reschedule appointments.

### Non-functional Requirements
These define *how* the system performs — quality attributes like performance and security.

**Examples:**
- The system should load booking data within 2 seconds.
- All user data must be encrypted.
- The system must support 1000 concurrent users.

## Use Case Diagrams

Use Case Diagrams visually represent the interactions between users (actors) and the system’s functions (use cases).

They help in:
- Clarifying system scope
- Identifying key interactions
- Communicating functionality clearly to all stakeholders

![Booking System Use Case Diagram](![alx-booking-uc](https://github.com/user-attachments/assets/d90cb5d7-0f05-4360-8ceb-1b2c97308647)
)

## Acceptance Criteria

Acceptance Criteria are conditions that must be met for a feature to be considered complete and acceptable by the stakeholder. They ensure clarity between developers and clients about expected behavior.

### Example: Checkout Feature – Booking Management System

**Scenario:** A user wants to finalize a booking.

**Acceptance Criteria:**
- User must be logged in.
- Booking summary is shown before payment.
- System must validate available slots.
- A confirmation email is sent after checkout.
- Booking status changes to “confirmed”.

These criteria help guide development, testing, and final approval.
