# RESTful-Bookstore-API

A simple RESTful backend for a Bookstore — built using Java + Spring Boot + MySQL.  
Supports CRUD operations on books and gives a foundation for full-stack or API-based applications.

## 📘 Project Overview

This project aims to provide a RESTful API for managing a bookstore: adding books, listing books, updating and deleting book records.  
The goal was to practice backend development using Java and Spring Boot and build a clean API service you can extend in future (e.g. with a front-end, authentication, more features).

## 🔧 Technologies & Tools Used

- Java (latest stable version)  
- Spring Boot  
- MySQL (or any relational DB — can be configured)  
- Maven (for build & dependency management)  
- (Optional) Postman for API testing  

## 🚀 How to Run Locally

1. Clone the repository  
   ```bash
   git clone https://github.com/poonam04-taxak/RESTful-Bookstore-API.git
   ```  
2. Open the project in your favorite IDE (IntelliJ IDEA / Eclipse / VS Code)  
3. Create a MySQL database — name it e.g. `bookstore_db`  
4. Update database configuration in `application.properties` (or equivalent) — set DB URL, username, password  
5. Build and run the Spring Boot application  
   ```bash
   mvn clean install  
   mvn spring-boot:run
   ```  
6. Use Postman (or any API client) to test the APIs at `http://localhost:8080/` (or configured port)

## 📚 API Endpoints

| HTTP Method | Endpoint | Description |
|-------------|----------|-------------|  
| `GET`       | `/books`       | List all books |  
| `GET`       | `/books/{id}`  | Get a book by ID |  
| `POST`      | `/books`       | Add a new book (provide book data in request body) |  
| `PUT`       | `/books/{id}`  | Update an existing book |  
| `DELETE`    | `/books/{id}`  | Delete a book by ID |  


## 🧪 What I Learned / Challenges & Growth

- Gained hands-on experience in designing REST APIs using Spring Boot.  
- Learned how to configure Spring Boot with MySQL and manage CRUD operations.  
- Understood API request/response design and how to handle exceptions or invalid inputs.  
- Built a clear project structure: controllers, services, repositories — which helps maintain clean code and separation of concerns.  

## 🔮 Future Improvements / What Next

- Add validation & exception handling (e.g. invalid input, missing fields)  
- Introduce user authentication & authorization (e.g. add users and allow only logged-in users to add/update/delete books)  
- Add pagination, search, and filtering for the book list  
- Implement a frontend (React / Angular / Vue) to consume these APIs and provide a full-stack application  
- Add unit & integration tests  

## 📂 Repository & Demo

- GitHub repo: https://github.com/poonam04-taxak/RESTful-Bookstore-API  
- (Optional) Live demo: *If you deploy your application you can add the live URL here.*  

## ⚠️ License & Notes

This project is for learning and demonstration purposes. Feel free to use and extend it, but please give appropriate credit.

---

