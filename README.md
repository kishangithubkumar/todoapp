<img width="990" height="827" alt="todopics" src="https://github.com/user-attachments/assets/b6f02efe-e6c5-446f-8130-b9ecc6ac2b25" />


# 📝 Todo Application

A simple and clean **Todo Application** built using **Spring Boot**, **Thymeleaf**, **Bootstrap** and **MYSql**.
This project allows users to manage daily tasks by adding, completing, and deleting tasks with a modern UI.

---

## 🚀 Features

- ➕ Add new tasks
- ✅ Mark tasks as **Completed / Pending** using checkbox toggle
- 🔁 Toggle task status
- 🗑️ Delete tasks
- 🎨 Clean and responsive UI with Bootstrap
- 👀 Visual indicators:
  - Strike-through for completed tasks
  - Status badges (Completed / Pending)
- 🧠 Follows Spring Boot MVC architecture

---

## 🖼️ UI Highlights

- Centered card-based layout
- Checkbox-based task completion
- Status badges
- Hover effects
- User-friendly design

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot  
- **Frontend:** Thymeleaf, HTML, CSS  
- **Styling:** Bootstrap 5  
- **Build Tool:** Maven  
- **Architecture:** MVC (Model–View–Controller)  
- **Server:** Embedded Tomcat  

---

## 📂 Project Structure
todoapp
│
├── .mvn / maven-wrapper
│   └── Maven wrapper files
│
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.app.todoapp
│   │   │       ├── controller
│   │   │       │   └── TaskController.java
│   │   │       ├── services
│   │   │       │   └── TaskService.java
│   │   │       ├── models
│   │   │       │   └── Task.java
│   │   │       ├── repository
│   │   │       │   └── TaskRepository.java
│   │   │       └── TodoappApplication.java
│   │   │
│   │   └── resources
│   │       ├── templates
│   │       │   └── tasks.html
│   │       ├── static
│   │       └── application.properties
│   │
│   └── test
│       └── java
│           └── com.app.todoapp
│               └── TodoappApplicationTests.java
│
├── pom.xml
├── mvnw / mvnw.cmd
├── .gitignore
└── HELP.md




