# 🎓 Educational Organisation Management System (ServiceNow)

## 📌 Overview
The **Educational Organisation Management System** is a custom ServiceNow application designed to streamline and automate administrative tasks within educational institutions.  

It enables efficient handling of:
- Student admissions  
- Teacher and student data management  
- Academic progress tracking  
- Section/class allocations  

This project demonstrates how ServiceNow’s low-code/no-code platform can be customized to build real-world solutions for the education domain.  

---

## 🎯 Objectives
- Automate the student admission process.  
- Maintain accurate records of students and their academic progress.  
- Reduce manual errors and improve efficiency.  
- Provide administrators with better visibility and control.  

---

## ✨ Features Implemented

### 🔹 Admission Management
- Tracks the **full lifecycle** of a student’s admission.  
- Status options: `New`, `In Progress`, `Joined`, `Rejected`, `Closed`, `Cancelled`.  

### 🔹 Student Progress Tracking
- Record **exam results and academic performance**.  
- View student progress across terms.  

### 🔹 Section Management
- Organize students into **sections/classes**.  
- Simplify group allocations for teachers.  

---

## 🛠️ Technical Implementation
- **Platform:** ServiceNow (Tokyo release or later)  
- **Development Tool:** ServiceNow Studio  
- **Customization Includes:**  
  - Tables: Admissions, Student Progress, Sections  
  - Form Layouts & Lists for data entry and tracking  
  - Workflows for admission lifecycle automation  
  - Number Maintenance for unique IDs  
  - Client Scripts for validation  
  - UI Policies for enhanced form behavior  

---

## 📈 Project Flow
1. Instance setup  
2. Update set creation  
3. Custom tables for Admissions, Students, Sections  
4. Form layouts & design  
5. Number maintenance for IDs  
6. Process flows for admissions  
7. Client scripts for validations  
8. Output verification with test data  

---

## ⚙️ Installation Guide
1. Go to **System Update Sets → Retrieved Update Sets** in your ServiceNow instance.  
2. Click **Import Update Set from XML**.  
3. Upload: `Educational_Organization_update_set.xml`.  
4. Preview update set and resolve conflicts.  
5. Commit update set to apply changes.  

---

## 🚀 Usage Guide
- Navigate to **Admissions Table** → Add/manage admission records.  
- Navigate to **Student Progress Table** → Update exam results and track performance.  
- Navigate to **Sections Table** → Assign students to sections/classes.  

---

## 🔮 Future Enhancements
- Self-service **Student Admission Portal**.  
- **Email Notifications** for admission status updates.  
- Automated **Progress Report Generation**.  
- **Role-based access control** (Admin, Teacher, Student).  

---

## 📸 Screenshots
*(Add screenshots here from your project implementation, e.g., forms, tables, workflows, dashboards.)*  

---

## 📦 Deliverables
- **XML File** → Update set export  
- **Screenshots** → Project proof of implementation  
- **Documentation** → Project report (this README + detailed report)  
- **Demo Video** → Walkthrough of the application  

---

## ✅ Conclusion
This project showcases the ability to leverage ServiceNow to build a **custom Educational Management System**. By automating core processes such as **admissions, student progress, and section management**, institutions can reduce manual workload, improve accuracy, and enhance efficiency.  

---
👩‍💻 *Developed as part of ServiceNow Project – Educational Organisation Using ServiceNow*  
