# Requirement Analysis in Software Development

## 1. Purpose of This Repository

This repository has been created to demonstrate and document the process of conducting Requirement Analysis for a software system.
It will include:

- Detailed requirement documentation.

- Use case diagrams and visual models.

- Acceptance criteria and validation steps.

- Step-by-step analysis aligned with SDLC best practices.

## What is Requirement Analysis?

Requirement Analysis is the process of collecting, examining, and documenting the needs and expectations of stakeholders for a software system. It is an early and essential phase of the Software Development Life Cycle (SDLC) that transforms vague ideas and stakeholder requests into clear, testable, and actionable specifications that guide design, development, and testing.

### Why it matters in SDLC

  Requirement Analysis sits at the beginning of the SDLC and directly affects every subsequent phase (design, implementation, testing, deployment, and maintenance). Good requirement analysis saves time and money by reducing rework, preventing scope creep, and improving stakeholder satisfaction. Conversely, poor or missing requirements are the most common sources of failed projects, late deliveries, and broken features.

## 2. Why is Requirement Analysis Important?

Requirement Analysis is one of the most crucial phases in the Software Development Life Cycle (SDLC) because it lays the foundation for every subsequent stage — from design and development to testing and deployment. Without a clear understanding of what needs to be built, projects can easily fail, exceed budgets, or fail to meet user expectations.

<b>Below are key reasons why Requirement Analysis is vital in software development:</b>

### 1. Establishes a Clear Project Scope

Requirement Analysis helps define what the system will and will not do. By identifying and documenting stakeholder needs early, it prevents misunderstandings, scope creep, and wasted effort.

  - Ensures all parties — clients, developers, and testers — share the same vision.
  
  - Prevents costly changes during later phases.
  
  - Sets measurable boundaries and goals for the project.

### 2. Improves Design and Development Efficiency

A well-defined set of requirements gives developers a clear roadmap to follow, reducing guesswork and rework.

  - Developers can focus on how to implement solutions rather than figuring out what needs to be built.
  
  - Leads to better system architecture and smoother integration between components.
  
  - Reduces time wasted on unnecessary features or incorrect assumptions.

### 4. Minimizes Project Costs and Risks

Detecting and fixing problems early in the requirement phase is far less costly than during later stages like development or testing.

  - Early identification of conflicts, ambiguities, or technical challenges saves time and money.
  
  - Helps predict potential risks and plan effective mitigation strategies.
  
  - Improves overall resource management and project predictability.


## 3. Key Activities in Requirement Analysis.

Requirement Analysis involves a series of structured activities aimed at understanding, documenting, and validating what a software system should achieve. These activities ensure that all stakeholder expectations are captured accurately and transformed into actionable requirements.

Below are the five key activities involved in the Requirement Analysis process:

### 1. Requirement Gathering

This is the first and most critical step in Requirement Analysis. It focuses on collecting information about user needs, business goals, and system expectations.

Key tasks include:

- Conducting interviews with stakeholders to understand their objectives and challenges.

- Distributing surveys or questionnaires to gather input from a broader audience.

- Observing how users currently perform their tasks to identify pain points.

- Reviewing existing systems, reports, and documentation to identify gaps and improvement areas.

### 2. Requirement Elicitation

Once information is gathered, the next step is to refine and expand on those insights. Requirement Elicitation focuses on extracting clear, specific, and measurable requirements from stakeholders.

Key tasks include:

- Organizing brainstorming sessions to generate ideas and solutions.

- Conducting focus group discussions to validate and refine needs.

- Creating prototypes or wireframes to help stakeholders visualize features.

- Identifying constraints and assumptions that may affect system design.

### 3. Requirement Documentation

After eliciting requirements, they must be documented in a structured and accessible format. This ensures that all team members and stakeholders have a shared understanding of what needs to be built.

Key tasks include:

- Creating a Software Requirement Specification (SRS) document that details all functional and non-functional requirements.

- Writing user stories to describe system interactions from an end-user perspective.

- Developing use case diagrams to visualize user interactions with the system.

- Ensuring all requirements are clear, complete, and traceable.

### 4. Requirement Analysis and Modeling

This stage focuses on analyzing and prioritizing the collected requirements and representing them through models or diagrams for better understanding and validation.

Key tasks include:

- Performing feasibility analysis to assess technical, financial, and time constraints.

