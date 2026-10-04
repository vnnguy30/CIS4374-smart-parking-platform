# Semester Project: Smart Parking Platform

**Version:** 0.5 (Week 5)
**Last updated:** October 4, 2026

## Table of Contents

1. [Project Overview](#project-overview)
2. [Business Need](#business-need)
3. [High-Level Requirements](#high-level-requirements)
4. [Stakeholders](#stakeholders)
5. [Development Teams](#development-teams)
6. [Project Constraints](#project-constraints)
7. [Research Component](#research-component)
8. [Weekly Update Log](#weekly-update-log)

---

## Project Overview

We are **$oftware ¢orp.**, a fictitious software development studio with unlimited resources and budget.

The project involves the planning and management of a software system that helps drivers locate, reserve, and pay for parking spaces in parking garages in real time. The platform will be available through web and mobile applications and will provide parking availability information, navigation assistance, and management tools for parking operators.

The goal is to develop a project management plan for the creation of this system, including requirements gathering, stakeholder management, scheduling, budgeting, risk management, and team coordination.

## Business Need

Drivers often spend significant time searching for available parking, leading to congestion, frustration, and lost productivity. Parking operators need better tools to monitor occupancy, manage pricing, and improve utilization of parking assets.

## High-Level Requirements

The platform should provide:

- User registration and authentication
- Real-time parking space availability
- Interactive map displaying available parking locations
- Parking reservation capability
- Digital payment processing
- Reservation history and receipts
- Administrative dashboard for parking operators
- Occupancy reporting and analytics
- Notifications and alerts for users
- Integration with external mapping/navigation services

Additional requirements will be identified through stakeholder analysis and requirements elicitation activities in upcoming weeks.

## Stakeholders

- Drivers and vehicle owners
- Parking facility operators
- City transportation departments
- System administrators
- Finance and billing personnel
- Mobile application users
- Third-party payment providers

## Development Teams

- Mobile Application Team
- Web Application Team
- Backend/API Team
- Mapping & Location Services Team
- Payment Integration Team
- Quality Assurance & Testing Team

## Project Constraints

- Unlimited theoretical development budget
- Fixed semester timeline
- Dependence on third-party services and APIs
- Compliance with security and privacy requirements, city ordinance & laws

## Research Component

## Work Breakdown Structure & Timeline

### Work Breakdown Structure (Parking App)

1. Smart Parking Platform
   1. Authentication & User Management
      1. User registration (driver)
      2. Operator registration
      3. Login / session management
      4. Password reset
   2. Driver-Facing Features
      1. Search & find available parking
      2. View garage details (price, hours, availability)
      3. Reserve a parking spot
      4. Payment processing
      5. Reservation confirmation & receipt
   3. Operator Dashboard
      1. Add / edit / remove garage
      2. Set pricing & availability rules
      3. Monitor real-time occupancy
      4. Manage reservations
   4. Reporting
      1. Occupancy graphs
      2. Revenue/financial reports
      3. Export reports (PDF/CSV)
   5. Project Management Docs
      1. Update PROJECT.md / VISION_AND_SCOPE.md / SRS.md
      2. Weekly video updates

### Draft Timeline

This is a rough draft timeline and will be refined as scope firms up.

![Draft Gantt Chart](./assets/gantt-draft-hw2.png)

| Phase | Weeks |
|---|---|
| Authentication & user management | 2–3 |
| Driver-facing features | 3–5 |
| Operator dashboard | 4–6 |
| Reporting | 6–7 |
| PM docs (ongoing) | 2–8 |

## Product Backlog & Sprint Planning

A full product backlog (45 items across Login, UI, Backend, and Reporting) was created and planned into Sprint 1 using Trello. See the board screenshot below.

![Sprint 1 Trello Board](./docs/sprint1-board.png)

**Sprint 1 goal:** Users can register/login, and drivers can search for and reserve a parking spot.

Sprint 1 scope (11 items):
- User registration (email/password) for drivers
- Operator login (separate role/permissions)
- Password reset flow
- Logout functionality
- Driver: search parking spots by location
- Driver: reserve a spot (date/time picker)
- API: create user account
- API: authenticate user (login/token)
- API: create reservation
- Database schema: users table
- Database schema: reservations table

## Risk Management & Communication Plan

### Risks by Category

**Technical:** parking data sync errors, mapping API downtime, payment security issues, app inconsistency across platforms

**Schedule:** payment integration delays, dashboard scope creep, compressed testing time, vendor delays

**Financial:** API costs over budget, scope-change costs, hosting costs underestimated, payment fees cut into revenue

**People:** developer unavailable, team miscommunication, inexperience with tech stack, stakeholder unavailable for feedback

### Risk Register

| ID | Description | Probability | Impact | Owner | Response | Status |
|----|---|---|---|---|---|---|
| R01 | Parking data fails to sync | Medium | High | Backend Team | Mitigate | Open |
| R02 | Mapping API downtime | Medium | High | Mapping Team | Mitigate | Open |
| R03 | Payment security vulnerability | Low | High | Payment Team | Avoid | Open |
| R04 | App inconsistent across platforms | Medium | Medium | Mobile/Web Team | Mitigate | Open |
| R05 | Payment integration delayed | Medium | Medium | Payment Team | Accept | Monitoring |
| R06 | Dashboard scope creep | Medium | Medium | Web Team | Mitigate | Monitoring |
| R07 | Testing time compressed | Medium | High | QA Team | Mitigate | Open |
| R08 | API costs exceed budget | Medium | Medium | PM | Mitigate | Open |
| R09 | Developer unavailable | Medium | High | PM | Mitigate | Monitoring |
| R10 | Team miscommunication | Medium | Medium | PM | Mitigate | Open |

### Communication Plan

- **Weekly team sync** for each development team to review progress and blockers
- **Bi-weekly stakeholder update** summarizing progress, risks, and milestones
- **Reporting via:** Trello board, written updates in `PROJECT.md`, weekly video update


## Resource & Cost Management

### Roles & Resources

| Role | Name (fictional) | Skill Level | % Allocation |
|---|---|---|---|
| Project Manager | Alex Rivera | Senior | 25% |
| Backend Developer | Sam Patel | Mid-level | 100% |
| Frontend/Web Developer | Jordan Lee | Mid-level | 100% |
| Mobile Developer | Casey Nguyen | Mid-level | 75% |
| Mapping & Location Specialist | Morgan Diaz | Senior | 50% |
| Payment Integration Developer | Taylor Kim | Mid-level | 50% |
| QA/Test Engineer | Riley Chen | Junior | 75% |

### Resource Plan (Bottom-Up)

| Role | Name | FTE % | Estimated Hours | Hourly Rate | Cost |
|---|---|---|---|---|---|
| Project Manager | Alex Rivera | 25% | 80 | $60 | $4,800 |
| Backend Developer | Sam Patel | 100% | 320 | $55 | $17,600 |
| Frontend/Web Developer | Jordan Lee | 100% | 320 | $50 | $16,000 |
| Mobile Developer | Casey Nguyen | 75% | 240 | $50 | $12,000 |
| Mapping & Location Specialist | Morgan Diaz | 50% | 160 | $65 | $10,400 |
| Payment Integration Developer | Taylor Kim | 50% | 160 | $55 | $8,800 |
| QA/Test Engineer | Riley Chen | 75% | 240 | $35 | $8,400 |
| **Total** | | | **1,520** | | **$78,000** |

### Cost Plan & Monthly Cashflow

Project runs 8 weeks (~2 months) for this semester simulation.

| Month | Planned Spend | Notes |
|---|---|---|
| Month 1 | $42,000 | Heaviest phase — auth, driver features, dashboard build-out |
| Month 2 | $36,000 | Reporting, testing, QA, wrap-up |
| **Total** | **$78,000** | |

### RACI Matrix

**R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed

| Task/Deliverable | PM (Alex) | Backend (Sam) | Web (Jordan) | Mobile (Casey) | Mapping (Morgan) | Payment (Taylor) | QA (Riley) |
|---|---|---|---|---|---|---|---|
| Authentication & login | A | R | C | C | I | I | C |
| Driver search & reservation | A | R | R | R | C | I | C |
| Operator dashboard | A | C | R | I | I | I | C |
| Payment processing | A | C | I | I | I | R | C |
| Mapping/navigation integration | A | C | I | I | R | I | C |
| Reporting features | A | R | R | I | I | I | C |
| Testing & QA | A | C | C | C | C | C | R |
| Weekly stakeholder updates | R | I | I | I | I | I | I |


## Weekly Update Log

### Week 1 — September 7, 2026

- Created public GitHub repository
- Drafted initial project document (overview, business need, high-level requirements, stakeholders, development teams, constraints)
- Recorded week 1 video update for stakeholders

### Week 2 — September 11, 2026

- Created Work Breakdown Structure (3+ levels deep) for the Parking App
- Drafted project timeline including Gantt chart
- Recorded week 2 video update for stakeholders

### Week 3 — September 24, 2026

- Created full product backlog (45 items) covering Login, UI, Backend, and Reporting for both driver and operator roles
- Planned Sprint 1 (11 items) in Trello
- Saved Sprint 1 board screenshot to `docs/sprint1-board.png`
- Recorded week 3 video update for stakeholders\

### Week 4 — September 30, 2026

- Identified 4+ risks per category (technical, schedule, financial, people)
- Built a Risk Register with 10 entries
- Created a Communication Plan for team meetings and reporting
- Recorded week 4 video update for stakeholders

### Week 5 — October 4, 2026

- Defined project roles with fictional names, skill levels, and % allocations
- Built a bottom-up Resource & Cost Plan with estimated hours and total cost
- Created a monthly budgeted cashflow
- Created a RACI matrix for key project tasks
- Recorded week 5 video update for stakeholders