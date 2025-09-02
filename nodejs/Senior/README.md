# Senior Engineer Task

## Task Overview
As a Senior Engineer, your task is to design and implement a RESTful API using Node.js (with Express) that manages a collection of products. This task evaluates your ability to design APIs, handle data persistence, and write scalable, maintainable code.

## Objectives
1. **API Endpoints**:
   - `GET /products`: List all products.
   - `POST /products`: Add a new product.
   - `GET /products/:id`: Get details of a specific product.
   - `PUT /products/:id`: Update a product.
   - `DELETE /products/:id`: Delete a product.
2. **Data Model**: Each product should have `id`, `name`, `price`, and `quantity` fields.
3. **Persistence**: Store data in a JSON file (`products.json`).
4. **Validation**: Validate input data for required fields and correct types.
5. **Error Handling**: Return appropriate HTTP status codes and error messages.

## Expected Outcome
- Proficiency in building RESTful APIs with Node.js and Express.
- Ability to structure code for scalability and maintainability.
- Proper error handling and input validation.
- Use of middleware and modular routing.

## Submission Guidelines
- Submit your code as a folder named `product-api`.
- Include instructions in a README for installing dependencies and running the server.
- Provide a sample `products.json` file.
