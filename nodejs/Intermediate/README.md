# Intermediate Engineer Task

## Task Overview
As an Intermediate Engineer, your task is to build a Node.js application that reads a JSON file containing user records, processes the data, and outputs a summary report. This task evaluates your ability to work with file I/O, data structures, and modular code.

## Objectives
1. **File Reading**: Read a JSON file named `users.json` containing an array of user objects. Each user has fields: `id`, `name`, `age`, and `isActive`.
2. **Data Processing**:
   - Count the total number of users.
   - Calculate the average age of users.
   - List all active users (where `isActive` is true).
3. **Output**: Print the summary report in a clear, formatted manner to the console.

## Expected Outcome
- Proficiency with Node.js file system operations.
- Ability to parse and process JSON data.
- Use of functions and modular code structure.
- Clean, maintainable, and well-commented code.

## Example Input (`users.json`)
```json
[
  {"id": 1, "name": "Alice", "age": 28, "isActive": true},
  {"id": 2, "name": "Bob", "age": 34, "isActive": false},
  {"id": 3, "name": "Carol", "age": 25, "isActive": true}
]
```

## Example Output
```
Total users: 3
Average age: 29
Active users: Alice, Carol
```

## Submission Guidelines
- Submit your code as `userReport.js`.
- Include a sample `users.json` file.
- Add a README explaining how to run your script and any assumptions made.
