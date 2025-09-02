# Senior Engineer Task

## Task Overview
As a Senior Engineer, your task is to design and implement a RESTful API in Java (using Spring Boot) that manages a collection of books. This task evaluates your ability to design APIs, handle data persistence, and write scalable, maintainable code.

## Objectives
1. **API Endpoints**:
   - `GET /books`: List all books.
   - `POST /books`: Add a new book.
   - `GET /books/{id}`: Get details of a specific book.
   - `PUT /books/{id}`: Update a book.
   - `DELETE /books/{id}`: Delete a book.
2. **Data Model**: Each book should have `id`, `title`, `author`, and `year` fields.
3. **Persistence**: Use an in-memory database (e.g., H2) or a file-based approach.
4. **Validation**: Validate input data for required fields and correct types.
5. **Error Handling**: Return appropriate HTTP status codes and error messages.

## Expected Outcome
- Proficiency in building RESTful APIs with Java and Spring Boot.
- Ability to structure code for scalability and maintainability.
- Proper error handling and input validation.
- Use of annotations, controllers, and service layers.

## Submission Guidelines
- Submit your code as a folder named `book-api`.
- Include instructions in a README for building and running the application.
- Provide a sample data file or instructions for initializing the database.