- Conducting requirement prioritization to focus on the most critical features first.

- Creating data flow diagrams (DFD), entity-relationship diagrams (ERD), and other visual models.

- Identifying dependencies, potential conflicts, and areas that need further clarification.

### 5. Requirement Validation

In this final activity, all documented requirements are reviewed, verified, and approved to ensure they align with user expectations and project objectives.

Key tasks include:

- Conducting review meetings with stakeholders for feedback and confirmation.

- Establishing acceptance criteria to define when a requirement is considered complete.

- Performing traceability analysis to ensure all requirements are covered in design and testing.

- Getting formal sign-off from stakeholders to finalize the requirements before development begins.

## 4. Types of Requirements

In software development, requirements define what the system should do and how it should perform. They are generally categorized into two main types: Functional Requirements and Non-functional Requirements. Both are essential to ensure that the system operates effectively and meets user expectations.

### Functional Requirements
Functional requirements describe the specific behaviors, actions, and features the system must perform. They define what the system should do to meet the needs of users and stakeholders.

Purpose:
These requirements directly relate to user interactions and system operations — they specify how users will use the system.

Examples for the Booking Management System:

- User Registration & Login:

  Users must be able to create an account by providing personal details such as name, email, and password.
  
  Registered users should be able to log in securely using their credentials.

- Property Search:

  Users should be able to search for properties based on filters like location, price range, and availability dates.
  
  The system should display a list of matching properties with key details and images.

- Booking Management:

  Users must be able to book properties by selecting available dates and confirming reservations.
  
  The system should generate booking confirmations and update property availability automatically.

- Payment Processing:

  Users should be able to make payments through integrated payment gateways (e.g., PayPal, credit card).
  
  The system should display payment status (successful, pending, or failed) in the booking history.

- Admin Management:

  Admins can view, edit, or remove property listings.
  
  Admins should be able to manage user accounts and view reports of bookings and payments.

###  Non-functional Requirements
Non-functional requirements describe how the system should perform rather than what it should do. They define system qualities such as performance, security, usability, scalability, and reliability.

Purpose:
These requirements ensure that the system operates efficiently, securely, and reliably under expected conditions.

Examples for the Booking Management System:

1- Performance:

  - The system should load all main pages (Home, Search, Booking) within 2 seconds.
  
  - It should support at least 1000 concurrent users without performance degradation.

2- Security:

  - All sensitive user data (e.g., passwords, payment information) must be encrypted using SSL/TLS protocols.
  
  - The system should implement two-factor authentication (2FA) for login and account verification.

3- Scalability:

  - The application should be scalable to support future increases in traffic and property listings.
  
  - It should support horizontal scaling by adding more servers when needed.

4- Usability:

  - The interface should be intuitive, ensuring users can complete bookings within 3 clicks from the search page.
  
  - The design should follow consistent color schemes, typography, and accessibility standards (WCAG compliance).

5- Reliability & Availability:

  - The system should maintain an uptime of 99.9%, ensuring high availability for users worldwide.
  
  - In the event of a system failure, data recovery should occur within 5 minutes to minimize downtime.


## 5. Use Case Diagrams

A Use Case Diagram is a visual representation that shows how users (actors) interact with a system to achieve specific goals (use cases). It is an essential part of Requirement Analysis because it helps identify, clarify, and organize system functionalities from the user’s perspective.

Benefits of Use Case Diagrams

1. Clarity in Requirements:
  Helps stakeholders easily understand the system’s scope and functionality.

2. Improved Communication:
  Acts as a bridge between technical and non-technical stakeholders, ensuring everyone understands system interactions.

3. Simplified Design Planning:
  Provides a foundation for defining user stories, workflows, and further design documentation.

4. Traceability:
  Each use case can be traced to a specific requirement, ensuring complete coverage during development and testing.

5 Error Reduction:
  Helps identify missing requirements or redundant features early in the project.

#### Actors in the Booking Management System

- Guest (Unregistered User): Can browse and search available properties.

- Registered User: Can search, book, and manage reservations.

- Admin: Manages property listings, users, and booking data.

#### Use Cases
Actor	Use Cases
- Guest	View Property Listings, Search for Properties
  
- Registered User	Register/Login, Search Properties, Book Property, Make Payment, View Booking History, Cancel Booking
  
- Admin	Manage Property Listings, Manage Users, View Reports
