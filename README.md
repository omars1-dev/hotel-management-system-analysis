🏨 Al Anwar Hotel Management System – System Analysis & Design

📌 Overview

This project presents a comprehensive System Analysis and Design for Al Anwar Hotel, developed based on real-world observation, interviews, and operational analysis.

The goal is to transform a legacy, inefficient system into a modern, secure, and scalable hotel management solution.

---

🎯 Objectives

- Improve system performance (response time < 3 seconds)
- Enhance security using HTTPS and industry standards
- Enable secure electronic payments
- Provide real-time room availability
- Support multi-room booking
- Generate accurate reports for decision-making

---

🔍 Current System Issues

The analysis identified 15 major problems, including:

- Slow system performance
- Complex and non-intuitive user interface
- No electronic payment support
- Lack of real-time room status
- No backup system
- Weak security (HTTP instead of HTTPS)
- No integration with external systems
- Outdated technology (ASP)

---

🧠 Requirements Analysis

📊 Summary

- Problems Identified: 15
- Requirements Identified: 16
- Functional Requirements: 15
- Non-Functional Requirements: 10

---

⚙️ Functional Requirements

- Guest management
- Reservation management
- Room management
- Advanced search
- Employee management
- Reporting system
- File attachments
- Secure login system
- Smart notifications
- Room status tracking
- Multi-room booking
- Electronic payment system
- Government system integration
- Customer notifications
- Invoice management

---

🔒 Non-Functional Requirements

- Performance: < 3 seconds response time
- Security: HTTPS, PCI DSS compliance
- Availability: 24/7 uptime
- Reliability: Daily backup
- Scalability: Expandable architecture
- Usability: Simple and intuitive UI
- Compatibility: Cross-browser support
- Maintainability: Easy to update and maintain

---

👥 System Roles

🧑‍💼 Reception Staff

- Register guests
- Create reservations
- Receive payments
- Search guest data
- View room status

🧑‍💻 Hotel Manager

- Manage employees
- Manage rooms
- View reports
- Control system operations

---

🗺️ System Diagrams

🔷 Context Diagram

Represents the system as a single entity interacting with:

- Guests
- Hotel Management
- Government System
- Payment Gateway

"Context Diagram" (diagrams/context.png)

---

🔶 Data Flow Diagram (Level-0)

Includes:

- 6 Core Processes
- 5 Data Stores
- External Entities
- Full Data Flow Representation

"DFD" (diagrams/dfd.png)

---

🟣 Entity Relationship Diagram (ERD)

Includes 7 main entities:

- Guest
- Reservation
- Room
- Room_Reservation (junction entity)
- Employee
- Transaction
- Payment_Method

🔑 Key Design Decisions

- Resolved Many-to-Many relationship using Room_Reservation
- Separated transactions for financial tracking
- Isolated payment methods for flexibility and scalability
- Applied normalization to reduce redundancy

"ERD" (diagrams/erd.png)

---

🧱 Database Design (Concept)

The system follows a relational database model with:

- Primary Keys (PK)
- Foreign Keys (FK)
- Normalized structure (up to 3NF)

---

🔐 Security Considerations

- Secure communication using HTTPS
- Payment security following PCI DSS
- Role-based access control
- Data protection and validation

---

🚀 Proposed Improvements

- Replace legacy system with modern architecture
- Introduce real-time processing
- Enable secure online payments
- Integrate with government systems
- Implement backup and recovery strategies

---

📁 Project Structure

├── diagrams/
│   ├── context.png
│   ├── dfd.png
│   └── erd.png
│
├── docs/
│   └── system_analysis.pdf
│
├── README.md

---

📎 Documentation

Full system analysis report is available in the "/docs" folder.

---

💡 Conclusion

This project demonstrates a complete system analysis lifecycle, from problem identification to structured system design, providing a solid foundation for future implementation.

---

👨‍💻 Authors

System Analysis Team – 2026
