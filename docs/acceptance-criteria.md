# UMNR Acceptance Criteria

## Overview

This document defines high-level acceptance criteria for the major UMNR platform capabilities.

Acceptance criteria provide measurable conditions that can be used to determine whether a feature is ready for validation and completion.

---

## 1. Authentication & Onboarding

### AC-AUTH-001 — User Authentication

**Given** a registered user has valid credentials  
**When** the user attempts to sign in  
**Then** the system should authenticate the user and provide access according to the user's assigned role.

### AC-AUTH-002 — Role-Based Access

**Given** a user has been assigned a platform role  
**When** the user accesses the platform  
**Then** only features and information permitted for that role should be accessible.

### AC-AUTH-003 — User Onboarding

**Given** a new agency or talent user  
**When** the user completes the required onboarding information  
**Then** the system should create the appropriate account and profile.

---

## 2. Talent Management

### AC-TMS-001 — Talent Directory

**Given** an authorized user accesses talent management  
**When** the talent directory loads  
**Then** available talent records should be displayed.

### AC-TMS-002 — Search & Filtering

**Given** talent records exist  
**When** an authorized user applies supported search or filtering criteria  
**Then** the system should return records matching the selected criteria.

### AC-TMS-003 — Restricted Information

**Given** a talent profile contains restricted information  
**When** an unauthorized user accesses the profile  
**Then** restricted information should not be displayed.

---

## 3. Casting

### AC-CAST-001 — Casting Creation

**Given** an authorized user has the required casting information  
**When** a new casting is submitted  
**Then** the system should create the casting and make it available within the appropriate workflow.

### AC-CAST-002 — Talent Shortlisting

**Given** an active casting exists  
**When** an authorized user selects suitable talent  
**Then** the selected talent should be added to the casting shortlist.

---

## 4. Booking & Scheduling

### AC-BOOK-001 — Booking Creation

**Given** valid booking information has been provided  
**When** an authorized user creates a booking  
**Then** the booking should be recorded with the appropriate talent and scheduling information.

### AC-BOOK-002 — Conflict Detection

**Given** a talent user has an existing scheduling conflict  
**When** another booking is attempted for the conflicting period  
**Then** the system should identify the conflict before normal booking confirmation.

### AC-CAL-001 — Booking Rescheduling

**Given** an existing booking  
**When** an authorized user changes its scheduled date or time  
**Then** the system should validate the updated schedule for conflicts.

---

## 5. Messaging & Documents

### AC-MSG-001 — Job Communication

**Given** a user has access to a relevant casting or booking  
**When** the user accesses its communication area  
**Then** the user should be able to view permitted job-related communication.

### AC-DOC-001 — Document Status

**Given** a document exists within the platform  
**When** its lifecycle changes  
**Then** the appropriate document status should be reflected in the system.

---

## 6. Analytics & Administration

### AC-ANAL-001 — Analytics Access

**Given** sufficient operational data exists  
**When** an authorized user accesses analytics  
**Then** the platform should display the information permitted for that user's role.

### AC-SET-001 — Permission Management

**Given** an administrator has permission-management access  
**When** user permissions are modified  
**Then** subsequent access should reflect the updated permissions.

---

## Definition of Done

A requirement may be considered complete when:

- The documented requirement has been implemented.
- Relevant acceptance criteria have been satisfied.
- Required testing has been completed.
- No unresolved critical defects prevent intended use.
- Relevant documentation has been updated.
- Required stakeholder review has been completed.
