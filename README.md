# Requirement Analysis in Software Development

## Introduction
This repository focuses on Requirement Analysis in Software Development. It explores its role, activities, and importance in the Software Development Life Cycle (SDLC), with practical examples from a booking management system.

---

## What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, analyzing, and documenting the needs and requirements of stakeholders for a new or altered product or system.

It serves as the foundation for all subsequent phases in the software development lifecycle. A well-executed requirement analysis ensures that the software meets the expectations of users and business goals.

Key goals include:
- Understanding stakeholder needs
- Defining project scope
- Preventing scope creep and misunderstandings
- Providing a base for design and testing

---

## Why is Requirement Analysis Important?

1. **Clarifies Project Scope**
   - Helps avoid misunderstandings and rework by clearly defining what the system should do.

2. **Ensures Stakeholder Alignment**
   - Keeps developers, testers, and business stakeholders on the same page regarding project expectations.

3. **Reduces Risks**
   - Early identification of issues helps minimize costly changes during later stages of development.

---

## Key Activities in Requirement Analysis

- **Requirement Gathering**
  - Collecting raw information from stakeholders about their expectations.

- **Requirement Elicitation**
  - Actively engaging with stakeholders through interviews, surveys, or brainstorming to extract precise requirements.

- **Requirement Documentation**
  - Creating detailed documentation that outlines all functional and non-functional requirements.

- **Requirement Analysis and Modeling**
  - Evaluating requirements for feasibility, consistency, and completeness, and creating models (e.g., use case diagrams).

- **Requirement Validation**
  - Ensuring all documented requirements reflect stakeholder needs and are realistic and testable.

---

## Types of Requirements

### Functional Requirements
These define **what** the system should do.

**Examples (Booking Management System):**
- Users can search for available bookings.
- Admin can add, update, or delete listings.
- Customers can book and cancel reservations.

### Non-functional Requirements
These define **how** the system performs functions.

**Examples:**
- The system must support 1,000 concurrent users.
- Booking confirmations must be sent via email within 2 minutes.
- The system must be accessible 99.9% of the time.

---

## Use Case Diagrams

Use Case Diagrams are visual representations of the interactions between users (actors) and the system. They help identify system functionalities and user roles.

**Benefits:**
- Clarify system functionality.
- Identify user interactions.
- Help with requirement validation and communication.

### Booking System Use Case Diagram

![Use Case Diagram](alx-booking-uc.png)

_Actors:_
- Customer
- Admin
- Payment Gateway

_Use Cases:_
- Search for bookings
- Make a booking
- Cancel a booking
- Process payment
- Manage listings

> Diagram created using [Draw.io](https://draw.io)

---

## Acceptance Criteria

Acceptance Criteria define the specific conditions under which a software feature is considered complete and functioning as expected.

**Importance:**
- Ensures stakeholder expectations are met.
- Provides clear goals for developers and testers.
- Serves as the basis for user acceptance testing (UAT).

**Example: Checkout Feature in Booking Management System**

**Acceptance Criteria:**
- The user must be able to proceed to checkout from the booking summary page.
- The checkout process must include payment input and confirmation.
- A confirmation email must be sent after successful payment.
- If payment fails, the user is prompted to retry or cancel.
- The entire checkout process must be completed in under 3 minutes.

---


