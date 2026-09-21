# CargoSphere Operations Platform
# User Requirements Specification

**Document Version:** 1.0  
**Date:** 21 September 2026  
**Status:** Draft – Requirements Discovery

---

## 1. Purpose

This document defines the initial user requirements identified during the requirements discovery phase of the CargoSphere Operations Platform.

Each requirement is assigned a unique identifier to support traceability throughout system design, development and testing.

The requirements will be refined and approved before being converted into detailed functional and non-functional requirements.

---

# 2. System Administrator Requirements

## User Management

**UR-ADM-001**  
The System Administrator shall be able to create user accounts.

**UR-ADM-002**  
The System Administrator shall be able to update user information.

**UR-ADM-003**  
The System Administrator shall be able to activate or deactivate user accounts.

**UR-ADM-004**  
The System Administrator shall be able to assign a predefined role to a user.

## System Configuration

**UR-ADM-005**  
The System Administrator shall be able to manage configurable system reference data.

**UR-ADM-006**  
The System Administrator shall be able to manage applicable document types and categories.

**UR-ADM-007**  
The System Administrator shall be able to manage applicable shipment and exception reference data.

## Monitoring

**UR-ADM-008**  
The System Administrator shall be able to view system audit activity.

**UR-ADM-009**  
The System Administrator shall be able to initiate a password reset for a user.

---

# 3. Operations Manager Requirements

## Shipment Oversight

**UR-OPS-MGR-001**  
The Operations Manager shall be able to view all active shipments.

**UR-OPS-MGR-002**  
The Operations Manager shall be able to search and filter shipments.

**UR-OPS-MGR-003**  
The Operations Manager shall be able to view operational shipment details.

## Operational Management

**UR-OPS-MGR-004**  
The Operations Manager shall be able to assign operational tasks.

**UR-OPS-MGR-005**  
The Operations Manager shall be able to reassign operational tasks when required.

**UR-OPS-MGR-006**  
The Operations Manager shall be able to monitor outstanding operational activities.

## Exception Management

**UR-OPS-MGR-007**  
The Operations Manager shall be able to view active shipment exceptions.

**UR-OPS-MGR-008**  
The Operations Manager shall be able to manage shipment exceptions.

**UR-OPS-MGR-009**  
The Operations Manager shall be able to monitor the resolution of operational exceptions.

## Reporting

**UR-OPS-MGR-010**  
The Operations Manager shall be able to view operational performance information.

**UR-OPS-MGR-011**  
The Operations Manager shall be able to access operational reports.

---

# 4. Operations Officer Requirements

## Shipment Creation

**UR-OPS-001**  
The Operations Officer shall be able to create an import or export shipment.

**UR-OPS-002**  
The system shall generate a unique internal reference for each shipment.

## Shipment Management

**UR-OPS-003**  
The Operations Officer shall be able to enter and maintain shipment information.

**UR-OPS-004**  
The Operations Officer shall be able to search and filter shipments.

**UR-OPS-005**  
The Operations Officer shall be able to view complete shipment details.

**UR-OPS-006**  
The Operations Officer shall be able to update permitted shipment information.

## Status Management

**UR-OPS-007**  
The Operations Officer shall be able to update shipment status according to the defined workflow.

**UR-OPS-008**  
The Operations Officer shall be able to view shipment activity history.

## Operational Activities

**UR-OPS-009**  
The Operations Officer shall be able to record operational activities and notes.

**UR-OPS-010**  
The Operations Officer shall be able to view pending operational tasks.

**UR-OPS-011**  
The Operations Officer shall be able to update assigned task status.

**UR-OPS-012**  
The Operations Officer shall be able to escalate operational issues.

---

# 5. Documentation Officer Requirements

## Document Management

**UR-DOC-001**  
The Documentation Officer shall be able to view the document requirements for a shipment.

**UR-DOC-002**  
The Documentation Officer shall be able to upload shipment documents.

**UR-DOC-003**  
The Documentation Officer shall be able to view and download shipment documents.

**UR-DOC-004**  
The Documentation Officer shall be able to update the review status of a document.

**UR-DOC-005**  
The Documentation Officer shall be able to reject a document and provide a reason.

**UR-DOC-006**  
The Documentation Officer shall be able to replace a rejected document.

## Document Compliance

**UR-DOC-007**  
The Documentation Officer shall be able to identify missing required documents.

**UR-DOC-008**  
The Documentation Officer shall be able to add notes related to shipment documentation.

**UR-DOC-009**  
The system shall maintain document version and history information.

**UR-DOC-010**  
The system shall prevent an applicable shipment from progressing through workflow stages when mandatory documentation requirements have not been satisfied.

---

# 6. Clearance Officer Requirements

## Clearance Management

**UR-CLR-001**  
The Clearance Officer shall be able to view shipments requiring clearance activity.

**UR-CLR-002**  
The Clearance Officer shall be able to create a clearance record for an applicable shipment.

**UR-CLR-003**  
The Clearance Officer shall be able to record clearance reference information.

**UR-CLR-004**  
The Clearance Officer shall be able to update the clearance status.

