# CS-255-12571-M01-System-Analysis-and-Design
System Analysis and Design

# CS-255: DriverPass System Design Project

## Overview

This repository contains my work for **CS-255: System Analysis and Design** at Southern New Hampshire University. The project focuses on designing a proposed DriverPass system for a company that provides online practice exams and in-person driving lessons for customers preparing for their driving tests.

The project demonstrates how I translated a client interview and business requirements into a complete system design. My work combines business analysis, object modeling, process modeling, UML diagrams, technical requirements, and client-focused communication.

## Client and Business Problem

DriverPass needed a centralized system that would allow customers to create accounts, purchase training packages, take online practice tests, and schedule driving lessons. The system also needed to support internal employees who manage customers, instructors, appointments, training packages, reports, and system data.

The proposed system addresses these needs by providing:

- Customer registration and secure account access
- Training package selection and purchase
- Online practice tests and progress tracking
- Driving lesson scheduling, rescheduling, and cancellation
- Customer and appointment management for the secretary
- Instructor availability and lesson-result tracking
- Training package and user administration
- Reports for business operations
- Access to current DMV requirements and training information

## Project Deliverables

The repository includes the major documents and models created for the DriverPass project:

- **Business Requirements Document** — Defines the business background, goals, functional and nonfunctional requirements, system components, assumptions, limitations, and user-interface expectations.
- **Model Application Short Paper** — Explains the recommended blended modeling approach and how object-oriented and process-oriented methods support the DriverPass solution.
- **UML Use Case Diagram** — Identifies the system actors and the interactions they have with the DriverPass system.
- **UML Activity Diagrams** — Illustrate important workflows, including customer registration, package enrollment, practice testing, and lesson scheduling.
- **UML Sequence Diagram** — Shows the interaction between a customer, the system, and supporting services during lesson scheduling.
- **UML Class Diagram** — Represents the core data and relationships needed to support users, customers, instructors, lessons, packages, payments, practice tests, and reports.
- **System Design Document** — Combines the UML models with technical requirements and design explanations for the development team.
- **Client Presentation** — Presents the proposed system and its benefits in clear, nontechnical language for DriverPass stakeholders.
- **Project Gantt Chart** — Organizes the project activities and provides a high-level implementation schedule.

## Modeling Approach

The project lead selected a **blended approach** that combines object modeling and process modeling. Object modeling helped define the system's major entities, responsibilities, and relationships. Process modeling helped explain how information and actions move through the system from the customer's request through system validation, scheduling, payment, and confirmation.

Using both approaches created a more complete design. The models describe not only what information the system must store, but also how users and system components interact to complete important business processes.

## Technical Design Considerations

The proposed DriverPass system is designed as a secure, cloud-accessible application that can be used from a computer or mobile device. Important technical requirements include:

- Role-based access control for customers, secretaries, owners, instructors, and IT personnel
- Secure authentication and password management
- HTTPS/TLS protection for data transmitted between users and the system
- A relational database for users, lessons, packages, payments, tests, and reports
- Validation to prevent double-booked lessons and unauthorized changes
- Audit tracking for important account and scheduling activities
- Integration with payment, email, and DMV information services
- Automated confirmations and notifications for appointments and account activity
- Responsive access for supported desktop and mobile devices

## What I Learned

This project strengthened my ability to move from a loosely defined business problem to a structured technical design. I learned that a strong system design must connect every proposed feature to a documented business need. The UML diagrams also showed me how different views of the same system help different stakeholders understand the solution.

One of the most important lessons was the value of communicating technical ideas at the audience's level. Developers need precise models and technical requirements, while clients need to understand how the system will improve their daily operations. Creating both the system design document and the client presentation helped me practice communicating the same solution to both audiences.

## Tools and Skills Demonstrated

- Requirements analysis
- Functional and nonfunctional requirements
- UML use case, activity, sequence, and class diagrams
- Object-oriented modeling
- Process modeling
- System design documentation
- User and system interaction analysis
- Technical communication
- Client-focused presentation design
- Lucidchart diagramming
- Microsoft Word and PowerPoint documentation

## Portfolio Purpose

This project is included in my computer science portfolio to demonstrate my ability to analyze business needs, create system models, document technical requirements, and explain a proposed solution clearly. It reflects my continued development as a systems analyst and supports my professional goal of connecting business operations, technology, and reliable system design.

## Author

**Cynthia “Cyn” Turner**  
SNHU Computer Science Student  
GitHub: [CynTurn/cs-portfolio](https://github.com/CynTurn/cs-portfolio)
