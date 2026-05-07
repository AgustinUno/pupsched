<div align="center">

# 🏢 PUPSCHED

### Facility Management System

<p>
  A prototype facility management system with WAN server access, featuring a <strong>Java desktop application</strong> and a <strong>PHP-based student portal</strong> — built at <strong>Polytechnic University of the Philippines – San Juan (PUP-SJ)</strong>.
</p>

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Archived-lightgrey?style=for-the-badge)

</div>

---

## 📋 Overview

A two-part facility management prototype built to streamline the tracking and management of facilities across locations with remote WAN access. The system consists of a **Java desktop application** for administrators and a **PHP web-based student portal** for end users.

> Built as an academic project at PUP-SJ — not intended for production use.

---

## ✨ Features

- 🌐 &nbsp;**WAN Server Access** — Access and manage facilities remotely over a wide area network
- 🏢 &nbsp;**Facility Tracking** — Monitor facility locations, capacities, and statuses
- 🔧 &nbsp;**Maintenance Scheduling** — Schedule and track maintenance tasks per facility
- 👥 &nbsp;**User Management** — Role-based access control for different user types
- 🎓 &nbsp;**Student Portal** — Web-based portal for students built with PHP and HTML/CSS
- 📊 &nbsp;**Reporting** — Generate reports on facility usage and maintenance history

---

## 🛠️ Tech Stack

| Layer         | Technology              |
|---------------|-------------------------|
| Desktop App   | Java                    |
| Student Portal| PHP / HTML / CSS        |
| Database      | MySQL                   |
| Network       | WAN (Wide Area Network) |
| IDE           | IntelliJ IDEA / VS Code |

---

## 📁 Project Structure

```
PUPSCHED/
├── DATABASE/         # SQL schema and database files
├── DESKTOP_APP/      # Java desktop application (admin)
├── LIBRARIES/        # External JAR dependencies
├── STUDENT PORTAL/   # PHP web portal for students
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Java 8 or higher
- PHP 7.x or higher
- MySQL server
- A local or WAN server (Apache/XAMPP recommended for the portal)

### Setup

**1. Clone the repository**
```bash
git clone https://github.com/AgustinUno/PUPSCHED.git
cd PUPSCHED
```

**2. Import the database**
```bash
mysql -u root -p < DATABASE/fms_database.sql
```

**3. Configure the database connection**

Update the DB credentials in `config.js` (desktop app) and in the PHP config file inside `STUDENT PORTAL/`.

**4. Run the Student Portal**

Copy the `STUDENT PORTAL/` folder to your XAMPP `htdocs` directory and start Apache. Access it at:
```
http://localhost/STUDENT PORTAL/
# or over WAN:
http://your_ip:your_port
```

**5. Run the Desktop App**

Open `DESKTOP_APP/` in IntelliJ IDEA, add the JARs from `LIBRARIES/` to the classpath, and run the main class.

---

## 🖼️ Screenshots

> 📸 _UI screenshots coming soon._

<!-- Uncomment and replace with actual screenshots once available:
<div align="center">
  <img src="screenshots/desktop-app.png" width="700" alt="Desktop Application" />
  <br/><br/>
  <img src="screenshots/student-portal.png" width="700" alt="Student Portal" />
</div>
-->

---

## 👥 Contributors

- **Justine Bautista** — [@AgustinUno](https://github.com/AgustinUno)
- **Raven Dela Cruz**
- **Regie San Juan**

---

## 🎓 Academic Context

> **Institution:** Polytechnic University of the Philippines – San Juan (PUP-SJ)
> **Type:** Academic Project
> **Languages:** Java, PHP, HTML, CSS, JavaScript

---

<div align="center">
  <sub>Made with ☕ Java and 🐘 PHP</sub>
</div>
