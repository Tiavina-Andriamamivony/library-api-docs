# Library Management API Specification

Welcome to the **Library Management API Specification** repository!  
This project documents the API for managing books and authors in a library system using the OpenAPI 3.1.0 standard.

---

## 🚀 Features

- **Books Management**:
    - CRUD operations for books.
    - Filter books by name or release date range.

- **Authors Management**:
    - CRUD operations for authors.
    - Filter authors by name.

- **OpenAPI Specification**:
    - Fully documented API using OpenAPI 3.1.0.
    - Mock server integration with SwaggerHub.

- **Postman Ready**:
    - Auto-generated Postman collection for endpoint testing.

---

## 📚 API Endpoints

### `/books`
| Method   | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| `GET`    | Retrieve all books or filter by `bookName` or `releaseDate`.               |
| `POST`   | Add a new book.                                                            |
| `PUT`    | Update a book (idempotent).                                                |
| `DELETE` | Delete a book by ID.                                                       |

### `/authors`
| Method   | Description                                                                 |
|----------|-----------------------------------------------------------------------------|
| `GET`    | Retrieve all authors or filter by `authorName`.                            |
| `POST`   | Add a new author.                                                          |
| `PUT`    | Update an author (idempotent).                                             |
| `DELETE` | Delete an author by ID.                                                    |

---

## 🛠️ Tools and Technologies

- **OpenAPI 3.1.0**: API documentation standard.
- **SwaggerHub**: Mock server and API visualization.
- **Postman**: For testing and collection generation.

---

## 🌟 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/library-management-api.git
   cd library-management-api
