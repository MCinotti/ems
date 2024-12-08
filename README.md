# Employee Management System (EMS) 👩‍💼👨‍💼

## Overview 🌟

The Employee Management System (EMS) is a web application designed to streamline HR operations. It provides a centralized platform for managing employee information, tracking performance, generating reports, and integrating with other systems. Built using Java, Spring Boot, React, and PostgreSQL, EMS simplifies HR tasks with user authentication, role management, and performance tracking.

## Key Features ⚙️

- **User Authentication and Authorization** 🔑: Secure login, with role-based access control for employees, managers, and admins.
- **Employee Management** 👥: CRUD operations for employee records, including personal details, job history, and contact information.
- **Department and Role Management** 🏢: Organize employees into departments and assign roles to streamline internal operations.
- **Performance Tracking** 📊: Record and review employee evaluations and performance metrics.
- **Reporting** 📈: Generate customizable reports on employee performance, attendance, salary history, and more.
- **RESTful API** 🌐: Expose endpoints for seamless integration with other internal or third-party systems.

## Technology Stack 🛠️

- **Backend**: Java, Spring Boot, Hibernate, REST API
- **Frontend**: React, JavaScript, JSX, CSS
- **Database**: PostgreSQL (or other RDBMS)
- **Other Tools**: Maven, Git, Node.js, npm

---

## Getting Started 🚀

### Prerequisites ⚙️

Before you can build and run the project, make sure you have the following installed:

- **Java 21+**: [Download Java](https://adoptopenjdk.net/)
- **Maven**: [Download Maven](https://maven.apache.org/download.cgi)
- **Node.js & npm**: [Download Node.js](https://nodejs.org/en/download/)
- **PostgreSQL** (or another relational database): [Download PostgreSQL](https://www.postgresql.org/download/)

---

### 1. Clone the Repository 🖥️

Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/ems
cd ems
```

---

### 2. Set Up Environment 🌍

#### Backend Setup (Spring Boot)

1. Install Java 21+ and Maven.
2. Set up a PostgreSQL database (or another preferred RDBMS).
3. Create a database named `ems` and update the `src/main/resources/application.properties` file with your database credentials:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/ems
spring.datasource.username=your-username
spring.datasource.password=your-password
```

#### Frontend Setup (React)

1. Navigate to the `frontend` directory:

```bash
cd frontend
```

2. Install the required npm dependencies:

```bash
npm install
```

---

### 3. Build and Run the Application 🚀

#### Backend (Spring Boot)

1. Navigate back to the root project directory:

```bash
cd ..
```

2. Build the backend using Maven:

```bash
mvn clean package
```

3. Run the backend application:

```bash
java -jar target/ems-app.jar
```

The backend should now be running on [http://localhost:8080](http://localhost:8080).

#### Frontend (React)

1. Navigate to the `frontend` directory:

```bash
cd frontend
```

2. Start the React development server:

```bash
npm start
```

The frontend should now be running on [http://localhost:3000](http://localhost:3000).

---

### 4. Access the Application 🔍

- The **frontend** will be available on [http://localhost:3000](http://localhost:3000).
- The **backend** REST API will be available on [http://localhost:8080](http://localhost:8080).

---

### 5. Common Issues and Troubleshooting ⚠️

- **Error: "Database connection failed"**: Make sure your PostgreSQL server is running and that the database credentials in `application.properties` are correct.
- **Error: "Port 8080 is already in use"**: If the backend cannot start, try changing the port in `application.properties` under `server.port`.
- **Frontend not loading**: Ensure you've installed the frontend dependencies using `npm install` and that the React development server is running with `npm start`.

---

## Screenshots 📸

![Employee List](path-to-screenshot.png)  
![Performance Dashboard](path-to-screenshot.png)

---

## Live Demo 🌍

[Live demo link here]  
**Username**: demo_user  
**Password**: demo_pass

---

## API Documentation 📚

For detailed API documentation, please refer to the [API Documentation](./API_DOCUMENTATION.md).

---

## Contributing 🤝

We welcome contributions to this project! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

---

### Coding Standards 📜

- Follow the Java coding conventions for the backend.
- For the frontend, follow React best practices, including using functional components and hooks.

---

### Testing 🧪

- **Backend Testing**: Unit tests for the backend are written using JUnit and Mockito. Run the tests using Maven:

```bash
mvn test
```

- **Frontend Testing**: Frontend tests can be run using Jest and React Testing Library. Run tests with:

```bash
npm test
```

---

## License 📝

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
