# 🎓 Student Management System

A full-stack web application to manage student records, built with Spring Boot and deployed on AWS EC2.

## 🌐 Live Demo
👉 http://16.171.166.26:8080/

## 🛠️ Tech Stack
- **Backend:** Java 17, Spring Boot, Spring Data JPA, REST API
- **Database:** MariaDB (MySQL) on AWS EC2
- **Frontend:** HTML, CSS, JavaScript
- **Cloud:** AWS EC2 (Amazon Linux 2023)
- **Build Tool:** Maven

## ✨ Features
- ➕ Add new students
- 📋 View all students
- ✏️ Edit student details
- 🗑️ Delete students
- 🔄 RESTful API endpoints

## 🚀 API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/students | Get all students |
| POST | /api/students | Add new student |
| PUT | /api/students/{id} | Update student |
| DELETE | /api/students/{id} | Delete student |

## ☁️ AWS Deployment
- Deployed on **AWS EC2** (eu-north-1)
- Database: **MariaDB** running on EC2
- App runs on port **8080**

## 📦 How to Run Locally
```bash
git clone https://github.com/Sowmiya-14/student-management-system.git
cd student-management-system
mvn spring-boot:run
```

## 👩‍💻 Developer
**Sowmiya S** — Java Full Stack Developer | AWS Cloud Practitioner
- GitHub: [@Sowmiya-14](https://github.com/Sowmiya-14)
- LinkedIn: [sowmiya-s14](https://linkedin.com/in/sowmiya-s14)
