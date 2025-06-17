# FAB ERP System

A dynamic enterprise-grade web application for managing frequency allocation workflows. Designed for use by admins, field agents, and department stakeholders, FAB streamlines the application and review process for frequency licenses with modular, real-time interfaces and automated multi-role workflows.

---

## 🌟 Key Features

### 🧠 Dynamic JSON-Based Forms
- All application forms are rendered dynamically based on JSON schema data.
- Field validation, conditional rendering, and layout rules are handled client-side using flexible form engines.
- New forms or fields can be introduced without code changes—just update the JSON.

### 📋 Multi-Step Frequency Application Process
- Applicants submit structured frequency allocation requests.
- Requests are routed through a multi-step approval pipeline involving multiple departments (technical, legal, administrative).
- Each user role sees only the relevant stages, permissions, and data.

### 📄 Automated Document Generation (Proposal Certificate)
- Upon approval of an application, the system auto-generates official documents such as:
  - **Proposal Certificates**
  - **Approval Letters**
  - **Departmental Memos**
- These are dynamically created using application data and workflow metadata, then stored and linked for future reference or download.

### 📍 Live Location Tracking
- Real-time map integration with **Mapbox GL JS** for visualizing the location of field agents or deployment sites.
- Filtering and zooming capabilities built-in.

### 📊 Admin Dashboards & Reports
- Admins can view application statistics, frequency usage, and user activity.
- Data tables are fully searchable and paginated, with options for export/download.

### 🔐 Role-Based Access Control (RBAC)
- Permissions and access levels are controlled via custom RBAC logic.
- Different dashboards and workflows are shown based on user roles: Agent, Reviewer, Admin, Department Head, etc.

### 🔄 Workflow Automation
- Automatic status transitions based on actions (submit, review, reject, approve).
- Notification system alerts users about pending tasks or decisions.
- Document generation and email notifications are triggered at key workflow points.

### 💡 UX and Performance
- Fully responsive, mobile-friendly layout using **Tailwind CSS** and **React**.
- Fast load times, dynamic routing, and smooth transitions using React Router.
- Modular code structure with reusable components and service layers.

---

## 🔧 Tech Stack

| Category         | Technologies                     |
|------------------|----------------------------------|
| Frontend         | React, TypeScript, Tailwind CSS |
| State Management | Context API / Redux             |
| Forms Engine     | Custom JSON-based renderer      |
| API Integration  | REST APIs                       |
| Mapping          | Mapbox GL JS                    |
| Access Control   | Custom RBAC Middleware          |
| Testing          | Jest, React Testing Library (planned) |
| Deployment       | Dockerized frontend + CI/CD     |

---

## 📸 Screenshots/Video
here is complete demo of FAB Portal
https://youtu.be/RggjTea785U


---

## 🛡️ Disclaimer

This project was developed in a professional setting. All sensitive data, credentials, and internal business logic have been removed or redacted. Screenshots and demonstrations are shared for portfolio purposes only and comply with non-disclosure policies.

---

## 👨‍💻 Developed By

**Ahmad Anis**  
Frontend Engineer  
📍 Germany  
📫 theahmdanis1@gmail.com | [LinkedIn](https://linkedin.com/in/theahmadanis)
