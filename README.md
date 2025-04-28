
# Course Management System (CMS)

**Version 1.0 | April 8, 2025**

## Overview

CMS is a full-stack, web-based Course Management System designed to streamline university academic operations for students, instructors, and administrators.  
The system supports course management, assignment tracking, enrollment, grading, and transcript generation through an intuitive and responsive interface.

Built with:
- **Frontend:** React.js
- **Backend:** Spring Boot (REST API)
- **Database:** Relational DB (JPA/Hibernate ORM)

---

## Features

### For Students:
- Enroll in and withdraw from courses
- View class schedules
- Access assignment lists and scores
- View academic transcripts
<img width="600" alt="Image" src="https://github.com/user-attachments/assets/9640602f-a0ef-4795-8947-b127c70fd921" />
<br />
<img width="600" alt="Image" src="https://github.com/user-attachments/assets/5696e5b4-92a4-42ee-8c52-3285227a6d57" />
<br />
<img width="600" alt="Image" src="https://github.com/user-attachments/assets/36223322-5115-469e-b5e3-666778a9f8c5" />
<br />
<img width="600" alt="Image" src="https://github.com/user-attachments/assets/5be4d78e-cc2c-4e7b-912f-b0396ace7655" />

### For Instructors:
- Manage course assignments (add/edit/delete)
- Grade assignments
- Enter and update final grades
- View enrolled students for assigned sections

<img width="500" alt="Image" src="https://github.com/user-attachments/assets/c42c99e5-f8f8-4726-a4db-723a650d0429" />
<br />
<img width="400" alt="Image" src="https://github.com/user-attachments/assets/241918dc-294e-419b-939f-de68a8c046ed" />
<br />
<img width="400" alt="Image" src="https://github.com/user-attachments/assets/f73ff291-135f-441b-8745-2a3e3685c03e" />

### For Administrators:
- Full user management (add, update, delete users)
- Course and section management (create, update, delete)
- Assign instructors to sections

<img width="400" alt="Image" src="https://github.com/user-attachments/assets/15ae7ca5-23ea-422c-bf6b-dfc54ebf34c9" />

---

## System Architecture

- **Frontend:**  
  React-based, role-specific user interfaces with responsive design.
  
- **Backend:**  
  RESTful API built using Spring Boot, following CRUD principles.

- **Communication:**  
  Frontend and backend communicate via secure HTTP (HTTPS preferred) with JSON-formatted data.

- **Database:**  
  Normalized relational database structure for users, courses, sections, enrollments, assignments, and grades.

---

## Key Technologies

- Java, Spring Boot (Backend)
- React.js (Frontend)
- JPA/Hibernate (ORM and persistence)
- REST API (backend communication)
- JSON (data format)
- SQL (Relational Database)

---

## Non-Functional Requirements

- **Performance:** Pages load within 1 second under normal conditions.
- **Security:** Role-based access control, password encryption, FERPA compliance.
- **Reliability:** 99.9% uptime excluding scheduled maintenance.
- **Usability:** WCAG 2.1 Accessibility Compliance.
- **Portability:** Platform-independent across major browsers and devices.
- **Maintainability:** Modular codebase for ease of updates and extensions.

---

## Getting Started

1. Clone this repository.
2. Set up the backend (Spring Boot) and frontend (React) environments.
3. Configure your database connection (MySQL or Postgres recommended).
4. Run backend and frontend servers.
5. Access the application in your browser at `http://localhost:3000` (default).
