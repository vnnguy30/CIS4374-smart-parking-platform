# Software Requirements Specification (SRS): Smart Parking Platform

**Version:** 0.1
**Last updated:** September 10, 2026

## 1. Introduction

This document specifies the functional and non-functional requirements, and use cases, for the Smart Parking Platform. It will be refined and expanded weekly as the project progresses.

## 2. Functional Requirements

| ID | Requirement |
|----|-------------|
| FR-1 | The system shall allow drivers to register an account using email and password. |
| FR-2 | The system shall allow drivers to log in and log out securely. |
| FR-3 | The system shall display real-time parking space availability on an interactive map. |
| FR-4 | The system shall allow drivers to reserve a specific parking space for a selected time window. |
| FR-5 | The system shall allow drivers to pay for a reservation using a credit/debit card or digital wallet. |
| FR-6 | The system shall generate a digital receipt for each completed transaction. |
| FR-7 | The system shall allow drivers to view their reservation history. |
| FR-8 | The system shall allow drivers to cancel a reservation before its start time, per operator cancellation policy. |
| FR-9 | The system shall send notifications to drivers (e.g., reservation confirmation, expiration reminders). |
| FR-10 | The system shall provide turn-by-turn navigation to a reserved space via integration with an external mapping service. |
| FR-11 | The system shall allow parking operators to log into an administrative dashboard. |
| FR-12 | The system shall allow operators to add, update, and remove parking spaces/garages from the platform. |
| FR-13 | The system shall allow operators to set and update pricing for their parking spaces. |
| FR-14 | The system shall provide operators with occupancy and revenue analytics reports. |
| FR-15 | The system shall allow operators to view and manage current and upcoming reservations for their facility. |

## 3. Non-Functional Requirements

| ID | Requirement |
|----|-------------|
| NFR-1 | The system must load the parking availability map within 2 seconds for up to 1,000 concurrent users. |
| NFR-2 | The system must maintain 99.9% uptime. |
| NFR-3 | The system must encrypt all payment and personal data in transit and at rest. |
| NFR-4 | The system shall allow a new driver to complete registration in 3 steps or fewer. |
| NFR-5 | The system must comply with applicable data privacy regulations and city parking ordinances. |

## 4. Use Cases

| # | Use Case Name | Primary Actor | Description |
|---|---------------|---------------|--------------|
| 1 | Register Account | Driver | Driver creates a new account using email and password. |
| 2 | Log In | Driver | Driver logs into their account to access the platform. |
| 3 | Search for Available Parking | Driver | Driver searches for parking near a destination and views results on a map. |
| 4 | View Parking Space Details | Driver | Driver views details of a specific space (price, hours, distance). |
| 5 | Reserve a Parking Space | Driver | Driver selects a space and time window and confirms a reservation. |
| 6 | Pay for a Reservation | Driver | Driver completes payment for a reservation via card or digital wallet. |
| 7 | Cancel a Reservation | Driver | Driver cancels an upcoming reservation within the allowed cancellation window. |
| 8 | View Reservation History | Driver | Driver views past and upcoming reservations and receipts. |
| 9 | Receive Notification | Driver | Driver receives a notification (confirmation, reminder, or expiration alert). |
| 10 | Navigate to Parking Space | Driver | Driver receives turn-by-turn directions to a reserved space. |
| 11 | Operator Login | Parking Operator | Operator logs into the administrative dashboard. |
| 12 | Add/Edit Parking Facility | Parking Operator | Operator adds a new facility or edits an existing facility's details. |
| 13 | Set Pricing | Parking Operator | Operator sets or updates pricing rules for a facility. |
| 14 | View Occupancy Analytics | Parking Operator | Operator views real-time and historical occupancy data for their facility. |
| 15 | View Revenue Report | Parking Operator | Operator generates a revenue report for a selected time period. |
| 16 | Manage Reservations | Parking Operator | Operator views, and if necessary overrides or cancels, reservations at their facility. |
| 17 | System Admin Manages Users | System Administrator | Admin manages driver and operator accounts (e.g., suspending accounts for abuse). |


## 5. Future Work

- Expand each use case into full use-case specifications (actors, preconditions, trigger, main flow, alternate/exception flows, postconditions).
- Add sequence/activity diagrams for key flows (reservation + payment).
- Refine non-functional requirements with measurable targets as research continues.