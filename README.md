## 📘 Project Overview

This project presents a **Computerized Maintenance Management System (CMMS)** designed to optimize warehouse maintenance workflows through automation, predictive scheduling, and efficient data management.  
Our client works at a retail logistics and supply chain maintenance facility (Canadian Tire GTA DC), where delays in scheduling repairs and part ordering were leading to inefficiencies and financial loss.  

The goal was to design a **comprehensive CMMS** that integrates with existing enterprise software (Kronos) to:
- Automate maintenance scheduling
- Track work orders and machine status
- Manage inventory and parts
- Optimize resource allocation using employee data

---

## 🧩 Key Features

### 🔹 Front-End (User Interface)
- Built with **Vue.js**, **JavaScript**, **HTML5**, and **CSS**
- AODA-compliant interface for accessibility (AA level)
- Distinct UIs for **tablet users** (maintenance workers) and **PC users** (supervisors)
- Real-time tracking of:
  - Work orders and completion time
  - Maintenance schedules
  - Inventory levels and notifications
  - KPI dashboards and performance data

### 🔹 Back-End (Automation & Logic)
- Developed using **Java (Spring Boot Framework)**
- Integrates with **Kronos API** for employee scheduling and data synchronization
- Predictive maintenance using historical repair data
- Automated notifications for:
  - Low inventory
  - Overdue maintenance
  - Equipment inefficiencies

### 🔹 Database & Data Management
- **MySQL** relational database following **MVC architecture**
- Stores user roles, equipment data, inventory, and maintenance records
- Implements **Role-Based Access Control (RBAC)** and encrypted **HTTPS** communication

### 🔹 Security & Privacy
- Encrypted API communication to secure data transfers  
- Multi-level access controls for employees, planners, and supervisors  
- Compliance with **PIPEDA** and **AODA** standards

---

## 🧱 System Architecture

The CMMS system architecture includes:
1. **User Interface Layer** – For PC and tablet users  
2. **Backend Service Layer** – Java Spring Boot application managing business logic and APIs  
3. **Database Layer** – MySQL for data storage and relationships  
4. **API Integration** – Secure Kronos API communication  
5. **Hardware Integration** – Tablets for field workers and servers for system hosting  

![System Architecture Diagram](docs/system_architecture.png) *(placeholder for diagram)*

---

## 🗓️ Implementation Plan

| Phase | Duration | Key Objectives |
|-------|-----------|----------------|
| **Phase 1: Scope & Planning** | Weeks 1–4 | Define project scope, architecture, and requirements |
| **Phase 2: Front-End UI Design** | Weeks 5–9 | Create UI prototypes, ensure AODA compliance |
| **Phase 3: Backend & API Development** | Weeks 9–20 | Implement logic, database integration, and automation |
| **Phase 4: Testing & Deployment** | Weeks 20–34 | Conduct system validation, training, and optimization |

---

## ⚙️ Technologies Used

| Category | Tools / Languages |
|-----------|-------------------|
| **Frontend** | Vue.js, HTML5, CSS, JavaScript |
| **Backend** | Java (Spring Boot) |
| **Database** | MySQL |
| **API Integration** | Kronos API, REST, JSON |
| **Security** | HTTPS Encryption, RBAC |
| **Version Control** | Git, GitHub |

---

## 🔐 Ethical, Social, and Environmental Considerations
- **Security:** Protects sensitive employee and asset data  
- **Privacy:** Encrypted communication and multi-factor authentication  
- **Equity:** AODA accessibility compliance and UI customization for all user types  
- **Sustainability:** Reduces resource waste and downtime through predictive maintenance  
- **Ethics:** Promotes fair work distribution through data-driven automation  

---

## 📈 Outcomes

Our CMMS design improves:
- **Scheduling efficiency** and reduces downtime  
- **Inventory tracking accuracy** with predictive restocking alerts  
- **Employee productivity** via automated assignment and KPI feedback  
- **Data transparency** through real-time dashboards and secure logging  

---

## 🧑‍💻 Contributors

| Name | Role |
|------|------|
| **Eric Liu** | Requirements Analysis, Design Documentation, Security Analysis |
| **Daniel Jegenjan** | Solution Design, Implementation Plan, Report Writing |
| **Maruf Choudhury** | Backend Integration, Security & Automation |
| **Rayyan Khan** | UI Design, Accessibility, Ethical Impact |
| **Sterling Joseph** | Frontend Integration, Testing, Communication Analysis |

---

## 📄 License
This project was developed as part of **CPS412: Software Engineering Fundamentals** at Toronto Metropolitan University.  
All intellectual property belongs jointly to the authors for academic purposes.

---

## 🧠 Learnings
Through this project, we gained experience in:
- Full-stack design (frontend, backend, database integration)
- System modeling and requirement analysis
- Secure API communication
- Accessibility compliance (AODA)
- Collaborative software engineering in team-based environments
