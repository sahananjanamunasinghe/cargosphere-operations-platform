# CargoSphere Operations Platform

## Project Charter

**Document Version:** 1.0  
**Project Status:** Active  
**Project Start Date:** 21 September 2026  
**Prepared By:** Sahan Anjana Munasinghe  
**Project Type:** Professional Portfolio Project  

---

# 1. Project Overview

## 1.1 Project Name

CargoSphere Operations Platform

## 1.2 Client Organization

CargoSphere Logistics (Pvt) Ltd

> Note: CargoSphere Logistics (Pvt) Ltd is a fictional organization created for portfolio and demonstration purposes.

## 1.3 Industry

Air Cargo and Freight Forwarding

## 1.4 Operating Environment

CargoSphere Logistics operates as an international air freight forwarding company based in Colombo, Sri Lanka, with its primary cargo operations coordinated through Bandaranaike International Airport (BIA).

The company manages both import and export shipments for corporate and business customers.

## 1.5 Project Purpose

The purpose of the CargoSphere Operations Platform is to provide a centralized digital platform for managing air cargo forwarding operations from shipment creation through completion.

The platform will improve operational visibility, reduce dependency on fragmented manual processes, centralize shipment information and provide appropriate information access to operational staff, management and customers.

---

# 2. Business Background

CargoSphere Logistics manages international air cargo shipments on behalf of importers and exporters.

The company coordinates activities involving customers, airline partners, cargo handling operations, documentation, customs and clearance processes, delivery providers and internal operational teams.

As the organization grows, managing shipment information across separate spreadsheets, email conversations and physical documents becomes increasingly difficult.

The company therefore requires a centralized system that can provide a consistent source of operational information throughout the shipment lifecycle.

---

# 3. Business Problem

CargoSphere currently relies on a combination of spreadsheets, email communication and physical documentation to manage shipment-related information.

This fragmented approach creates several operational challenges:

- Shipment information is distributed across multiple locations.
- Staff have limited visibility into the current status of shipments.
- Shipment updates may need to be communicated manually between departments.
- Missing or incomplete documentation can be difficult to identify.
- Customers frequently need to contact staff to obtain shipment updates.
- Management has limited real-time visibility into operational performance.
- Identifying delayed or exceptional shipments requires manual monitoring.
- Historical operational information is difficult to consolidate for reporting and analysis.

As shipment volumes increase, these limitations can affect operational efficiency, information accuracy and customer communication.

---

# 4. Proposed Solution

The proposed solution is the CargoSphere Operations Platform, a centralized web-based business application for managing air cargo import and export operations.

The platform will provide a shared operational environment where authorized users can create and manage shipments, monitor shipment status, manage documentation, coordinate delivery activities, identify exceptions and access operational reports.

The system will support different user roles and provide access to information according to each user's responsibilities.

---

# 5. Project Objectives

The project aims to:

1. Centralize shipment and cargo information.
2. Provide structured management of import and export shipments.
3. Improve visibility of shipment status throughout the operational lifecycle.
4. Provide centralized document management.
5. Identify and track shipment exceptions.
6. Provide customers with shipment visibility.
7. Provide management with operational dashboards and reports.
8. Implement role-based access to protect operational information.
9. Maintain an auditable history of important shipment activities.
10. Reduce reliance on fragmented manual information management processes.

---

# 6. Key Stakeholders

The anticipated stakeholders include:

- Operations Manager
- Operations Officers
- Documentation Officers
- Delivery Coordinators
- System Administrator
- Customers
- Management
- Airline and logistics partners

---

# 7. Initial User Roles

The initial system design will consider the following roles:

### System Administrator

Responsible for:

- User management
- Role and permission management
- System configuration
- Monitoring system activity
- Access to audit information

### Operations Manager

Responsible for:

- Monitoring shipments
- Reviewing operational performance
- Managing operational exceptions
- Assigning operational activities
- Accessing management reports

### Operations Officer

Responsible for:

- Creating shipments
- Updating shipment information
- Updating shipment statuses
- Managing cargo information
- Recording operational activities

### Documentation Officer

Responsible for:

- Managing shipment documentation
- Recording document status
- Identifying missing documentation
- Verifying required documents

### Delivery Coordinator

Responsible for:

- Coordinating cargo deliveries
- Assigning delivery activities
- Updating delivery status
- Recording delivery information

### Customer

