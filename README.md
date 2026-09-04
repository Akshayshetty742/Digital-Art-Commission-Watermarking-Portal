# Digital Art Commission & Watermarking Portal

## Project Overview

**PES University CSE — Software Engineering Labs**

**Problem Statement #58:** Digital Art Commission & Watermarking Portal

This project is a portal where clients submit visual creative briefs, digital artists upload watermarked work-in-progress (WIP) drafts, clients review the drafts and request revisions, milestone payments are processed, and the final high-resolution artwork is made available after the required payment.

---

## Jira Project

All project planning and tracking work for the labs was done using Jira.

**Jira Project:** Digital Art Commission  
**Project Key:** KAN

**Jira:** https://akshaysworkspace-46639750.atlassian.net/jira/software/projects/KAN/summary

---

# Lab 1 — Requirements & Use-Case Modelling

### Tasks Completed

- Identified and documented the project requirements.
- Created **5 Functional Requirements (FR-001 to FR-005)**.
- Created **2 Non-Functional Requirements (NFR-001 to NFR-002)**.
- Added priority, acceptance criteria, and rationale for each requirement.
- Created a UML Use-Case Diagram.
- Included the main actors:
  - Client Buyer
  - Digital Artist
  - Payment Gateway
- Added `«include»` relationships.
- Added an `«extend»` relationship.
- Created a one-page use-case flow for **Make Milestone Payment**.
- Included preconditions, postconditions, main success scenario, and an alternate payment-declined flow.

### Lab 1 Deliverables

- `Requirements_Table.xlsx`
- `Use_Case_Diagram.pdf`
- `Make_Milestone_Payment_Flow.pdf`

---

# Lab 2 — Component Modelling & Architecture

### Tasks Completed

- Selected **Layered Architecture** for the system.
- Created a UML component diagram.
- Identified the main software components:
  - Client Portal
  - Digital Artist Portal
  - Commission Management Service
  - Payment Service
  - Watermark Service
  - File Storage & Download Service
  - Database
- Added the required interfaces and interactions between components.
- Documented the architecture choice.
- Explained the benefits of separation of concerns and modularity.
- Explained the security advantage of dedicated services and controlled final-file access.
- Explained the performance benefit of separating watermarking and file-delivery responsibilities.

### Lab 2 Deliverables

- `Component_Diagram.pdf`
- `Architecture_Justification.pdf`

---

# Lab 3 — Jira Project Planning & Tracking

### Tasks Completed

Jira was used to organize the project work into user stories, use cases, backlog items, and a sprint.

## Jira Work Items

A total of **17 work items** were created.

### 7 User Stories

| Issue | User Story |
|---|---|
| KAN-1 | Client submits a creative brief |
| KAN-2 | Artist uploads a WIP draft |
| KAN-3 | System applies a watermark to WIP drafts |
| KAN-4 | Client reviews the WIP draft |
| KAN-5 | Client requests a revision |
| KAN-6 | Client makes a milestone payment |
| KAN-7 | Client downloads the final artwork |

### 10 Use Cases

| Issue | Use Case |
|---|---|
| KAN-8 | Use Case - Submit Creative Brief |
| KAN-9 | Use Case - View Creative Brief |
| KAN-10 | Use Case - Upload WIP Draft |
| KAN-11 | Use Case - Apply Watermark |
| KAN-12 | Use Case - Review WIP Draft |
| KAN-13 | Use Case - Request Revision |
| KAN-14 | Use Case - Make Milestone Payment |
| KAN-15 | Use Case - Process Payment |
| KAN-16 | Use Case - Download Final Artwork |
| KAN-17 | Use Case - Deliver Final Artwork |

## Backlog & Sprint

- Enabled the **Jira Backlog** for the project.
- Enabled **Sprints**.
- Created **Digital Art Commission Sprint**.
- Planned the main 7 user stories into the sprint.
- Set a sprint goal:
  **Implement the core digital art commission workflow**
- Started the sprint successfully.
- The 7 sprint items are currently in the **To Do** status.
- The 10 detailed use-case work items remain available in the backlog.

### Lab 3 Evidence

- Jira List view showing the user stories.
- Jira List view showing the use cases.
- Jira active sprint board showing the sprint and its work items.
- `Lab_3_Jira_Complete_Report.pdf`

---

# Project Files

The repository contains the documents created for the software engineering labs.

```text
Digital-Art-Commission-Watermarking-Portal/
├── README.md
├── Requirements_Table.xlsx
├── Use_Case_Diagram.pdf
├── Make_Milestone_Payment_Flow.pdf
├── Component_Diagram.pdf
├── Architecture_Justification.pdf
└── Lab_3_Jira_Complete_Report.pdf
```

---

## Tools Used

- **Jira** — project planning, user stories, use cases, backlog and sprint tracking
- **StarUML / diagramming tools** — UML modelling
- **Microsoft Excel** — requirements table
- **PDF** — lab documentation and evidence

---

## Project Status

| Lab | Status |
|---|---|
| Lab 1 — Requirements & Use Cases | Completed |
| Lab 2 — Component & Architecture Modelling | Completed |
| Lab 3 — Jira Planning & Tracking | Completed |

**Current project status: All three lab activities completed.**
