# EduPro Hub
### A Collaborative Students  Project Management Platform for Uganda Institute of Information and Communications Technology.

## Project Overview

EduPro Hub is a web-based Final Year Project Management System developed to improve the management, monitoring, and collaboration of final year student projects at the Uganda Institute of Information and Communications Technology (UICT), Nakawa Campus.

The system provides a centralized platform where students, supervisors, and administrators can collaborate throughout the entire project lifecycle, from proposal submission to final project approval.

---

# Problem Statement

The current management of final year projects in many higher institutions, including UICT, relies heavily on manual processes and fragmented communication channels. These methods present several challenges, including:

- Loss of project documents.
- Delayed supervisor feedback.
- Poor communication between students and supervisors.
- Difficulty in tracking project progress.
- Lack of centralized project storage.
- Time-consuming administrative work.
- Difficulty monitoring project milestones and deadlines.
- Inefficient approval and evaluation processes.

These challenges reduce efficiency, increase delays, and make project management difficult for students, supervisors, and administrators.

---

# Proposed Solution

EduPro Hub addresses these challenges by providing an integrated online platform that enables users to manage the entire final year project process digitally.

The system provides:

- Secure user authentication.
- Student project proposal submission.
- Supervisor review and approval.
- Online feedback and comments.
- Progress tracking dashboard.
- Project milestone monitoring.
- File upload and document management.
- Project status monitoring.
- Administrator management dashboard.
- Notification system.
- Centralized project repository.
- Report generation.

---

# Installation Guide

## Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/eduprohub.git
```

---

## Step 2: Move the Project

Copy the project folder into the XAMPP htdocs directory.

Example:

```
C:\xampp\htdocs\EduProHub
```

---

## Step 3: Start XAMPP

Open XAMPP Control Panel and start:

- Apache
- MySQL

---

## Step 4: Create the Database

Open phpMyAdmin.

```
http://localhost/phpmyadmin
```

Create a new database named:

```
eduprohub
```

---

## Step 5: Import the Database

Select the database.

Click **Import**.

Choose:

```
eduprohub.sql
```

Click **Go**.

---

## Step 6: Configure Database Connection

Open:

```
config/database.php
```

Update the credentials if necessary.

Example:

```php
<?php

$host = "localhost";
$user = "root";
$password = "";
$database = "eduprohub";

$conn = mysqli_connect($host, $user, $password, $database);

if(!$conn){
    die("Connection Failed: ".mysqli_connect_error());
}

?>
```

---

## Step 7: Run the Project

Open your browser.

Navigate to:

```
http://localhost/EduProHub
```

---

# Default Login Credentials

## Administrator

Email

```
admin@eduprohub.com
```

Password

```
admin123
```

---

## Supervisor

Email

```
supervisor@eduprohub.com
```

Password

```
supervisor123
```

---

## Student

Email

```
student@eduprohub.com
```

Password

```
student123
```


# Contribution

Contributions are welcome.

To contribute:

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature/new-feature
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push your branch.

```bash
git push origin feature/new-feature
```

5. Open a Pull Request.

---