Responsible for:

- Viewing their shipments
- Tracking shipment status
- Viewing available shipment information
- Accessing relevant documents
- Receiving shipment updates

---

# 8. High-Level Scope

## 8.1 In Scope

The initial project scope includes:

- User authentication
- Role-based access control
- Customer management
- Shipment management
- Import shipment management
- Export shipment management
- Cargo information management
- Air Waybill (AWB) information
- Shipment status tracking
- Flight information
- Document management
- Shipment exception management
- Delivery coordination
- Customer shipment tracking
- Operational dashboard
- Basic reporting
- Audit/activity history
- System administration

## 8.2 Out of Scope

The following areas are initially outside the project scope:

- Direct airline reservation systems
- Real-time airline API integrations
- Direct customs authority integration
- Online payment gateway integration
- Physical warehouse automation
- IoT-based cargo tracking
- Full accounting/ERP functionality
- Actual airline cargo booking transactions

These areas may be considered as future enhancements.

---

# 9. High-Level Shipment Lifecycle

## Export Shipment

Customer Booking  
→ Shipment Creation  
→ Cargo Acceptance  
→ Documentation  
→ Customs/Clearance  
→ Airline Handover  
→ Flight Departure  
→ Destination  
→ Shipment Completion

## Import Shipment

Flight Arrival  
→ Cargo Receipt  
→ Documentation  
→ Customs/Clearance  
→ Cargo Release  
→ Delivery Coordination  
→ Delivery  
→ Shipment Completion

---

# 10. Shipment Exceptions

The system will support identification and tracking of operational exceptions, including:

- Missing documentation
- Customs delays
- Flight delays
- Cargo damage
- Delivery issues
- Other operational exceptions

Exceptions will include appropriate status and priority information.

---

# 11. Success Criteria

The project will be considered successful when the developed platform can:

- Manage the core import and export shipment lifecycle.
- Allow authorized users to perform their assigned operations.
- Maintain centralized shipment information.
- Track shipment status changes.
- Manage required shipment documentation.
- Record and track operational exceptions.
- Provide customer shipment visibility.
- Provide useful operational dashboards and reports.
- Enforce role-based access control.
- Maintain an activity/audit history.
- Be deployed as a functioning web application.

---

# 12. Initial Technology Direction

The final technology stack will be confirmed during the system design phase.

The project is expected to use a modern web application architecture consisting of:

- Frontend application
- Backend REST API
- Relational or document-based database
- Authentication and authorization layer
- Cloud deployment environment
- Version control through Git and GitHub

Technology decisions will be documented in the project Decision Log.

---

# 13. Project Development Approach

The project will follow an iterative software development approach.

The major phases are:

1. Discovery and Project Initialization
2. Requirements Analysis
3. System Analysis and Design
4. UI/UX Design
5. Backend Development
6. Frontend Development
7. Integration
8. Testing
9. Deployment
10. Documentation and Final Review

Development work will be managed through Git branches and meaningful commits.

---

# 14. Initial Project Timeline

| Phase | Description | Status |
|---|---|---|
| Phase 1 | Discovery & Project Initialization | In Progress |
| Phase 2 | Requirements Analysis | Planned |
| Phase 3 | System Analysis & Design | Planned |
| Phase 4 | UI/UX Design | Planned |
| Phase 5 | Backend Development | Planned |
| Phase 6 | Frontend Development | Planned |
| Phase 7 | Integration | Planned |
| Phase 8 | Testing | Planned |
| Phase 9 | Deployment | Planned |
| Phase 10 | Final Documentation | Planned |

Detailed dates and milestones will be established as the project progresses.

---

# 15. Project Documentation Strategy

The project will maintain documentation throughout development rather than creating documentation only after implementation.

The documentation structure will include:

- Project Charter
- Requirements Documentation
- System Design Documentation
- UI/UX Documentation
- Testing Documentation
- Deployment Documentation
- Decision Log
- Project Timeline
- Final Project Report

All significant project decisions and changes will be recorded.

---

# 16. Version History

| Version | Date | Description | Author |
|---|---|---|---|
| 1.0 | 21 September 2026 | Initial Project Charter | Sahan Anjana Munasinghe |

---

# 17. Approval

This document establishes the initial project direction for the CargoSphere Operations Platform.

Further requirements, technical decisions and scope changes will be documented and version-controlled throughout the project lifecycle.