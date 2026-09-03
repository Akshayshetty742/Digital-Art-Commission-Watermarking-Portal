# Digital Art Commission & Watermarking Portal

## Software Engineering Labs

### Problem Statement #58 — Media, Events & Community

This repository contains the work completed for the Software Engineering Lab assignments based on the assigned problem statement:

**Digital Art Commission & Watermarking Portal**

The system is an art commission platform where clients submit visual creative briefs, digital artists submit watermarked work-in-progress drafts, and final high-resolution source files are unlocked after milestone payment.

---

# Lab 1 — Requirements Engineering & UML Use-Case Modelling

## Objective

The objective of Lab 1 is to identify and document the functional and non-functional requirements of the Digital Art Commission & Watermarking Portal and model the system using a UML use-case diagram and use-case flow.

## Actors

- Client Buyer
- Digital Artist
- Payment Gateway

## Deliverables

### 1. Requirements Table

The requirements table contains exactly:

- 5 Functional Requirements (FR-001 to FR-005)
- 2 Non-Functional Requirements (NFR-001 to NFR-002)

Each requirement contains:

- Requirement ID
- Type
- Description
- Priority
- Acceptance Criteria
- Rationale

### 2. UML Use-Case Diagram

The use-case diagram represents the interaction between the actors and the Digital Art Commission & Watermarking Portal.

The diagram includes:

- Client Buyer
- Digital Artist
- Payment Gateway
- Main system use cases
- `«include»` relationships
- `«extend»` relationship

### 3. Use-Case Flow

The use-case flow is based on:

**UC-03 — Make Milestone Payment**

It contains:

- Preconditions
- Postconditions
- Main Success Scenario
- Alternate Flow for payment failure

## Lab 1 Files

- `Requirements_Table.xlsx`
- `Use_Case_Diagram.pdf`
- `Make_Milestone_Payment_Flow.pdf`

---

# Lab 2 — Component Modelling & Architectural Design

## Objective

The objective of Lab 2 is to identify the major software components of the Digital Art Commission & Watermarking Portal, define the interfaces between them, and select a suitable architectural style.

## Selected Architecture

**Layered Architecture**

The architecture separates the system into different responsibilities such as the user interface, commission management, supporting services, and data storage.

## Main Components

The component diagram contains the following components:

1. Client Portal
2. Digital Artist Portal
3. Commission Management Service
4. Payment Service
5. Watermark Service
6. File Storage & Download Service
7. Database

## Main Interfaces

The component diagram represents interfaces such as:

- Client Request Interface
- Artist Request Interface
- Payment Service Interface
- Watermark Service Interface
- File Storage Interface
- Data Access Interface

The diagram uses UML component notation and shows the interactions and dependencies between the components.

## Architecture Justification

The written justification explains:

- Why Layered Architecture was selected
- Two reasons for selecting the architecture
- Security advantage
- Performance advantage

## Lab 2 Files

- `Component_Diagram.pdf`
- `Architecture_Justification.pdf`

---

# Project Workflow

The Digital Art Commission & Watermarking Portal supports the following general workflow:

1. Client submits a creative brief.
2. Artist views the project requirements.
3. Artist uploads a work-in-progress draft.
4. The system applies a watermark to the draft.
5. Client reviews the watermarked draft.
6. Client makes the required milestone payment.
7. The payment is processed through the payment service.
8. The final high-resolution artwork is released after successful payment.
9. Client downloads the final artwork through secure file access.

---

# Repository Structure

```text
Digital-Art-Commission-Watermarking-Portal/
│
├── README.md
│
├── Requirements_Table.xlsx
├── Use_Case_Diagram.pdf
├── Make_Milestone_Payment_Flow.pdf
├── Component_Diagram.pdf
└── Architecture_Justification.pdf

Conclusion

Labs 1 and 2 model the Digital Art Commission & Watermarking Portal from different software engineering perspectives.

Lab 1 focuses on requirements engineering and UML use-case modelling.

Lab 2 focuses on component modelling and architectural design.

Both labs are based on the same assigned problem statement:

Digital Art Commission & Watermarking Portal — Problem Statement #58.
