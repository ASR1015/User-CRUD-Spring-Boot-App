# User CRUD Spring Boot App

## Requirements
- Java 17
- Maven
- Postman (for testing)

## Setup & Run
```bash
git clone https://github.com/your-username/user-crud.git
cd user-crud
mvn clean install
mvn spring-boot:run
```
  
## API Endpoints
| Method | URL                   | Description        |
| ------ | --------------------- | ------------------ |
| GET    | `/api/users`          | List all users     |
| POST   | `/api/users`          | Create a new user  |
| GET    | `/api/users/{id}`     | Get user by ID     |
| PUT    | `/api/users/{id}`     | Update user by ID  |
| DELETE | `/api/users/{id}`     | Delete user by ID  |

## Postman Collection
1. Import `User_CRUD_API.postman_collection.json`  
2. Run the **Create User** and **List Users** requests.