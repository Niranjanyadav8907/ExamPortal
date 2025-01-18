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

---

## Further Help

For more information:
- Visit the [Angular CLI Overview and Command Reference](https://angular.io/cli).
- Refer to the [Spring Boot Documentation](https://spring.io/projects/spring-boot).

# Fixing PowerShell Execution Policy Error

If you encounter an error while running Angular commands in PowerShell, such as:

```
File C:\Users\<User>\AppData\Roaming\npm\ng.ps1 cannot be loaded because running scripts is disabled on this system.
```

This error occurs due to PowerShell's execution policy settings. Here's how you can fix it.

---

## Solution

### 1. Open PowerShell in Administrator Mode
- Search for "PowerShell" in the Windows search bar.
- Right-click on **Windows PowerShell** and select **Run as Administrator**.

### 2. Change the Execution Policy
Run the following command in the PowerShell terminal:

```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

- When prompted for confirmation, type `Y` and press `Enter`.

### 3. Retry Your Angular Command
- Return to your project directory in Visual Studio Code or any terminal.
- Run the Angular development server command again:

```bash
ng serve
```

---

## Alternative Temporary Fix
If you prefer not to change the execution policy permanently, you can bypass it for the current session:

```powershell
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

This change is temporary and will reset when you close the PowerShell session.

---

## Notes
- The execution policy change is safe when using trusted scripts.
- Always be cautious and avoid running scripts from unknown sources.

For more information about PowerShell execution policies, visit the official documentation:
[Microsoft PowerShell Execution Policies](https://go.microsoft.com/fwlink/?LinkID=135170).





