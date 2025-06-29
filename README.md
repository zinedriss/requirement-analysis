# Requirement Analysis in Software Development

---

## What is Requirement Analysis?

Requirement Analysis is a systematic process of gathering, analyzing, and documenting the needs and expectations of stakeholders for a software project. It focuses on understanding **what the system should do**, ensuring that the end product aligns with business goals and user needs.

This phase is crucial because:
- It bridges the gap between client expectations and developer implementation.
- It helps identify technical and business requirements early.
- It forms the foundation for design, development, and testing phases.

Without accurate requirement analysis, projects are at risk of scope creep, miscommunication, delays, or failure to meet user needs.

---

## Why is Requirement Analysis Important?

Requirement Analysis plays a critical role in SDLC due to several key reasons:

- **Clarity and Alignment**  
  Ensures all stakeholders have a shared understanding of the system requirements.

- **Cost and Time Efficiency**  
  Detecting issues during the requirement phase is much cheaper and quicker than fixing them during development or post-deployment.

- **Foundation for Testing and Design**  
  Requirements serve as a basis for writing test cases and designing system architecture, leading to better quality assurance and structured development.

---

## Key Activities in Requirement Analysis

- **Requirement Gathering**  
  Collecting data from stakeholders using interviews, surveys, documents, and observation.

- **Requirement Elicitation**  
  Drawing out hidden or implicit needs from users through techniques like brainstorming, workshops, and prototyping.

- **Requirement Documentation**  
  Clearly recording requirements in a structured format such as SRS (Software Requirements Specification), user stories, or use cases.

- **Requirement Analysis and Modeling**  
  Analyzing, prioritizing, and modeling requirements using diagrams, flowcharts, or UML to validate feasibility and completeness.

- **Requirement Validation**  
  Reviewing and confirming requirements with stakeholders to ensure they accurately reflect business goals and user needs.

---

## Types of Requirements

### Functional Requirements
Functional requirements describe the specific behavior or functions of a system.

**Examples (Booking Management System):**
- Users can **create** an account.
- Admin can **approve or reject** a booking request.
- Users can **search** and **filter** available booking slots.
- System sends **confirmation emails** after successful booking.

### Non-functional Requirements
Non-functional requirements describe **how** the system performs its functions, including quality attributes.

**Examples (Booking Management System):**
- The system must handle **up to 10,000 concurrent users**.
- Booking responses should be processed within **2 seconds**.
- The application should be **available 99.9% of the time**.
- The UI should be accessible via **mobile devices** and **desktop** browsers.

---

## Use Case Diagrams

Use Case Diagrams are part of UML (Unified Modeling Language) and illustrate the interactions between **actors** (users or systems) and **use cases** (system functionalities).

### Benefits:
- Provide a high-level overview of system functionality.
- Identify different user roles and how they interact with the system.
- Help communicate scope and boundaries effectively.

### Example: Booking System Use Case Diagram

![Booking System Use Case Diagram](alx-booking-uc.png)

---

## Acceptance Criteria

Acceptance Criteria define the **conditions that must be met** for a feature to be accepted by stakeholders. It helps ensure that all parties understand the scope and functionality of a requirement.

### Importance:
- Prevents misunderstandings.
- Guides development and testing.
- Provides a clear definition of "done."

### Example: Checkout Feature (Booking Management System)

**Feature**: Booking Checkout

**Acceptance Criteria**:
- User must be logged in to access the checkout page.
- User can view booking summary including date, time, and cost.
- System calculates total cost including applicable taxes.
- User can choose a payment method and complete the payment.
- Confirmation email is sent after successful payment.
- If payment fails, user receives an error message and is prompted to retry.

---
