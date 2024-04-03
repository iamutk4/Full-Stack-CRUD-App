# Full Stack CRUD Application

This project is a Full Stack CRUD (Create, Read, Update, Delete) application built using Java with Spring Boot for the back end and React for the front end. The application allows users to perform CRUD operations on a database through a user-friendly interface.

## Project Overview:

**Back End (Java with Spring Boot):**
- **RESTful APIs:** The back end is implemented using Spring Boot, where RESTful APIs are created to handle various requests from the front end.
- **Database Integration:** MySQL database is used to store and manage data, and Spring Data JPA is employed to interact with the database.
- **CRUD Operations:** Endpoints are created to handle CRUD operations, enabling users to create, read, update, and delete data in the database.

**Front End (React):**
- **User Interface:** The front end is developed using React to create a responsive and dynamic user interface.
- **State Management:** React Hooks are utilized for state management, allowing for efficient management of component state.
- **Integration with Back End:** The front end communicates with the back end through APIs created in Postman, enabling seamless integration between the two layers.

## Workflow Overview:
1. **Back End Development:** RESTful APIs are designed and implemented using Java with Spring Boot. Spring Data JPA is used to interact with the MySQL database.
2. **Front End Development:** The user interface is created using React, with a focus on responsiveness and dynamic user experience. React Hooks are employed for state management.
3. **Integration:** Front end and back end are integrated using APIs created in Postman, ensuring smooth communication between the two layers.
4. **Testing and Deployment:** The application is thoroughly tested to ensure functionality and reliability before deployment to production environment.

## Libraries and Tools Used:
- **Back End:** Java, Spring Boot, Spring Data JPA, MySQL
- **Front End:** Javascript, React, React Hooks

## Usage:
1. Clone the repository:
```
git clone https://github.com/iamutk4/full-stack-crud-project.git
```
2. Setup MySQL database

3. Start the backend server by running ```FullStackBackendApplication.java``` file present in:
```
fullstack-backend/src/main/java/com/crudapp/fullstackbackend/FullstackBackendApplication.java
```
4. Start the frontend server:
```
cd fullstack-frontend
npm start
```
