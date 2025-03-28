# **Campus Attendance Tracker**

## **Group Members**

| Name              | ID.NO         | Section |  
|-------------------|--------------|----------|  
| Tsedeke Techane   | UGR/6036/15   | 2       |  
| Anat Esayas       | UGR/5002/15   | 3       |  
| Kalkidan Semre    | UGR/9847/15   | 1       |  
| Biruk Seyoum      | UGR/8267/15   | 4       |  
| Nuel Mezemir      | UGR/9233/15   | 1       |  

## **Project Overview**

**Project Name:** Campus Attendance Tracker

**Objective:**  
The **Campus Attendance Tracker** system is designed to streamline the attendance marking process for students and teachers on campus. It automates the process of recording, managing, and analyzing attendance data for both students and teachers, improving academic tracking and management.

**Scope:**  
The system will provide **teachers** with the ability to create classes, generate QR codes for attendance tracking, and manage student data. **Students** will be able to scan QR codes to mark their attendance and view their attendance history, including any excused absences.

---

## **Features**

### **For Unregistered Users**
- **View class details and available courses**.
- Cannot mark attendance or access attendance reports.

### **For Registered Students**
- **Sign Up** to create an account and log in.
- **Scan QR codes** generated by teachers to mark attendance.
- View **personal attendance history**: Present %, Absent, and Excused.
- Submit **excuse requests** for missed classes.
- View **attendance status** (current month, semester, or year).
  
### **For Teachers**
- **Sign Up** to create an account and log in.
- **Create and manage classes** (add students, set class details).
- **Generate QR codes** for each class session for attendance marking.
- **Approve or reject student excuses** for missed classes.
- **Mark attendance manually** for students unable to scan QR codes.
- View **attendance reports** for all students in their classes.
- View **individual student profiles** with detailed attendance history.
  
---

## **Technologies Used**

### **Frontend**
- **Flutter**: For building a responsive mobile app interface for both students and teachers.
- **Dart**: The programming language used for Flutter development.

### **Backend**
- **Node.js**: JavaScript runtime environment used for building server-side logic.
- **Express.js**: Web framework used to build REST APIs for handling attendance-related services.
  
### **Database**
- **MongoDB**: NoSQL database used to store user details, class data, attendance records, and other necessary information.

### **Authentication**
- **JWT (JSON Web Tokens)**: Custom JWT-based token authentication system for user login and authorization.

---

## **Installation and Setup**

### **Prerequisites**
- **Node.js** (v16 or higher)
- **MongoDB** instance (local)
- **Git**
  
### **Steps**
1. **Clone the repository**:
   ```bash
   git clone https://github.com/tsedeke-techane/Campus_Attendance_Tracker.git
   cd campus-attendance-tracker
