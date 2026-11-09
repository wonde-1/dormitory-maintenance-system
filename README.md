# 🏢 Dormitory Maintenance Reporting System (DMRS)

> A modern, web-based facility issue reporting and maintenance management platform designed for university campuses.

---

## 📌 1. Project Overview & Problem Statement

In many university campuses, dormitory maintenance issue reporting (such as plumbing leaks, electrical failures, broken windows, and damaged locks) relies entirely on manual logbooks and physical paperwork. This traditional method leads to:
* **Lost or forgotten complaints** due to unorganized records.
* **Slow resolution time** because technicians are not notified promptly.
* **Lack of transparency** where students cannot track the status of their repair requests.
* **Poor resource management** for dormitory administrators.

**The Solution:**  
The **Dormitory Maintenance Reporting System (DMRS)** digitizes the entire lifecycle of maintenance requests—from instant issue reporting by students, to automated dispatching to technicians, and final verification by proctors/administrators.

---

## 👥 2. System Actors & Key Features

### 🎓 1. Students (End Users)
* **Authentication:** Secure sign-up/login using student ID.
* **Submit Issues:** Report room/block maintenance problems with details (category, description, priority, and optional photos).
* **Real-time Status Tracking:** View request states: Pending ➔ In Progress ➔ Resolved.
* **Issue History & Feedback:** View previously resolved requests and rate the quality of service.

### 📋 2. Proctors / Dormitory Managers
* **Request Verification:** Review and approve incoming student tickets.
* **Technician Assignment:** Assign maintenance tasks to specific technicians (e.g., Electrician, Plumber).
* **Block Oversight:** Monitor ongoing issues across specific dormitory blocks.

### 🔧 3. Technicians (Maintenance Staff)
* **Assigned Work Orders:** Dedicated dashboard to view assigned tasks and urgency levels.
* **Status Updates:** Update ticket status to In Progress and Resolved upon completion.
* **Work Logs:** Add resolution notes or report required spare parts.

### 📊 4. System Administrator
* **Analytics Dashboard:** Visual metrics on average repair times, recurring issues, and technician workload.
* **User Management:** Manage student, technician, and proctor accounts.
* **Block & Facility Management:** Add and update campus dormitory structures.

---

## 🛠️ 3. Proposed Technology Stack

* **Frontend:** React.js / Vite, Tailwind CSS
* **Backend:** Node.js (Express.js) / RESTful API
* **Database:** PostgreSQL or MongoDB
* **Authentication:** JWT (JSON Web Tokens)
* **Version Control:** Git & GitHub

---

## 🔄 4. Software Engineering Methodology (SDLC)

This project strictly follows the **Agile (Scrum)** software development lifecycle:
* **Iterative Sprints:** Development is split into focused 2-week iterations.
* **Requirements Modeling:** Full UML design (Use Case, Sequence, Class, and ER diagrams).
* **Continuous Integration:** Regular commits, branch management, and automated testing.

---

## 🗺️ 5. Project Development Phases

- [x] **Sprint 1: Inception & Setup** (Problem Definition, Scope, Git Setup)
- [ ] **Sprint 2: Requirements Analysis** (SRS Documentation & User Stories)
- [ ] **Sprint 3: System Modeling & Architecture** (UML Diagrams & DB Schema)
- [ ] **Sprint 4: Core Backend Development** (REST APIs & Database Integration)
- [ ] **Sprint 5: Frontend Interface & State Management**
- [ ] **Sprint 6: Quality Assurance & Testing** (Unit & Integration Tests)
- [ ] **Sprint 7: Final Deployment & Documentation**

---

## ⚙️ 6. Local Setup & Installation (Upcoming)

* Clone the repository:
  git clone https://github.com/wonde-1/dormitory-maintenance-system.git

* Navigate into the project directory:
  cd dormitory-maintenance-system

---

## 👨‍💻 Author

* **Name:** Yalelet Melkamu
* **Department:** Department of Computer Science (3rd Year)
* **Institution:** Wollo University (Kombolcha Institute of Technology - KIOT)

---
