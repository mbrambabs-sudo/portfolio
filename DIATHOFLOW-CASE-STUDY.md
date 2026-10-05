# DiathoFlow — Real-World Construction Operations Platform

> **Featured professional project:** designed, developed, tested and deployed for **Diatho Consulting**, a Quantity Surveying / construction consulting company. The platform was handed over in 2026 and is currently used in company operations.

## Why this project matters

DiathoFlow demonstrates the point where my construction and Quantity Surveying experience moved beyond spreadsheets and documentation into building a working digital business system.

The goal was to create one operational environment for information that had previously been spread across different processes: projects, tenders, employees, commercial information, meetings, actions, documents, reporting and internal communication.

This was not a classroom prototype. It was developed around real company workflows, tested across interconnected features, deployed and handed over for operational use.

## Business problem

Construction consulting teams work with large amounts of information that must stay connected:

- project status and deadlines
- tender opportunities and pressure points
- employee assignments and workload
- BOQs and commercial workflows
- payment certificates and cost control
- meeting minutes and actions
- documents and reporting
- internal communication

The challenge was not simply to create pages for each function. The challenge was to make the information work together as an operational system.

## What I built

### Operations Command Centre
A central dashboard intended to give management an operational view rather than requiring information to be reconstructed from multiple sources.

### Projects & work management
Project records, stages, checklists, assignments, deadlines and related work information.

### Tender management
Tender tracking and workflow support for opportunities, dates and commercial activity.

### Quantity Surveying / commercial workflows
BOQ import and commercial workflows, cost control and payment-certificate processes.

### Meetings, actions & communication
Minutes of Meetings, action tracking, documents, reporting and internal Chatbox/presence functionality.

### Operational intelligence
The platform is designed to turn operational data into useful signals such as project health, workload visibility, trends, early warnings, explanations and next-best-action recommendations.

## Security-first engineering

Security was treated as a core engineering requirement rather than a final checklist item.

The development process included:

- role-based access boundaries for Admin, Manager, Employee and Viewer users
- authentication and authorization validation
- cross-user access testing
- cross-project / relationship-level authorization testing
- regression testing after security fixes
- end-to-end scenario diagnostics across interconnected workflows
- verification that fixes did not break legitimate workflows

The portfolio intentionally does **not** publish credentials, secrets, private infrastructure details or exploitable implementation specifics.

## Testing & reliability

Because the system contains connected business workflows, a change in one area can affect another. I therefore used a repeatable engineering loop:

**CHANGE → BUILD → TEST → DIAGNOSE → COMMIT → PUSH → VERIFY**

Testing included build verification, end-to-end scenarios, relationship lifecycle diagnostics, regression checks and targeted fixes.

This approach helped me move from “the feature works on my screen” to “the connected workflow has been tested.”

## Technical scope

I worked across:

- frontend application development
- backend/API development
- database and data relationships
- authentication and authorization
- business rules and workflow logic
- diagnostics and regression testing
- deployment and handover
- translating QS/construction requirements into software

The project uses a web application architecture built around React/Vite, Node.js/Express and SQLite.

## Architecture

See [assets/diathoflow-architecture.svg](assets/diathoflow-architecture.svg) for a recruiter-safe high-level architecture and security view.

## Professional value

DiathoFlow demonstrates that I can:

1. understand a construction/QS business problem;
2. translate the workflow into a digital product;
3. build across frontend, backend and data layers;
4. think about access control and security;
5. test interconnected workflows;
6. diagnose regressions;
7. deploy and hand over a working system;
8. communicate the technical work in business terms.

## Important boundary

DiathoFlow is presented as a professional construction-technology project developed for my employer. It should not be represented as a commercial SaaS product sold to external customers, and this portfolio does not disclose confidential company information.

## Career relevance

This project strengthens my profile across **Quantity Surveying, Construction Management, Project Management, Cost & Commercial Management, Construction Technology, automation and AI-enabled operations**.
