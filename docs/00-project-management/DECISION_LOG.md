# CargoSphere Operations Platform
# Decision Log

This document records significant project decisions and the reasoning behind them.

Decisions are documented throughout the project so that technical and business choices can be explained during project reviews and interviews.

---

## Decision 001 — Project Domain

**Date:** 21 September 2026

**Decision:**  
The project will focus on the air cargo and freight forwarding industry.

**Reason:**  
The domain provides realistic business workflows involving shipments, documentation, cargo handling, customs/clearance processes, airline coordination and delivery.

**Impact:**  
The system will require business workflows beyond basic CRUD functionality.

---

## Decision 002 — Cargo Type

**Date:** 21 September 2026

**Decision:**  
The system will support both import and export air cargo operations.

**Reason:**  
Supporting both directions provides a more complete representation of an air freight forwarding operation and allows the system to model different shipment lifecycle workflows.

**Impact:**  
The system will need separate but related workflows for import and export shipments.

---

## Decision 003 — Fictional Client Organization

**Date:** 21 September 2026

**Decision:**  
The fictional client will be named CargoSphere Logistics (Pvt) Ltd.

**Reason:**  
A dedicated fictional organization allows the project to be presented as a realistic business case while clearly distinguishing it from actual professional client work.

**Impact:**  
All company information, operational data and business scenarios used in the project will be fictional unless explicitly identified otherwise.

---

## Decision 004 — Operational Environment

**Date:** 21 September 2026

**Decision:**  
CargoSphere will be based in Colombo, Sri Lanka, with Bandaranaike International Airport (BIA) established as its primary operational environment.

**Reason:**  
This provides a realistic operational context for an air cargo/freight-forwarding system and supports relevant business concepts such as AWBs, cargo acceptance, airline coordination, documentation and delivery.

**Impact:**  
The system's terminology and example workflows will be designed around international air cargo operations.

---

## Decision 005 — Centralized Operations Platform

**Date:** 21 September 2026

**Decision:**  
The proposed solution will be a centralized web-based operations platform.

**Reason:**  
The identified business problem involves fragmented shipment information and limited operational visibility. A centralized system can provide a common source of operational information for authorized users.

**Impact:**  
The solution will be designed around centralized data, role-based access and shared operational workflows.

---

## Decision 006 — Git Branching Strategy

**Date:** 21 September 2026

**Decision:**  
The project will use `main` as the stable branch and `develop` as the active development branch. Feature-specific work will use dedicated branches where appropriate.

**Reason:**  
Separating stable releases from active development provides a clean project history and supports controlled development.

**Impact:**  
Changes will normally be developed and reviewed through the appropriate development branch before being incorporated into the stable branch.

---

## Decision 007 — Documentation Throughout Development

**Date:** 21 September 2026

**Decision:**  
Project documentation, decisions, timeline information and significant development activities will be recorded throughout the project rather than created only at the end.

**Reason:**  
Continuous documentation provides an accurate development history and supports creation of the final project report.

**Impact:**  
Documentation will be maintained as a first-class project activity and tracked through Git.