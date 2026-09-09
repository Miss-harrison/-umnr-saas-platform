# Functional Requirements

## Overview

This document defines the core functional requirements for the UMNR platform.

Each requirement is assigned a unique identifier to support traceability throughout development, testing, and project delivery.

---

## 1. Authentication & Onboarding

**AUTH-001:** The system shall support secure email/password registration and OAuth 2.0 authentication.

**AUTH-002:** During registration, users shall select an appropriate role: Agency Admin, Staff, or Talent.

**AUTH-003:** Agency administrators shall complete an onboarding process that captures agency details, branding assets, and tenant configuration.

**AUTH-004:** Talent users shall complete an onboarding process for profile information, portfolio assets, measurements, identification documents, and relevant social links.

---

## 2. Main Dashboard

**DASH-001:** The dashboard shall display operational metrics including active bookings, upcoming castings, available talent, and pending requests.

**DASH-002:** Users shall have access to quick actions for frequently performed tasks such as adding talent, creating castings, and creating bookings.

**DASH-003:** The dashboard shall provide an activity feed displaying relevant operational updates.

---

## 3. Talent Management

**TMS-001:** Users shall be able to view the talent directory using both grid and table layouts.

**TMS-002:** The system shall support talent search and filtering based on criteria including category, location, availability, and skills.

**TMS-003:** Users shall be able to preview key talent information without leaving the talent directory.

---

## 4. Talent Profiles

**PROF-001:** Talent profiles shall support high-quality images and video portfolio content.

**PROF-002:** Talent profiles shall display availability, previous bookings, and pending scheduling holds.

**PROF-003:** Sensitive talent information shall only be accessible to authorized users.

---

## 5. Casting Management

**CAST-001:** Authorized users shall be able to create castings containing project information, client details, location, and budget parameters.

**CAST-002:** Casting users shall be able to search for talent and create shortlists.

**CAST-003:** The system shall support reviewing talent submissions against relevant profile information.

---

## 6. Booking Management

**BOOK-001:** The system shall support single-day and multi-day bookings.

**BOOK-002:** The system shall check talent availability before confirming a booking and identify scheduling conflicts.

**BOOK-003:** Authorized administrators shall be able to override booking conflicts when operationally necessary.

---

## 7. Calendar & Scheduling

**CAL-001:** The system shall provide daily, weekly, and monthly calendar views.

**CAL-002:** Authorized users shall be able to reschedule bookings through the calendar interface.

**CAL-003:** Changes to booking dates shall trigger availability and scheduling conflict checks.

---

## 8. Messaging

**MSG-001:** Communication shall be organized into job-specific threads associated with castings or bookings.

**MSG-002:** Users shall be able to share supported files within relevant communication threads.

**MSG-003:** Users shall receive notifications for new messages and relevant mentions.

---

## 9. Contracts & Documents

**DOC-001:** Documents shall support defined lifecycle states including Draft, Sent, Signed, and Expired.

**DOC-002:** The platform shall provide an interface for viewing and interacting with contract documentation.

---

## 10. Analytics

**ANAL-001:** The system shall provide analytics relating to talent performance and booking activity.

**ANAL-002:** Authorized administrative users shall be able to access financial and revenue-related analytics.

**ANAL-003:** Authorized users shall be able to export supported analytical data.

---

## 11. Settings & Administration

**SET-001:** Administrative users shall be able to manage user permissions.

**SET-002:** The platform shall provide administrative visibility into subscription, renewal, and seat-utilization information.
