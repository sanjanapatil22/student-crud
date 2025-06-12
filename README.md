# 📚 Student Management System — *Beginner-Friendly Java Spring Boot Project*

This is a **complete beginner-friendly** web application built with **Java, Spring Boot, Thymeleaf**, and an in-memory **H2 database**.

It teaches the **basics of CRUD (Create, Read, Update, Delete)** operations with clean code, minimal setup, and a simple UI.

---

## 🚀 Features

- ✅ **Add** student with Name, Roll No, Semester, CGPA, and Phone Number  
- 🗑️ **Delete** student using Roll Number  
- 👀 **Display all** students or **view one** by Roll Number  
- 🖥️ Clean and minimal frontend using **HTML + CSS + Thymeleaf**  
- 🧠 Uses **H2 In-Memory Database** (no database installation needed)

---

## 🧑‍🎓 Who Is This For?

This project is designed **especially for absolute beginners** who want to:
- Learn Spring Boot without feeling overwhelmed
- Understand how backend and frontend connect
- Build a small working project for portfolios or assignments
- Practice using Thymeleaf templates with form handling

---

## 🛠️ Tech Stack

| Layer        | Technology           |
|--------------|----------------------|
| Backend      | Java + Spring Boot   |
| Frontend     | Thymeleaf + HTML/CSS |
| Database     | H2 In-Memory DB      |
| Build Tool   | Maven                |
| IDE Tested   | IntelliJ IDEA        |

## 📂 Project Structure

student-crud/
│
├── src/
│   ├── main/
│   │   ├── java/com/example/studentcrud/
│   │   │   ├── controller/       # Web endpoints
│   │   │   ├── model/            # Student class
│   │   │   ├── repository/       # JPA interface
│   │   │   └── StudentCrudApplication.java
│   │   └── resources/
│   │       ├── templates/        # Thymeleaf HTML pages
│   │       └── application.properties
│
├── pom.xml
└── README.md

---

## 💻 How to Run (Using IntelliJ IDEA)

1. **Clone or Download** the project:
   ```bash
   git clone https://github.com/your-username/student-crud.git

2.	Open the folder in IntelliJ IDEA
	3.	Let Maven install dependencies automatically.
	4.	Run the file StudentCrudApplication.java (your main class)
	5.	Open your browser and visit:
👉 http://localhost:8080

🧪 Dependencies Used
	•	spring-boot-starter-web
	•	spring-boot-starter-thymeleaf
	•	spring-boot-starter-data-jpa
	•	com.h2database:h2

⸻

📌 Notes
	•	Data is stored temporarily using an in-memory H2 database.
	•	To use MySQL/PostgreSQL in the future, update your application.properties.

give markdown code
