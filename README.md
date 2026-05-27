# FirstAid Connect - ELEC1005 Assignment 2

## Project Overview

**FirstAid Connect** is a community safety and first aid response application developed using **Microsoft Power Apps**. The app is designed to support emergency coordination during community events by connecting three main user groups:

- Residents / Public users
- Community safety volunteers
- Administrators / coordinators

The project was developed as part of **ELEC1005 Assignment 2**, building on the software prototype and requirements from Assignment 1. The main goal of the app is to provide a functional Power Apps prototype that supports emergency SOS submission, volunteer dispatch, incident tracking, volunteer status management, and shift creation.

---

## Main Purpose

FirstAid Connect helps community event teams respond more quickly and clearly to first aid incidents.

The system allows:

1. A resident to submit a medical assistance request.
2. An administrator to view active incidents.
3. An administrator to dispatch an available volunteer.
4. A volunteer to view the assigned incident.
5. A volunteer to mark the incident as resolved.
6. An administrator to create volunteer shifts.

---

## User Roles

### 1. Resident / Public

Residents can:

- Submit an SOS medical assistance request.
- Select an incident type.
- Enter their location.
- Add additional notes.
- Use current location if browser/device permission is available.
- View first aid guidance.

### 2. Volunteer

Volunteers can:

- Select their volunteer profile.
- View their current availability status.
- Update status to Available, Responding, or On Break.
- View their current assigned incident.
- Open the incident detail screen.
- Mark an incident as resolved.
- View assigned shifts.

### 3. Administrator

Administrators can:

- View the operations dashboard.
- See active incidents.
- See volunteer availability counts.
- Dispatch available volunteers to new incidents.
- Create duty shifts for volunteers.
- Refresh incident and volunteer data.

---

## Core Features

| Feature | Description |
|---|---|
| Role-based Home Screen | Provides separate entry points for Resident, Volunteer, and Administrator users. |
| SOS Submission | Allows residents to submit emergency assistance requests. |
| First Aid Guide | Provides quick-reference first aid guidance for common emergencies. |
| SOS Confirmation | Confirms that an emergency request has been submitted successfully. |
| Admin Dashboard | Shows active incident count and volunteer availability. |
| Dispatch Volunteer | Allows admins to assign available volunteers to new incidents. |
| Volunteer Dashboard | Allows volunteers to check status, current task, and shifts. |
| Incident Detail | Shows assigned incident information for volunteers. |
| Mark as Resolved | Allows volunteers to close an incident after response. |
| Create Shift | Allows admins to create volunteer duty shifts. |

---

## Technology Stack

| Area | Technology |
|---|---|
| Frontend | Microsoft Power Apps Canvas App |
| Backend | SharePoint Lists |
| App Logic | Power Fx |
| Testing | Power Apps Test Studio |
| Performance Evaluation | Power Apps Monitor |
| Documentation | Confluence |
| Source Control | GitHub |
| Source Export | Power Platform CLI |
