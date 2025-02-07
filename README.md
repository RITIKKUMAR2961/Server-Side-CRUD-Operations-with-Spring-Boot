# Student Management API with Spring Boot

## 📌 Overview
This is a **CRUD (Create, Read, Update, Delete) API** for managing student data using **Spring Boot**. The API allows users to:
- Add new students
- Retrieve all students or a specific student by ID
- Update student details
- Delete a student record

## 🛠️ Tech Stack
- Java 17
- Spring Boot
- RESTful API
- HashMap for in-memory storage

---

## 🚀 Getting Started

### ✅ Prerequisites
Ensure you have the following installed:
- **Java 17** (Check with `java -version`)
- **Maven** (Check with `mvn -version`)
- **Spring Boot** framework

---

### 📥 Installation
1. **Clone the repository**  
   ```bash
   git clone # Student Management API with Spring Boot

## 📌 Overview
This is a **CRUD (Create, Read, Update, Delete) API** for managing student data using **Spring Boot**. The API allows users to:
- Add new students
- Retrieve all students or a specific student by ID
- Update student details
- Delete a student record

## 🛠️ Tech Stack
- Java 17
- Spring Boot
- RESTful API
- HashMap for in-memory storage

---

## 🚀 Getting Started

### ✅ Prerequisites
Ensure you have the following installed:
- **Java 17** (Check with `java -version`)
- **Maven** (Check with `mvn -version`)
- **Spring Boot** framework

---

### 📥 Steps for using This Project
1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-repo/student-api.git
   cd student-api

2. **Build the project**  
   ```bash
    mvn clean install

3. **Run the Spring Boot Application**  
   ```bash
    mvn spring-boot:run

 4 **The API will be available at:**  
   ```bash
    http://localhost:8080/students
 


📡 API Endpoints

| Method  | Endpoint                  | Description             |
|---------|---------------------------|-------------------------|
| GET     | `/students`                | Welcome message         |
| POST    | `/students/add`            | Add a new student       |
| GET     | `/students/all`            | Get all student records |
| GET     | `/students/{id}`           | Get student by ID       |
| PUT     | `/students/update/{id}`    | Update student by ID    |
| DELETE  | `/students/delete/{id}`    | Delete student by ID    |

