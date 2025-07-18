# Library Book Catalog API (Spring Boot)

This is a Spring Boot REST API for managing a library's book catalog.  
It allows you to add books, retrieve all books, and manage the catalog.
---
## How to Run This Project

### Requirements:
- Java 17+
- Maven

### Steps:

1. Clone the repository:
```bash
git clone https://github.com/Ashna123293/library-s-book-catalog.git

2.Open the project in STS or IntelliJ

3.Run the application using:
mvn spring-boot:run

4.The API will start at:
http://localhost:8080

## Sample Requests & Responses

### Add a Book By Using POST Mapping 
Request Body:
```json
{
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "isbn": "9780061122415"
}

Response Body:
{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho",
  "isbn": "9780061122415"
}


### GET All Books 
Response Body:
[
  {
    "id": 1,
    "title": "The Alchemist",
    "author": "Paulo Coelho",
    "isbn": "9780061122415"
  }
]
