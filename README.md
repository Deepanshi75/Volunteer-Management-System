# Volunteer Management System - Java + JDBC(Web App)
 Volunteer Management System is a web-based application designed to simplify the process of managing volunteers for college events. 
 The system automatically matches volunteers to suitable event tasks based on their skills, interests, and availability.
## 1. Project Overview
  The project’s core goal is to automate volunteer assignment and management by allowing:
### Volunteers to:
  - Register & Login
  - Select skills (Photography, Anchoring, Decoration, etc.)
  - Enter available dates & interests
  - View events and apply for tasks
### Event Organizers/Admins to:
  - Create Events & Tasks
  - View volunteer applicants
  - Approve or Reject applications
  - Auto-suggestion of best volunteers
## 2.Project Structure

```
VolunteerManagementSystem/
│
├─ frontend/                     # HTML, CSS, JavaScript-based UI
│   ├─ css/                      # Stylesheets
│   ├─ js/                       # Scripts & form validations
│   └─ *.html                    # Web pages (Login, Register, Events, etc.)
│
├─ backend/                      # Java backend + business logic
│   ├─ controller/               # Request handling & Servlets (if used)
│   ├─ dao/                      # Database operations (JDBC CRUD)
│   ├─ model/                    # Java classes (Event, Volunteer, Application)
│   └─ util/                     # DB connection and helpers
│
└─ database/
    └─ volunteer_db.sql          # MySQL tables & sample data
```




    
