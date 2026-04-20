# DWARKESH AUTO SERVICE

## Project Report

### Submitted To
Your College Name

### Submitted By
Your Name  
Enrollment Number  
Semester / Year  
Department Name

### Guide
Faculty Guide Name

### Academic Year
2025-2026

---

## Certificate

This is to certify that the project titled **"Dwarkesh Auto Service"** is a bonafide work carried out by the student in partial fulfillment of the requirements for the academic program. The work has been completed under guidance and is suitable for submission to the college.

---

## Declaration

I hereby declare that the project report entitled **"Dwarkesh Auto Service"** is my original work and has not been submitted to any other university or institution for the award of any degree, diploma, or certificate.

---

## Acknowledgement

I would like to express my sincere gratitude to my project guide, faculty members, friends, and family members for their valuable support and guidance during the development of this project. Their suggestions and encouragement helped me complete this work successfully.

---

## Abstract

Dwarkesh Auto Service is a web-based automobile service booking and management system developed to simplify the process of booking vehicle service appointments, selecting spare parts, managing service records, generating bills, and monitoring booking status. The project aims to reduce manual work and provide a structured digital platform for customers and service administrators.

The system allows a customer to choose a car brand and model, enter service details, select spare parts, and submit a booking request. The administrator can review the request, update the booking status, manage payment details, and generate bill values such as labor charges, tax, discount, and final amount. The project also includes a modern user interface and role-based pages for users and administrators.

This project is useful for small and medium automobile service centers that want to digitize their workflow. It improves record keeping, increases transparency in billing, reduces paperwork, and saves time for both customers and staff.

---

## Index

1. Introduction
2. Problem Statement
3. Objectives
4. Scope of Project
5. Existing System
6. Proposed System
7. Technology Stack
8. System Requirements
9. Feasibility Study
10. System Analysis
11. System Design
12. Modules of the System
13. Database Design
14. API Design
15. Implementation Details
16. Testing
17. Advantages
18. Limitations
19. Future Scope
20. Conclusion
21. References

---

## 1. Introduction

The automobile service industry is growing rapidly, and customer expectations for convenient service booking and billing are increasing. Many local service centers still rely on manual registers, handwritten bills, and phone-based coordination, which creates problems such as data loss, confusion in scheduling, improper record maintenance, and billing errors.

The Dwarkesh Auto Service project is developed to provide a simple but effective digital solution for service center operations. This system provides an online interface through which service requests can be recorded, tracked, and managed. The project focuses on practical functionality such as booking management, customer details, spare parts selection, service cost calculation, and bill generation.

The system has been designed as a full-stack web application. The frontend provides an interactive and user-friendly interface, while the backend handles business logic, validation, database storage, and API communication. This project demonstrates how real-world service center operations can be transformed into a structured digital workflow.

---

## 2. Problem Statement

Traditional service centers face multiple operational problems:

- Customer booking details are often maintained manually.
- Spare parts and pricing records are difficult to track.
- Service status updates are not properly communicated.
- Billing is time-consuming and may contain mistakes.
- Historical records are difficult to retrieve.
- Manual methods increase paperwork and reduce efficiency.

Because of these issues, both customers and administrators face inconvenience. A centralized digital platform is required to solve these operational challenges.

---

## 3. Objectives

The major objectives of this project are:

- To provide an online booking facility for vehicle service.
- To store customer and vehicle details in an organized manner.
- To allow spare parts selection with amount calculation.
- To generate and manage billing details.
- To provide separate views for users and admin.
- To reduce manual effort in service center operations.
- To improve transparency in payment and spare parts management.
- To maintain records for future reference.

---

## 4. Scope of Project

The scope of this project includes:

- Online service booking for different car brands and models.
- Spare parts selection and total amount estimation.
- Admin panel for booking review and status management.
- Bill generation using labor, tax, discount, and final amount.
- Payment status update and transaction record handling.
- Customer and admin dashboards for viewing records.

The project is suitable for educational demonstration and can also be adapted for small service centers with additional enhancements.

---

## 5. Existing System

In the existing manual system:

- Bookings are taken through phone calls or paper forms.
- Customer records are stored in notebooks or loose files.
- Spare part pricing is checked manually.
- Bills are created by hand or in simple calculators.
- Service progress tracking is not systematic.

Disadvantages of the existing system:

- Time consuming
- Error-prone
- Difficult to maintain
- No centralized records
- Poor transparency
- Weak reporting capability

---

## 6. Proposed System

The proposed system is a web-based automobile service management platform. It allows service booking and billing in a single digital workflow. The proposed system improves efficiency, minimizes paper usage, and ensures better storage and retrieval of data.

Main features:

- Home page with premium project presentation
- Car details and service booking form
- Side-by-side spare parts and booking workflow
- HD car image support
- Admin dashboard for operational control
- Payment and bill management
- Booking status update
- User dashboard for tracking entries

---

## 7. Technology Stack

### Frontend

- React.js
- React Router
- CSS

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Other Tools

- REST API
- Local Storage
- VS Code
- PowerShell / Terminal

---

## 8. System Requirements

### Hardware Requirements

- Processor: Intel i3 or above
- RAM: 4 GB minimum
- Hard Disk: 20 GB free space

