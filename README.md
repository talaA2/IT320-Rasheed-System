# IT320-Rasheed-System

## Overview
Rasheed is a web-based reporting system designed to help residents report water and electricity issues in their communities. The system allows residents to submit reports, track report status, receive notifications, and view reward points and badges. It also provides an admin interface for reviewing reports and updating their status.

## Project Objectives
- Provide a unified platform for reporting water and electricity issues.
- Improve transparency through report tracking.
- Notify residents about report status updates.
- Encourage community participation through a rewards system.
- Support administrators in managing and processing submitted reports.

## Main Features

### Resident Features
- Register and log in securely.
- Submit water or electricity reports.
- Add report details such as description, location, severity, and optional image.
- View submitted reports.
- Track report status.
- Receive notifications.
- View accumulated points and earned badges.

### Admin Features
- Log in as an administrator.
- View submitted reports.
- Open report details.
- Update report status.
- Trigger notifications and reward points when reports are completed.

## Technologies Used
- HTML
- CSS
- JavaScript
- PHP
- MySQL
- phpMyAdmin
- MAMP
- GitHub

## Database
The system uses a MySQL database named rasheed.

Main tables:
- user
- resident
- report
- notification

## Project Structure
```text
IT320-Rasheed-System/
│
├── src/
│   ├── index.php
│   ├── login.php
│   ├── register.php
│   ├── process_login.php
│   ├── process_register.php
│   ├── logout.php
│   ├── main.php
│   ├── AddReport.php
│   ├── MyReports.php
│   ├── report-det.php
│   ├── Rewards.php
│   ├── Notifications.php
│   ├── Admin.php
│   ├── status.php
│   ├── db.php
│   ├── style.css
│   ├── images/
│   └── uploads/
│
├── docs/
│   └── Phase4_Report.docx
│
├── database/
│   └── rasheed.sql
│
├── AUTHORS.md
└── README.md
