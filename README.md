# EMS Backend – Spring Boot

Backend API for managing employees, built with Spring Boot.

## 🚀 Features

- REST CRUD: `GET`, `POST`, `PUT`, `DELETE` for `/employees`
- Layers: Controller → Service → Repository → Entity
- Entity ↔ DTO conversion using Mapper
- Spring Data JPA with H2 (default) or switchable DB
- Lombok annotations: `@Getter`, `@Setter`, `@NoArgsConstructor`, `@AllArgsConstructor`

## 🛠 Stack

- Java 17+
- Spring Boot 3.x
- Spring Data JPA
- H2 database (configurable)
- Maven
- Lombok

![img](https://github.com/user-attachments/assets/e22b402d-92bf-4f36-b68f-5d98e7d23c78)

## Sample Endpoints

| Method | URL                   | Action                              |
|--------|-----------------------|--------------------------------------|
| GET    | `/api/employees`      | List all employees                   |
| GET    | `/api/employees/{id}` | Get employee by ID                   |
| POST   | `/api/employees`      | Create new employee (via DTO)        |
| PUT    | `/api/employees/{id}` | Update employee by ID (via DTO)      |
| DELETE | `/api/employees/{id}` | Delete employee by ID                |
| DELETE | `/api/employees`      | Delete all employees                 |
