AICTE CaseSync

AI-Powered Grievance & Case Coordination Platform for AICTE

AICTE CaseSync is a professional frontend prototype designed to demonstrate a centralized system for receiving, classifying, prioritizing, routing, monitoring, and resolving institution-related complaints and administrative cases across AICTE Bureaus/Cells.

The prototype focuses on improving case visibility, reducing manual coordination, enabling structured case handling, and providing role-based workflows for institutions, Bureau/Cell officers, and AICTE administrators.

---

🎯 Problem Statement

Handling institution-related complaints and administrative cases across multiple Bureaus and Cells can involve:

- Manual case classification and routing
- Difficulty identifying the appropriate Bureau/Cell
- Delays in case assignment and resolution
- Limited visibility into case status and SLA deadlines
- Difficulty tracking related or similar cases
- Lack of a centralized view for administrators and officers

AICTE CaseSync demonstrates how these processes can be brought together into a single centralized digital platform.

---

💡 Proposed Solution

AICTE CaseSync provides a centralized case management interface where complaints can be:

Submitted → Analyzed → Classified → Prioritized → Routed → Assigned → Monitored → Resolved

The prototype includes simulated AI-assisted processing to demonstrate how submitted complaints could be automatically analyzed and categorized.

---

✨ Key Features

🤖 AI-Assisted Case Analysis

The prototype simulates AI-based processing to determine:

- Complaint category
- Sub-category
- Priority
- Appropriate Bureau/Cell
- Confidence score
- Case summary
- Similar/related cases

The AI processing is currently implemented as a frontend simulation using local rules, allowing it to be replaced with a real AI service in a future implementation.

---

📂 Centralized Case Management

Users can view and manage cases through a structured case-management interface.

The system demonstrates:

- Case IDs
- Complaint titles
- Categories
- Priority levels
- Case status
- Assigned Bureau/Cell
- SLA information
- Related cases
- Case details

---

⏱️ SLA Monitoring

The prototype includes SLA tracking to help identify cases requiring attention.

SLA Levels

SLA State| Condition
Healthy| Less than 50% of allotted time used
Approaching Deadline| 50% or more
At Risk| 80% or more
Overdue| Past the deadline

The prototype uses different SLA durations depending on case priority.

---

👥 Role-Based Interface

The application demonstrates three different user roles:

Institution / User

Institutions can:

- View their dashboard
- Submit complaints
- Track submitted cases
- View notifications
- View their profile

Bureau / Cell Officer

Officers can:

- View assigned cases
- Review case details
- Monitor SLA status
- Update case status
- Coordinate case resolution

AICTE Administrator

Administrators can:

- Monitor cases across the platform
- View case information
- Track case progress
- Manage and monitor overall case activity

---

🧭 Application Workflow

Institution / User
        │
        ▼
Submit Complaint
        │
        ▼
AI-Assisted Analysis
        │
        ├── Category
        ├── Sub-category
        ├── Priority
        ├── Bureau / Cell
        └── Confidence
        │
        ▼
Case Creation
        │
        ▼
Bureau / Cell Officer
        │
        ▼
Case Review & Processing
        │
        ▼
Status & SLA Monitoring
        │
        ▼
Resolution
        │
        ▼
Case Closed

---

🖥️ Prototype Screens

The prototype demonstrates interfaces for:

- Sign In
- Institution Dashboard
- Bureau / Cell Dashboard
- AICTE Administrator Dashboard
- Submit Complaint
- Case List
- Case Details
- AI Case Analysis
- Notifications
- Profile
- Navigation Menu
- SLA Monitoring

---

🛠️ Technology Stack

Technology| Purpose
React| Frontend application
TypeScript| Type-safe development
Vite| Development and build environment
Tailwind CSS| UI styling
Lucide React| Interface icons
Browser LocalStorage| Local prototype data persistence

---

🔐 Data & Prototype Architecture

This repository contains a frontend prototype.

The current version does not connect to a production AI model, government database, authentication server, or external case-management backend.

Case information and prototype state are handled locally in the browser.

This architecture allows the prototype to demonstrate the intended user experience while keeping the implementation lightweight and suitable for further development.

---

🚀 Running the Project Locally

Prerequisites

- Node.js
- npm
- VS Code or another code editor

Installation

Clone or download the repository and open the project folder.

Install dependencies:

npm install

Start the development server:

npm run dev

The application will then be available through the local development URL displayed by Vite.

---

🔮 Future Scope

The prototype can be extended into a production-ready platform by integrating:

- Real AI/ML-based complaint classification
- Secure user authentication
- AICTE institutional databases
- Government identity and authorization systems
- Centralized backend case management
- Real-time notifications
- Email/SMS notifications
- Advanced analytics and reporting
- Document and evidence management
- Audit trails
- Production-grade SLA monitoring
- Role-based access control
- Secure cloud deployment

---

🎯 Project Objective

AICTE CaseSync aims to demonstrate how an intelligent centralized case-management platform can help AICTE improve:

Visibility • Classification • Routing • Coordination • SLA Monitoring • Resolution

The prototype provides a foundation that can be further developed into a complete production system with real AI services, backend infrastructure, authentication, and government data integrations.

---

📌 Project Status

Current Status: Frontend Prototype

The current implementation focuses on demonstrating the complete user interface, role-based workflows, case-management experience, simulated AI processing, and SLA monitoring required for the proposed solution.

---

👨‍💻 Repository

Project: AICTE CaseSync
Type: AICTE Case Management Frontend Prototype
Built with: React + TypeScript + Vite + Tailwind CSS

---

Built as a Smart India Hackathon (SIH) 2026 Prototype

AICTE CaseSync is developed as a prototype to demonstrate a centralized and intelligent approach to managing institution-related complaint cases across AICTE Bureaus/Cells.
