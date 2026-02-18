# TaskFlow – Collaborative Project Management System

## 1. Problem Statement
Teams struggle to manage projects, tasks, deadlines, and collaboration in a structured way.
Existing tools are either too complex or lack proper backend structure for learning system design.

## 2. Solution
TaskFlow is a Full Stack Project Management System where teams can:
- Create organizations
- Create projects
- Create and assign tasks
- Track status (TODO, IN_PROGRESS, DONE)
- Comment on tasks
- Manage roles (Admin, Manager, Member)

## 3. Scope

### Core Features
- User Authentication (JWT-based)
- Organization & Project Management
- Task CRUD operations
- Task Assignment
- Comments on tasks
- Role-based access control
- Activity logging

### Future Scope
- Notifications
- File attachments
- Kanban board UI
- Email reminders

## 4. Tech Stack
Backend:
- Spring Boot / Node.js (Express)
- PostgreSQL
- JWT Authentication
- Layered Architecture (Controller → Service → Repository)

Frontend:
- React
- REST API integration

## 5. System Design Focus
- OOP principles
- Clean architecture
- Repository pattern
- Service layer abstraction
- DTO pattern
- Role-based authorization
