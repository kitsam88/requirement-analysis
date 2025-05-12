# requirement-analysis
# Requirement Analysis in Software Development.
This repository provides an overview of the Requirement Analysis phase in the software development lifecycle. It covers key concepts, types of requirements, and best practices for gathering, documenting, and analyzing requirements to ensure successful project outcomes.

Contents
Introduction to Requirement Analysis

Functional vs. Non-functional Requirements

Techniques for Requirements Gathering

Common Challenges and Solutions

Purpose
To help developers, analysts, and stakeholders understand the importance of clear and thorough requirement analysis in building effective software solutions.

# What is Requirement Analysis?
📌 What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a new or modified software application. This phase acts as a bridge between the business problems and the technical solutions, helping to ensure that the final product aligns with what users truly need.

It typically involves various stakeholders—including clients, end-users, business analysts, and developers—to ensure that all requirements are well understood and documented before development begins.

📈 Importance in the Software Development Lifecycle (SDLC)
Requirement Analysis is one of the most critical stages in the SDLC, and here's why:

1. ✅ Sets a Clear Project Scope
By defining what the software should do, requirement analysis helps establish clear boundaries and prevents scope creep—the gradual expansion of project scope without proper planning.

2. 🧭 Guides Design and Development
Well-documented requirements serve as a blueprint for software designers and developers. They help in creating system architecture, user interfaces, and workflows that align with user expectations.

3. 🔄 Improves Communication
It ensures that all stakeholders have a shared understanding of the goals and expectations. This minimizes misunderstandings and discrepancies later in the project.

4. 🕵️‍♂️ Reduces Errors and Rework
Identifying requirements early helps catch inconsistencies, incomplete needs, or conflicting expectations before development starts, reducing costly changes and delays later in the lifecycle.

5. 🎯 Enhances Quality and User Satisfaction
Software built upon well-understood and validated requirements is more likely to meet user needs, ensuring higher satisfaction and lower rejection rates after deployment.

🔍 Types of Requirements
Functional Requirements – Describe what the system should do (e.g., login functionality, report generation).

Non-Functional Requirements – Define how the system performs (e.g., performance, security, usability).

Business Requirements – High-level goals from a business perspective.

User Requirements – Specific needs of end-users interacting with the system.

System Requirements – Technical needs for implementation, integration, or hardware.

🔧 Common Techniques Used
Interviews and surveys

Use case modeling

User stories and scenarios

Requirement workshops (e.g., JAD sessions)

Prototyping

Document analysis

🏁 Conclusion
Requirement Analysis is a foundation for the entire SDLC. Skipping or poorly executing this phase can lead to project failure, budget overruns, and unsatisfied users. A thorough analysis ensures the development team builds the right software—not just software that works.

# Why is Requirement Analysis Important?
🔑 Key Reasons Why Requirement Analysis Is Critical in SDLC
📌 Defines Clear Scope
Sets project boundaries and prevents scope creep by outlining exactly what needs to be built.

🛠️ Reduces Errors and Rework
Detects inconsistencies and gaps early, minimizing costly changes during development.

🗣️ Improves Communication
Aligns stakeholders with a shared understanding of objectives and expectations.

# Key Activities in Requirement Analysis.
🔍 1. Requirement Gathering
Involves collecting information from stakeholders, users, and other sources.

Focuses on identifying business needs, user expectations, and system constraints.

Tools/techniques: surveys, interviews, observations, and reviewing existing documentation.

💬 2. Requirement Elicitation
A deeper process than gathering—it involves actively engaging stakeholders to draw out hidden or unspoken needs.

Encourages collaboration through brainstorming, workshops, and prototyping.

Helps reveal conflicting or unclear requirements early in the process.

📝 3. Requirement Documentation
Captures all gathered and elicited requirements in a structured and readable format.

Common formats include Software Requirement Specification (SRS) documents or user stories.

Serves as a reference point throughout the SDLC for all stakeholders.

📊 4. Requirement Analysis and Modeling
Involves evaluating, organizing, and refining requirements for clarity, completeness, and feasibility.

May include creating models like use case diagrams, data flow diagrams, or entity-relationship diagrams.

Helps visualize system behavior and identify potential issues before design begins.

✅ 5. Requirement Validation
Ensures the documented requirements are accurate, complete, and agreed upon by all stakeholders.

