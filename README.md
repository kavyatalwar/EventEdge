# 🚀 EventEdge – Intelligent Event Management System

## 📌 Overview
**EventEdge** is a full-stack web application designed to modernize and automate event management workflows within institutions and organizations. It replaces fragmented manual coordination with a centralized, secure, and scalable system.

The platform enables event organizers to efficiently manage the entire lifecycle of events — from creation and team structuring to scheduling and communication — while providing administrators with complete system visibility and control.

---

## 🎯 Problem Statement
Traditional event management systems often face:
* Lack of centralized coordination  
* Inefficient communication across teams  
* Manual data handling and tracking  
* Limited transparency and accountability  
* Time-consuming reporting processes  

---

## 💡 Solution
EventEdge addresses these issues by offering:
* **Centralized Platform:** A single source of truth for all event data.
* **Automated Workflows:** Communication and notification triggers.
* **Structured Management:** Clear hierarchy for committees and teams.
* **Real-time Monitoring:** Live tracking for administrators.
* **Data Insights:** Robust reporting and filtering tools.

---

## 🏗️ System Architecture
EventEdge follows a modular full-stack architecture:
* **Frontend Layer:** HTML, CSS, Bootstrap  
* **Backend Layer:** Flask (Python)  
* **Database Layer:** SQLite  
* **Service Layer:** * Email Service (Flask-Mail)  
    * PDF Generation (ReportLab)  

---

## 👥 User Roles & Permissions

### 👤 Event Organizer
* Create and manage events  
* Add core committee members  
* Schedule meetings  
* Send automated notifications  

### 🛠️ Administrator
* Full system access and oversight
* Monitor all events and activity logs  
* Advanced filtering and search  
* Generate downloadable PDF reports  

---

## ⚙️ Core Features

### 🔐 Authentication & Security
* Secure user registration and login  
* Password hashing using **Werkzeug** * Role-based access control (RBAC)  
* Protected routes via **Flask-Login** ### 📅 Lifecycle Management
* Detailed event metadata: Name, Department, Date, Faculty Head.
* **Committee Management:** Store member roles, emails, and contact details.
* **Meeting Scheduling:** Timeline storage with integration links (Google Meet, WhatsApp).

### 📧 Automation & Reporting
* **Email Notifications:** Structured HTML emails sent to all committee members.
* **Activity Logging:** Audit trails for logins, creations, and updates.
* **PDF Generation:** Professional, structured event reports for stakeholders.

---

## 🗄️ Database Design

| Table Name | Description |
| :--- | :--- |
| **User** | Credentials, roles, and profile info |
| **Event** | Core event metadata and ownership |
| **EventMember** | Committee roles and contact details |
| **ActivityLog** | System-wide audit logs and timestamps |

---

## 🧰 Tech Stack
* **Backend:** Python, Flask
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
* **Database:** SQLite (SQLAlchemy ORM)
* **Tools:** Flask-Mail, ReportLab, python-dotenv, Git

---

## 🚀 Getting Started

### 🔧 Prerequisites
* Python 3.8+
* pip (Python package manager)

### ⚙️ Installation & Setup
1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/eventedge.git](https://github.com/your-username/eventedge.git)
   cd eventedge
   ```
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Environment Setup**
   Create a `.env` file in the root directory:
   ```env
   SECRET_KEY=your_secret_key
   MAIL_USERNAME=your_email@gmail.com
   MAIL_PASSWORD=your_app_password
   ```
4. **Run the Application**
   ```bash
   python app.py
   ```
   Access at: `http://127.0.0.1:5000`

---

## 📈 Future Enhancements
* 📊 **Advanced Analytics:** Visual dashboard for event trends.
* 📱 **Mobile App:** Integration for on-the-go management.
* 🎟️ **Participant Module:** Registration and ticketing system.
* 📍 **Attendance:** QR-code based tracking.
* ☁️ **Cloud Migration:** Transition to PostgreSQL/AWS.

---

## ⭐ Author
**Kavya Talwar** *B.Sc. (Mathematics, Computer Science, Statistics)* 

**Aspiring Data Analyst**

---

## 🏁 Conclusion
EventEdge provides a scalable and efficient solution for managing events through automation and structured workflows. It significantly reduces manual effort, improves coordination, and enhances communication, making it a reliable tool for any modern organization.
