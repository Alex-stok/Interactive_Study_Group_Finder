# Study Group Finder

**Software Engineering Project – Group 7**  
**Semester:** Spring 2025  

**Team Members:**  
Alex Stokes (Coordinator), Eric (Hyeonsu) Choi, Jainish Patel, Andy Kim,  
Duncan Bennett-Conner, Omokhudu Akhigbe  

**Faculty Advisor:** Dr. Tushara Sadasivuni  
**Course:** Software Engineering  

---

## 1. Project Overview

Study Group Finder is a full-stack web application designed to help students efficiently find, form, and manage study partnerships and study groups. The system connects students based on shared academic subjects, availability, and learning preferences, enabling both online and in-person collaboration.

Many students struggle to find academic support outside of office hours or existing social circles. This platform addresses that problem by providing a structured, searchable system for discovering compatible study partners and organizing study sessions.

The application is designed to be deployable as:
- A university-specific plug-in
- Or a standalone public web platform

---

## 2. Goals and Objectives

### Primary Objectives
- Enable students to discover compatible study partners
- Reduce friction in forming and managing study groups
- Provide scheduling, communication, and material-sharing tools
- Support both synchronous (live sessions) and asynchronous collaboration

### Secondary Objectives
- Provide admin-level moderation and oversight
- Ensure safe, respectful interaction between users
- Maintain scalability for institutional deployment

---

## 3. Key Features

### User & Profile Management
- Secure student login and authentication
- Editable user profiles including:
  - Subjects of interest
  - Study level
  - Availability
  - Learning preferences
- Profile picture and background information support

### Study Partner Discovery
- Search for partners based on:
  - Subject
  - Time availability
  - Study format (online or in-person)
  - Academic level
- Send, accept, or decline partner requests
- Block partners to prevent further interaction

### Study Groups
- Create public or private study groups
- Invite members via links or direct invitations
- Assign group leaders/admins
- Manage group membership
- Leave or dissolve groups when needed

### Scheduling & Meetings
- Schedule meetings with partners or groups
- Online meeting room creation
- Invite-only or password-protected sessions
- Join sessions via links or scheduled invites
- Calendar-based meeting management

### Study Materials
- Upload notes, files, and links
- Share materials within:
  - Study groups
  - Individual sessions
- Synchronize materials with scheduled meetings
- Notification of new materials to group members

### Communication & Notifications
- Direct messaging between study partners
- Notifications for:
  - Meeting invites
  - Messages
  - Study requests
  - Material uploads
- User-configurable notification preferences
- Temporary notification muting

### Safety & Moderation
- Report inappropriate content or users
- Admin review and enforcement
- Content moderation workflows

---

## 4. System Architecture

The system follows a **client–server architecture**.

### Frontend
- HTML
- CSS
- JavaScript
- Responsive UI for student interaction

### Backend
- Python-based web service
- REST-style API endpoints
- Business logic for:
  - Partner matching
  - Scheduling
  - Permissions
  - Notifications

### Database
- SQL-based relational database (MySQL)
- Managed using DBeaver
- Normalized schema to ensure data integrity

---

## 5. Core Use Cases (Summary)

The system supports a comprehensive set of use cases, including:

- Login and authentication
- Edit personal profile
- Find study partners
- View partner details
- Send partner requests
- Block study partners
- Create and manage study groups
- Schedule meetings
- Join live study sessions
- Upload and share study materials
- Request study help
- Manage notifications
- Report inappropriate content

Each use case includes defined:
- Inputs
- Preconditions
- Main flow
- Exception paths
- Postconditions

---

## 6. Data Design

The database supports entities such as:

- Students and profiles
- Study partners and relationships
- Study groups and memberships
- Meetings and schedules
- Notifications
- Uploaded study materials
- Blocked users

Relationships enforce:
- Partner validation
- Group membership rules
- Permission checks
- Notification routing

All tables are normalized to reduce redundancy and maintain consistency.

---

## 7. Behavioral and UML Modeling

The project includes:
- Context diagrams
- Activity diagrams
- Use case diagrams
- Class diagrams
- Sequence diagrams

These models describe:
- User interactions
- System workflows
- Backend logic
- Database interactions

They are included in the full project documentation.

---

## 8. Testing Strategy

Testing was conducted using **Pytest** and manual workflow validation.

### Covered Areas
- User authentication
- Meeting creation and joining
- Profile editing
- Partner blocking
- Notification preference updates
- Error handling
- Permission enforcement

Each system requirement is mapped to one or more test cases, ensuring traceability between requirements and implementation.

---

## 9. Documentation

The complete Software Engineering documentation includes:

- Planning and scheduling
- Requirements matrix
- Detailed use cases
- UML diagrams
- Database schema diagrams
- Test cases and results
- Architectural modeling

📄 **Full technical report:**  
See `docs/Group7_Sprint5.pdf` for complete documentation and diagrams.

---

## 10. Project Status

This project was completed as part of a Software Engineering course and demonstrates:

- Team-based development
- Requirements-driven design
- UML-based modeling
- Database-backed web application architecture
- Full software development lifecycle coverage

---

## 11. License

This project was developed for academic purposes and is not licensed for commercial use.