### Software Requirements

- Operating System: Windows 10 or above
- Node.js
- MongoDB
- Code Editor: VS Code
- Browser: Chrome / Edge / Firefox

---

## 9. Feasibility Study

### Technical Feasibility

The project is technically feasible because it uses widely available web technologies such as React, Node.js, Express, and MongoDB.

### Economic Feasibility

The project is cost-effective because it can be developed using open-source technologies without expensive software licensing.

### Operational Feasibility

The system is easy to use for both customer-facing and admin-facing operations, making it operationally feasible.

---

## 10. System Analysis

The system accepts booking information from the customer and stores it in the database through backend APIs. The admin can later access the same data and update payment, bill, and booking status. The customer can also track service-related information through the dashboard.

Input data:

- Customer name
- Mobile number
- Car brand
- Car model
- Service mode
- Pickup address
- Preferred date
- Payment method
- Spare parts

Output data:

- Booking confirmation
- Service status
- Payment status
- Bill amount
- Spare parts breakdown

---

## 11. System Design

### High Level Design

The project is divided into two main layers:

- Frontend layer
- Backend layer

The frontend communicates with the backend through REST APIs. The backend interacts with MongoDB for storing and retrieving data.

### Workflow

1. Customer opens the application.
2. Customer selects car details and service information.
3. Customer selects spare parts.
4. Booking is submitted.
5. Admin reviews booking.
6. Admin updates payment and generates bill.
7. User can see updated records.

---

## 12. Modules of the System

### 12.1 Home Module

The home module provides a premium landing interface with project branding.

### 12.2 Car Details Module

This module collects customer information, vehicle information, and service-related details.

### 12.3 Spare Parts Module

This module allows the selection of spare parts, quantity handling, custom spare parts, and total calculation.

### 12.4 Admin Module

This module allows booking management, bill update, payment status update, and notification handling.

### 12.5 User Module

This module provides booking record visibility to the user.

### 12.6 Billing Module

This module calculates and stores labor amount, tax amount, discount amount, and final bill amount.

---

## 13. Database Design

The project uses MongoDB for storing booking-related records.

### Main Collection

`bookings`

### Important Fields

- customerName
- customerPhone
- carBrand
- carModel
- serviceMode
- pickupAddress
- preferredDate
- priority
- paymentMethod
- paymentAmount
- paymentStatus
- paymentTransactionId
- spareParts
- sparePartsTotal
- billLaborAmount
- billTaxAmount
- billDiscountAmount
- billFinalAmount
- billGeneratedAt
- status

---

## 14. API Design

Important API endpoints used in the project:

- `POST /api/book`
- `GET /api/bookings`
- `PATCH /api/bookings/:id/status`
- `PATCH /api/bookings/:id/payment`
- `POST /api/bookings/:id/notify`

These APIs connect frontend actions with backend logic and database storage.

---

## 15. Implementation Details

The frontend has been developed using React components and route-based page navigation. The backend is implemented using Express routes, middleware validation, and controller functions. MongoDB stores the records using Mongoose models.

Some important implementation highlights:

- Car images are loaded dynamically.
- Spare parts are grouped and filtered by category.
- Booking and spare parts are placed side-by-side to reduce scrolling.
- Bill values are stored inside booking records.
- Admin can manage operational workflow.

---

## 16. Testing

The system can be tested through the following methods:

- Form validation testing
- API endpoint testing
- Database record verification
- UI testing for responsiveness
- Admin workflow testing
- Bill calculation testing
- Payment update testing

Test cases include:

- Valid booking submission
- Invalid mobile number
- Empty required fields
- Spare part quantity handling
- Payment status update
- Bill generation

---

## 17. Advantages

- Reduces manual paperwork
- Improves service center efficiency
- Stores data in a structured way
- Simplifies billing
- Supports admin monitoring
- Enhances customer convenience
- Easy to extend in future

---

## 18. Limitations

- Currently designed for a limited project scope
- No full authentication system yet
- Depends on internet/local server availability
- PDF export and advanced reports are not yet included

---

## 19. Future Scope

This project can be enhanced in future by adding:

- Authentication and authorization
- Online payment gateway
- Invoice PDF generation
- Email/SMS/WhatsApp notification system
- Service history reports
- Analytics dashboard
- Stock management for spare parts
- Multi-user and branch support

---

## 20. Conclusion

The Dwarkesh Auto Service project successfully demonstrates a practical web-based solution for digital automobile service center management. The project provides booking, spare parts handling, billing, and admin control in one integrated system. It helps in reducing manual work and increasing transparency in service operations.

This project is suitable for academic submission and also has real-world relevance. With additional features, it can be expanded into a full commercial automobile service management platform.

---

## 21. References

- React Documentation
- Node.js Documentation
- Express.js Documentation
- MongoDB Documentation
- Mongoose Documentation
- MDN Web Docs

---

## Appendix

### Suggested Screenshot List

- Home page
- Car details and spare parts page
- User dashboard
- Admin dashboard
- Bill update section
- Booking table

### Note

This file is the initial report draft. It can now be expanded chapter by chapter into a complete 40-page college report with detailed explanation, screenshots, diagrams, and formatting.