## Clearance Issues

**UR-CLR-005**  
The Clearance Officer shall be able to record clearance issues.

**UR-CLR-006**  
The Clearance Officer shall be able to request additional information or documentation.

## Cargo Release

**UR-CLR-007**  
The Clearance Officer shall be able to record the release of cleared cargo.

**UR-CLR-008**  
The Clearance Officer shall be able to add clearance-related notes.

**UR-CLR-009**  
The system shall maintain the history of clearance status changes.

**UR-CLR-010**  
The system shall make applicable shipment workflow stages dependent on the appropriate clearance status.

---

# 7. Delivery Coordinator Requirements

## Delivery Requests

**UR-DEL-001**  
The Delivery Coordinator shall be able to view shipments eligible for delivery.

**UR-DEL-002**  
The Delivery Coordinator shall be able to create a delivery request.

**UR-DEL-003**  
The Delivery Coordinator shall be able to record the delivery address and customer contact information.

## Delivery Scheduling

**UR-DEL-004**  
The Delivery Coordinator shall be able to schedule a delivery.

**UR-DEL-005**  
The Delivery Coordinator shall be able to assign a transport provider.

**UR-DEL-006**  
The Delivery Coordinator shall be able to assign a driver and vehicle.

## Delivery Tracking

**UR-DEL-007**  
The Delivery Coordinator shall be able to update delivery status.

**UR-DEL-008**  
The Delivery Coordinator shall be able to record delivery failures and reasons.

**UR-DEL-009**  
The Delivery Coordinator shall be able to reschedule failed deliveries.

## Proof of Delivery

**UR-DEL-010**  
The Delivery Coordinator shall be able to record proof-of-delivery information.

**UR-DEL-011**  
The Delivery Coordinator shall be able to upload proof-of-delivery documentation.

**UR-DEL-012**  
The system shall maintain the history of delivery status changes.

---

# 8. Customer Requirements

## Authentication and Access

**UR-CUS-001**  
The Customer shall be able to securely log into the CargoSphere platform.

**UR-CUS-002**  
The system shall prevent customers from accessing shipments belonging to other customers.

## Shipment Tracking

**UR-CUS-003**  
The Customer shall be able to view their own shipments.

**UR-CUS-004**  
The Customer shall be able to search and filter their shipments.

**UR-CUS-005**  
The Customer shall be able to view shipment tracking information.

**UR-CUS-006**  
The Customer shall be able to view relevant shipment details.

## Documents and Delivery

**UR-CUS-007**  
The Customer shall be able to view customer-accessible shipment documents.

**UR-CUS-008**  
The Customer shall be able to view delivery information for applicable shipments.

## Notifications and Account

**UR-CUS-009**  
The Customer shall be able to receive important shipment notifications.

**UR-CUS-010**  
The Customer shall be able to manage permitted account information.

**UR-CUS-011**  
The system shall prevent customers from accessing internal operational information that is not designated as customer-visible.

---

# 9. Cross-Role Business Requirements

The following requirements apply across multiple user roles.

**UR-CROSS-001**  
The system shall maintain a unique internal reference for every shipment.

**UR-CROSS-002**  
The system shall maintain a history of significant shipment activities.

**UR-CROSS-003**  
The system shall enforce valid shipment status transitions.

**UR-CROSS-004**  
The system shall enforce role-based access control.

**UR-CROSS-005**  
The system shall maintain an audit trail for significant system activities.

**UR-CROSS-006**  
The system shall allow operational exceptions to be associated with relevant shipments.

**UR-CROSS-007**  
The system shall maintain the history of significant status changes.

**UR-CROSS-008**  
The system shall protect customer information from unauthorized access.

**UR-CROSS-009**  
The system shall maintain document visibility according to the document's access classification.

**UR-CROSS-010**  
The system shall prevent dependent operational activities from proceeding when required business conditions have not been satisfied.

---

# 10. Initial Business Rules

## BR-001 — Role-Based Access

Users shall only access functionality permitted by their assigned role.

## BR-002 — Shipment Status

Shipment status changes shall follow defined workflow transitions.

## BR-003 — Document Compliance

Mandatory documentation requirements shall be satisfied before applicable workflow stages can proceed.

## BR-004 — Clearance Dependency

Applicable cargo shall not proceed to release-dependent activities until the required clearance process has been completed.

## BR-005 — Delivery Eligibility

A delivery request shall only be created when the shipment is eligible for delivery according to the applicable workflow.

## BR-006 — Customer Data Isolation

Customers shall only access information belonging to their own organization/account.

## BR-007 — Auditability

Important system activities shall retain information about the user, action and relevant timestamp.

## BR-008 — User Deactivation

Deactivating a user account shall not remove historical records associated with that user.

## BR-009 — Document History

Replacing a document shall preserve the relevant document history rather than silently removing previous versions.

---

# 11. Requirement Traceability

Each user requirement has been assigned a unique identifier.

These identifiers will be used later to establish relationships between:

```text
User Requirement
        ↓
Functional Requirement
        ↓
Use Case
        ↓
System Feature
        ↓
Test Case
        ↓
Test Result 