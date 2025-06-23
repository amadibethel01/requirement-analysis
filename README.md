# Requirement Analysis in Software Development

## Introduction

This repository serves as a foundational resource for understanding and applying Requirement Analysis within the Software Development Life Cycle (SDLC). It documents the process of gathering, analyzing, and structuring requirements for a real-world project — a Booking Management System.

The goal of this project is to simulate a professional environment where clear, structured, and scalable requirements lay the groundwork for successful software development. Through diagrams, documentation, and structured tasks, this project demonstrates how to bridge business needs with technical solutions.

---

## What is Requirement Analysis?

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) that involves the process of identifying, gathering, analyzing, and validating the needs and expectations of stakeholders for a proposed software system.

It serves as the foundation for all subsequent stages of development — from system design to testing — ensuring that the final product meets user expectations, business objectives, and technical constraints.

### 🔍 Key Objectives of Requirement Analysis:
- To understand the **problem domain** and the scope of the system to be built.
- To define **functional requirements** (what the system should do).
- To identify **non-functional requirements** (how the system should perform).
- To document all requirements in a clear, unambiguous, and structured format.
- To serve as a basis for **system validation** and **project planning**.

### 📌 Importance in the SDLC:
- **Minimizes misunderstandings** between developers and stakeholders.
- **Reduces costly rework** by identifying inconsistencies early.
- **Aligns the development process** with business and user needs.
- **Improves project estimation** (cost, time, and resources).
- **Ensures traceability** from requirements to implementation and testing.

Requirement Analysis is not a one-time activity; it is an **iterative and collaborative process** involving continuous communication between business analysts, developers, testers, stakeholders, and end-users.

In summary, Requirement Analysis lays the **blueprint** for building reliable, user-centered, and goal-driven software systems.

---

## Why is Requirement Analysis Important?

Requirement Analysis is one of the most essential activities in the Software Development Life Cycle (SDLC). It acts as the foundation for the entire project and significantly influences the success or failure of the final product.

Below are three key reasons why Requirement Analysis is critical:

### 1. ✅ Prevents Miscommunication Between Stakeholders
Without clear requirements, developers may make assumptions that don’t align with user expectations. Requirement Analysis bridges the communication gap between clients, end-users, and the technical team by documenting agreed-upon needs in a structured format.

### 2. ✅ Reduces Development Costs and Rework
Identifying requirements early ensures potential issues, inconsistencies, and gaps are discovered before coding begins. Fixing problems at the design stage is far more cost-effective than during implementation or post-deployment.

### 3. ✅ Ensures Project Alignment with Business Goals
Requirement Analysis aligns technical outcomes with business objectives by translating goals into measurable software features. This ensures the final system provides real value to the business and its users.

Additional benefits include improved planning, accurate budgeting, better testing, and enhanced product quality — all of which stem from strong requirement analysis practices.
---

## Key Activities in Requirement Analysis

Requirement Analysis consists of several key activities that help ensure the system meets user needs and aligns with business goals. These activities form the backbone of understanding and shaping what the system should do.

### 🔑 The five key activities are:

- **1. Requirement Gathering**
  - Involves collecting information from stakeholders about what they expect from the system.
  - Techniques include interviews, surveys, document analysis, brainstorming sessions, and observation.

- **2. Requirement Elicitation**
  - Focuses on drawing out hidden, implicit, or unspoken requirements.
  - Encourages stakeholders to clarify and articulate their needs.
  - Helps identify both functional and non-functional requirements.

- **3. Requirement Documentation**
  - Converts gathered and elicited requirements into well-structured, formal documents.
  - These include Software Requirements Specifications (SRS), user stories, use cases, and requirement traceability matrices.

- **4. Requirement Analysis and Modeling**
  - Analyzes and organizes requirements into logical groups and models.
  - Involves prioritizing, categorizing, checking for completeness, consistency, feasibility, and eliminating conflicts.
  - May include creating use case diagrams, process flows, and data models to represent the requirements visually.

- **5. Requirement Validation**
  - Ensures that documented requirements accurately reflect stakeholder needs.
  - Activities include reviews, walkthroughs, and inspections with stakeholders.
  - Helps identify ambiguities, redundancies, and inconsistencies before development begins.

Each of these activities contributes to building a reliable foundation for system design, development, and successful delivery.
---

## Types of Requirements

Requirements in software development are generally categorized into two main types: **Functional Requirements** and **Non-functional Requirements**. Both are essential for building a complete and effective software system.

### 🔧 Functional Requirements

Functional requirements define **what** the system should do. These are the features and capabilities that the system must support to satisfy user needs and business processes.

#### 📝 Examples for Booking Management System:
- Users shall be able to **create new bookings** for available rooms or services.
- The system shall allow users to **view, update, or cancel** existing bookings.
- The system shall enable administrators to **manage room inventory** and availability.
- Users shall receive **email confirmations** after completing a booking.
- The system shall allow **staff members** to check the **daily schedule** of bookings.

---

### ⚙️ Non-functional Requirements

Non-functional requirements describe **how** the system performs its functions. They define the quality attributes, performance benchmarks, and technical standards the system must meet.

#### 📝 Examples for Booking Management System:
- The system should be available **24/7** with **99.9% uptime**.
- Users should be able to complete a booking within **3 seconds** under normal load.
- The application must **encrypt all user data** using industry-standard security protocols (e.g., HTTPS, SSL/TLS).
- The platform should support up to **10,000 concurrent users** without performance degradation.
- The UI should be **responsive** and accessible on desktop, tablet, and mobile devices.

Understanding both types ensures that the booking system is **functionally complete** and **operationally reliable** across real-world scenarios.
---

## Use Case Diagrams

Use Case Diagrams are a type of UML (Unified Modeling Language) diagram used to visually represent the functional requirements of a system. They illustrate the interactions between **actors** (users or systems) and the **use cases** (system functionalities) they are involved in.

### 📌 Benefits of Use Case Diagrams:
- Help stakeholders and developers understand system functionality at a high level.
- Provide clarity on what each type of user can do in the system.
- Serve as a communication tool during requirement analysis and validation.
- Assist in identifying scope, responsibilities, and access control.

Below is the use case diagram for the **Booking Management System**, showing how different actors interact with the core functionalities of the system:

![Booking Management System Use Case Diagram](./alx-booking-uc.png)
---

## Acceptance Criteria

Acceptance Criteria are predefined conditions that a software product must satisfy to be accepted by the user, customer, or other stakeholders. They are written from the perspective of the end user and provide a clear, testable definition of when a requirement is complete.

### ✅ Importance of Acceptance Criteria in Requirement Analysis:
- Ensures a **shared understanding** between stakeholders and developers.
- Defines **boundaries and expectations** for system functionality.
- Helps testers create **relevant test cases** based on defined behavior.
- Reduces ambiguity by offering **clear success conditions**.
- Supports **agile development** through the definition of “done” for features.

---

### 📦 Example: Acceptance Criteria for "Checkout Feature" in a Booking Management System

**Feature:** Booking Checkout Process

**Acceptance Criteria:**
- ✅ Given the user has selected a room and filled in personal details,  
  When they click “Proceed to Checkout”,  
  Then the system should display a summary of the booking and total cost.

- ✅ Given the user is on the checkout page,  
  When they click “Confirm Booking”,  
  Then the system should process the booking and display a success confirmation with a unique booking ID.

- ✅ Given the booking is successful,  
  When the confirmation screen appears,  
  Then the system should trigger an email notification with the booking details.

These criteria ensure that the checkout feature is functionally complete and delivers the expected user experience.
