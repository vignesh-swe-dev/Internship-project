# Thinkinfo Expert Solutions — Workforce & Intern Management System

A comprehensive multi-role enterprise workforce and intern management platform featuring a high-contrast dark cyber security operations center (SOC) aesthetic, dynamic Canvas-rendered metrics, automated document generation, and role-based operational workflows.

---

## 🏛️ Project Architecture & Modules

The platform is divided into four dedicated role modules:

### 1. 🏢 CEO Portal (`Ceo Main/`)
Executive suite for high-level enterprise oversight and decision-making:
- **CEO Dashboard (`ceo-home-dashboard.html`)**: Real-time KPI statistics counters, attendance donut charts, and department employee distribution bar charts.
- **Organization Hierarchy Management**: Add and manage departments (`add-department.html`, `manage-department.html`) and divisions (`add-division.html`, `manage-division.html`).
- **Personnel Administration**: Directory listing and records for employees, managers, and interns (`ceo-manage-employees.html`, `ceo-manage-managers.html`, `manage-interns.html`).
- **Leave & Attendance Oversight**: Company-wide attendance review (`view_attendance.html`) and leave authorization (`employee-leave.html`, `manager-leave.html`).
- **Broadcast Notifications**: Role-targeted communication pipelines (`notify-employee.html`, `notify_manager.html`, `notify-intern.html`).
- **Feedback Loops**: Multi-tier employee and manager review channels (`ceo-employee-feedback.html`, `manager-feedback.html`).

### 2. 👔 Manager Portal (`Manager Main/`)
Operational hub for team leads, supervisors, and HR administrators:
- **Manager Dashboard (`manager-home.html`)**: Team presence metrics and action queues.
- **Talent Acquisition & Onboarding**: Add employees and interns (`manager-add-employee.html`, `manager-add-intern.html`).
- **Attendance & Leave Control**: Daily attendance capture (`manager-take-attendance.html`), attendance verification (`manager-view-attendance.html`), and approval workflows (`attendance-approval.html`).
- **Compensation Management**: Salary allocation and revisions (`manager-add-salary.html`, `manager-edit-salary.html`).
- **Document & Certificate Generation**: Automated creation of intern offer letters, employee offer letters, internship completion certificates (with AICTE and MSME compliance logos), and experience letters.

### 3. 💼 Employee Portal (`Employee Main/`)
Dedicated workspace for regular enterprise staff:
- **Employee Hub (`employee-home.html`)**: Task shortcuts and personal activity summaries.
- **Attendance & Leave**: Monthly punch card logs (`employee-attendance.html`) and leave requests (`employee-apply-leave.html`).
- **Payroll & Documents**: View pay slips (`employee-view-salary.html`) and generate official relieving letters (`relieving-letter-TES.html`).
- **Feedback & Notifications**: Internal alerts and anonymous feedback submission.

### 4. 🎓 Intern Portal (`Intern Main/`)
Streamlined portal tailored for internship trainees:
- **Intern Hub (`intern-home.html`)**: Project milestones, attendance records (`intern-attendance.html`), leave applications (`intern-apply-leave.html`), and mentor feedback channels (`intern-feedback.html`).

---

## 🎨 Visual Identity & Design System

- **Design Aesthetic**: SOC (Security Operations Centre) dark cyber theme.
- **Palette**: Deep noir (`#020608`), midnight navy (`#0a0f18`), neon cyan (`#0ef`), status green (`#00e676`), warning amber (`#ffaa00`), and crimson alert (`#ff3a4a`).
- **Animations**: Ambient Matrix digital rain rendered via HTML5 Canvas and smooth CSS transitions.

---

## 🚀 Getting Started

1. Clone or download the repository:
   ```bash
   git clone https://github.com/vignesh-swe-dev/Internship-project.git
   ```
2. Open `index.html` in any modern web browser or serve via a lightweight HTTP server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```
3. Navigate between roles using the role gateway or direct portal entry points.

---

## 📄 License
Thinkinfo Expert Solutions. All rights reserved.
