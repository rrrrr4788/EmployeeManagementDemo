## Intro

Employee is a project that demos how to perform basic CRUD operations in Spring Boot.

## Running the application

This application is built in IntelliJ IDEA, so it is highly recommended to run this application under the IDEA environment.

Below are the procedures:

1. Configure your local MySQL and setup an account with name being 'springstudent' and password being 'springstudent'.
2. Set the port to 3306.
3. Run employee.sql in MySQL to create the tables.
4. Back to IntelliJ, install the packages via Maven.
5. Run the project.

## APIs:

- GET /api/employees (return all employees in the database)
- GET /api/employees/{employeeId} (return one employee with the given employeeId)
- POST /api/employees (add a new employee)
- PUT /api/employees (update an employee's info)
- DELETE /api/employees/{employeeId} (delete an employee given his id)