Often involves reviews, walkthroughs, and approval sessions.

Helps prevent misunderstandings and ensures the system being built meets actual user needs.


# Types of Requirements.
🔍 1. Requirement Gathering
Functional Requirements

Users can create a booking for rooms, flights, or services.

Admin can approve, modify, or cancel bookings.

System sends confirmation emails after successful booking.

Non-functional Requirements

System should be accessible 24/7.

Response time should be under 2 seconds for booking submissions.

Must support multi-language interfaces.

💬 2. Requirement Elicitation
Functional Requirements

Users can search availability by date, location, and type.

Payment gateway integration for secure online payments.

Display real-time booking status to users.

Non-functional Requirements

System should support 500+ concurrent users without performance degradation.

Must comply with GDPR for data privacy.

Interface must be mobile-friendly and responsive.

📝 3. Requirement Documentation
Functional Requirements

Booking history must be stored and retrievable for each user.

Admin panel must show all current and past bookings with filtering options.

Users can cancel or reschedule a booking within a set time frame.

Non-functional Requirements

System uptime should be 99.9% per month.

Booking data should be backed up daily.

Interface must maintain WCAG 2.1 accessibility standards.

📊 4. Requirement Analysis and Modeling
Functional Requirements

Develop use cases for booking workflow and payment processing.

Model user roles (guest, registered user, admin) and their permissions.

Diagram the booking confirmation logic with optional features like promo codes.

Non-functional Requirements

Determine scalability requirements for future expansion (e.g., adding new service categories).

Define data encryption protocols for storing sensitive user information.

Assess load handling for peak booking seasons.

✅ 5. Requirement Validation
Functional Requirements

Confirm that users can successfully complete a booking from start to finish.

Test if admins can edit or delete bookings with proper audit logs.

Validate the email and notification triggers after each booking action.

Non-functional Requirements

Verify system handles high traffic during load testing.

Ensure response time goals are met under normal and peak conditions.

Review logs to confirm security compliance and data integrity.


# Use Case Diagrams.
🎯 What Are Use Case Diagrams?
Use Case Diagrams are a type of UML (Unified Modeling Language) diagram used to visually represent the interactions between users (actors) and a system.

They show what the system does from a user’s perspective, rather than how it does it.

Each "use case" represents a function or feature that delivers value to an actor (e.g., user, admin, external system).

🧩 Key Elements
Actors – Users or external systems interacting with the system.

Use Cases – Specific actions or services the system performs.

System Boundary – Defines the scope of the system.

Relationships – Associations between actors and use cases (e.g., include, extend).

✅ Benefits of Use Case Diagrams
📚 Simplifies Requirements
Presents complex functionality in an easy-to-understand visual format.

👥 Enhances Communication
Helps bridge the gap between technical teams and stakeholders by focusing on user interactions.

🧭 Clarifies System Scope
Clearly shows what the system is expected to do—and what it’s not.

⚙️ Aids Design and Development
Provides a reference for developers and testers to design system behaviors and test cases.

🧪 Improves Test Planning
Helps identify user scenarios for functional testing and validation.

# Acceptance Criteria.
✅ Importance of Acceptance Criteria in Requirement Analysis
📌 Defines Done
Clearly outlines the conditions under which a feature is considered complete and acceptable to stakeholders.

🔍 Ensures Clarity and Alignment
Prevents misunderstandings by setting shared expectations between business analysts, developers, testers, and stakeholders.

🧪 Drives Testing and Validation
Forms the basis for test cases, ensuring all functionality is verifiable and meets business needs.

🚫 Reduces Rework
Identifies edge cases and failure conditions early, minimizing the chances of rework or rejection.

📋 Enhances Traceability
Provides a direct link between requirements and deliverables, ensuring each feature meets its intended purpose.

🛒 Example: Acceptance Criteria for the "Checkout" Feature in a Booking Management System
The user must be logged in to access the checkout page.

The checkout page must display a summary of selected bookings (e.g., room details, dates, total cost).

Users must be able to enter or select a payment method (e.g., credit card, PayPal).

The system must validate payment details before processing.

A confirmation message and email must be sent upon successful booking.

The system must update availability immediately after checkout.

If the payment fails, the user must receive a clear error message and the booking should not be confirmed.

Checkout must be completed within 2 minutes or the session should time out for security.



