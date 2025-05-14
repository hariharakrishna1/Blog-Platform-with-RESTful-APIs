# 📝 Article Management App

A full-stack Spring Boot application for creating, reading, updating, and deleting articles through a clean and RESTful API.

This project demonstrates core backend development practices using **Spring Boot**, **Spring Data JPA**, and **MySQL**. Designed for developers who want to showcase their ability to build scalable, maintainable web services, this app simulates a simple content management platform where users can manage articles effortlessly.

---

## 🚀 Features

- CRUD operations on articles (Create, Read, Update, Delete)
- RESTful API design with clear endpoints
- Layered architecture (Controller, Service, Repository, Model)
- JPA and Hibernate for database interaction
- MySQL integration with configuration via `application.properties`

---

## 🛠️ Technologies Used

- Java 17+
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven

---

## 📂 Project Structure
src/
└── main/
├── java/
│ └── com.example.articlemanagement/
│ ├── controller/
│ ├── model/
│ ├── repository/
│ └── service/
└── resources/
└── application.properties



---

## 📦 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/article-management-app.git


Set up your MySQL database

Create a database named article_db and update the credentials in application.properties.

Build and run the project

bash
Copy
Edit
mvn spring-boot:run
Access the API

Open your browser or Postman at: http://localhost:8080/api/articles

✅ Sample API Endpoints

| Method | Endpoint             | Description          |
| ------ | -------------------- | -------------------- |
| GET    | `/api/articles`      | Get all articles     |
| GET    | `/api/articles/{id}` | Get article by ID    |
| POST   | `/api/articles`      | Create new article   |
| PUT    | `/api/articles/{id}` | Update article by ID |
| DELETE | `/api/articles/{id}` | Delete article by ID |

📄 License
This project is open-source and available under the MIT License.
