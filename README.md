# BookHub System

Welcome to the Book Shop API project! This project aims to provide a comprehensive solution for managing a book store, offering CRUD operations and a seamless communication flow between the backend and frontend.


## Features

- Add a new book to the store
- Retrieve details of all books
- Retrieve details of a specific book by ID
- Update the information of an existing book
- Delete a book by ID

## Technologies Used

- **Backend:**
  - Spring Boot
  - Hibernate/JPA
  - Jakarta Validation

- **Frontend:**
  - Angular

- **Database:**
  - MySQL

## API Endpoints
GET /books: Retrieve details of all books.  
GET /books/{bookId}: Retrieve details of a specific book by ID.  
POST /books: Add a new book to the store.  
PUT /books: Update the information of an existing book.  
DELETE /books/{bookId}: Delete a book by ID.

## Database Design
The project uses a MySQL database with a Book table. Here is the table structure:   
CREATE TABLE Book (   
      id BIGINT NOT NULL AUTO_INCREMENT,  
      book_name VARCHAR(255),  
      author_name VARCHAR(255),  
      ISBN VARCHAR(70),  
      Price BIGINT,  
      PRIMARY KEY (id)  
);


