# D424 – Software Engineering Task 3

## Application Name: WGU Term Tracker  
**Student:** Eric Day - 011579679

---

## Overview

The **WGU Term Tracker** is a mobile application designed for students and instructors to manage academic terms, courses, and assessments. The application provides role-based functionality, offering specific features for instructors and students.

---

## Features

### 🔐 User Registration and Login
- Users can register with a **username** and **password**.
- During registration, users must indicate if they are a **student** or **instructor**.
- Existing users can log in with their credentials.

---

### 👨‍🏫 Instructor Features
- **Add, edit, and delete**:
  - Terms
  - Courses
  - Assessments
- Mobile-friendly form inputs:
  - Dropdown lists
  - Date pickers
  - Textboxes
- View courses within each term and assign assessments.
- Manage instructor details for each course:
  - Name
  - Phone number
  - Email address
- Add multi-line course **notes**.
- Access to all **student** features.

---

### 🎓 Student Features
- View a list of **terms**.
- Tap a term to view **courses**.
- Tap a course to view:
  - Start and end dates
  - Instructor contact info
  - Course notes
- **Share notes** via native mobile sharing (text, email, etc.).
- Toggle **notifications** for course start and end dates.

---

### 📊 Reporting (Instructors Only)
- Generate a report listing **terms and courses**.
- Filterable by **date range**.

---

## 📱 UI and Platform Considerations
- Designed with **mobile usability** in mind:
  - Standard Android controls (dropdowns, date pickers, textboxes)
  - Proper font sizing
  - Tap-friendly UI elements

---

## 💾 Data and Security
- **SQLite database** used for storing:
  - Terms
  - Courses
  - Assessments
  - User data
- User **passwords are encrypted** in the database.

---

## 📦 Download

[Download APK](app.apk)
