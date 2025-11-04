# 📱 ERPNext HRMS Mobile Extension (HRMS App)

An Android mobile application designed to **extend the functionalities of ERPNext HRMS**, enabling employees and managers to access HR features directly from their mobile devices.  
The app enhances ERPNext’s core HR modules by providing **a modern Material Design interface**, **real-time data sync**, and **offline-ready views** for attendance, leave, and employee profile management.

---

## 🏗️ Project Overview

This mobile application acts as a **frontend extension layer** for ERPNext HRMS.  
It connects to ERPNext backend APIs to deliver essential employee self-service and manager features through a responsive, user-friendly mobile experience.

### 🔹 Core Modules Implemented

| Module | Description | ERPNext Link |
|--------|--------------|--------------|
| **Login & Dashboard** | Authenticates ERPNext users and provides quick access to HR modules. | `/api/method/login` |
| **Leave Request** | Create and manage leave applications with attachment support. | `/api/resource/Leave Application` |
| **Leave Summary** | Fetch and display ERPNext leave balances and approvals. | `/api/resource/Leave Allocation` |
| **Attendance List** | View daily attendance with color-coded markers. | `/api/resource/Attendance` |
| **Profile Page** | Displays ERPNext employee details — personal, contact, and job data. | `/api/resource/Employee` |

---

## 🧩 Tech Stack

- **Language:** Kotlin  
- **Framework:** Android SDK (Jetpack Components)
- **UI Framework:** Material Design 3 (Material Components)
- **Architecture:** MVVM + Repository pattern (API-integrated)
- **Data Binding:** ViewBinding
- **API Integration:** Retrofit + JSON Parsing (ERPNext REST APIs)
- **Minimum SDK:** 26  
- **Target SDK:** 34  
- **IDE:** Android Studio Koala (or later)

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-org/erpnext-hrms-mobile.git
cd erpnext-hrms-mobile
