# UMNR Project Roadmap

## Overview

This roadmap translates the documented UMNR requirements into a structured delivery sequence.

The roadmap is organized around dependencies between major product capabilities rather than fixed calendar dates. This allows delivery timelines to be adjusted based on team capacity, technical complexity, and stakeholder priorities.

---

## Phase 1 — Foundation & Access

### Objective
Establish the platform foundation and secure user access.

### Scope
- Authentication
- User registration
- Role-Based Access Control (RBAC)
- Agency onboarding
- Talent onboarding
- Core account structure

### Key Outcome
Users can securely access the platform and receive appropriate permissions based on their assigned roles.

---

## Phase 2 — Talent Management

### Objective
Establish the core talent-management functionality required for agency operations.

### Scope
- Talent directory
- Talent profiles
- Search and filtering
- Availability management
- Media portfolio management
- Restricted access to sensitive talent information

### Dependencies
- Authentication
- User roles and permissions
- Core user and talent data

### Key Outcome
Agency teams can create, organize, search, and manage talent information.

---

## Phase 3 — Casting Management

### Objective
Enable agencies to manage casting workflows.

### Scope
- Casting creation
- Talent discovery
- Talent shortlisting
- Submission review

### Dependencies
- Talent management
- Search and filtering
- User permissions

### Key Outcome
Casting teams can create opportunities, identify suitable talent, and manage candidate shortlists.

---

## Phase 4 — Booking & Scheduling

### Objective
Enable agencies to convert casting activity into structured bookings while preventing scheduling conflicts.

### Scope
- Single-day bookings
- Multi-day bookings
- Talent availability checks
- Conflict detection
- Authorized conflict overrides
- Calendar management
- Booking rescheduling

### Dependencies
- Talent profiles
- Talent availability
- Casting workflows
- User permissions

### Key Outcome
Agency teams can create and manage bookings while maintaining accurate scheduling information.

---

## Phase 5 — Communication & Documents

### Objective
Centralize operational communication and documentation.

### Scope
- Job-specific messaging
- File sharing
- Notifications
- Contract management
- Document status tracking

### Dependencies
- Casting records
- Booking records
- User access controls

### Key Outcome
Users can communicate and manage relevant documentation within the context of active work.

---

## Phase 6 — Analytics & Administration

### Objective
Provide management visibility and administrative controls.

### Scope
- Talent performance analytics
- Booking analytics
- Financial reporting
- Data exports
- Permission management
- Subscription administration

### Dependencies
- Operational data from previous phases
- Access controls
- Booking and talent records

### Key Outcome
Authorized users can monitor platform activity, analyze performance, and manage administrative settings.

---

## Delivery Approach

Development should prioritize foundational capabilities before features that depend on them.

Authentication, access control, and core talent data should therefore be established before casting, booking, communication, and analytics functionality.

Each phase should pass defined acceptance criteria before dependent functionality is considered ready for release.
