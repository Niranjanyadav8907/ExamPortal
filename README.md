# ExamPortal
ExamPortal is a comprehensive project developed using **Spring Boot** for the backend and **Angular** for the frontend. This tutorial will guide you step by step through the development process of the ExamPortal project. The frontend of this project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 11.2.10.

---

## Development Server

To run the development server for the Angular frontend:

1. Execute the following command:
   ```bash
   ng serve
   ```
2. Navigate to `http://localhost:4200/` in your web browser. The application will automatically reload if you make any changes to the source files.

---

## Code Scaffolding

You can generate various components, directives, pipes, and other elements for your Angular project using the following commands:

- To generate a new component:
  ```bash
  ng generate component component-name
  ```
- To generate other elements like directives, pipes, services, etc.:
  ```bash
  ng generate directive|pipe|service|class|guard|interface|enum|module
  ```

---

## Build

To build the Angular application:

- Run the following command:
  ```bash
  ng build
  ```
- The build artifacts will be stored in the `dist/` directory.
- For a production build, use:
  ```bash
  ng build --prod
  ```

---

## Running Unit Tests

To execute unit tests using [Karma](https://karma-runner.github.io):

```bash
ng test
```

---

## Running End-to-End Tests

To execute end-to-end tests using [Protractor](http://www.protractortest.org/):

```bash
ng e2e
```

---

## Backend Setup with Spring Boot

The backend of the ExamPortal project is built using **Spring Boot**. It provides RESTful APIs for managing exam-related data and user authentication.

### Key Features:
1. **User Management**: Registration, login, and role-based access.
2. **Exam Management**: CRUD operations for exams, questions, and categories.
3. **Results**: Storing and retrieving user performance data.
4. **Security**: Integrated Spring Security and JWT for authentication.

---

## Language and Tools Used

| **Technology**  | **Purpose**                  |
|------------------|------------------------------|
| Spring Boot      | Backend development         |
| Angular          | Frontend development        |
| MySQL            | Database management         |
| Spring Security  | Authentication and security |

### Language Tool Image
![Language Tools](https://upload.wikimedia.org/wikipedia/commons/8/8e/Spring-Boot-Logo.svg)

---

## Further Help

For more information:
- Visit the [Angular CLI Overview and Command Reference](https://angular.io/cli).
- Refer to the [Spring Boot Documentation](https://spring.io/projects/spring-boot).

---

Feel free to contribute to this project by raising issues or submitting pull requests on GitHub!

