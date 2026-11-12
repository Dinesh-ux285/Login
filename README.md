# Login and Registration System

A Java web application that implements user login and registration functionality using **JSP, Servlets, JDBC, and MySQL**. This project demonstrates how a Java web application handles user requests, validates login credentials, and interacts with a relational database.

## 🚀 Technologies Used

- **Java** – Backend programming
- **JSP (JavaServer Pages)** – Frontend and dynamic web pages
- **Servlets** – Request handling and application logic
- **JDBC** – Database connectivity
- **MySQL** – Database management
- **HTML & CSS** – Page structure and styling
- **Apache Tomcat** – Web application server
- **Eclipse IDE** – Development environment

## ✨ Features

- User login functionality
- User registration functionality
- Validates user credentials
- Stores user information in MySQL database
- Connects Java application with MySQL using JDBC
- Handles HTTP requests using Servlets
- Displays dynamic content using JSP

## 📂 Project Structure

```text
Loginn/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── Login.java
│       │
│       └── webapp/
│           ├── META-INF/
│           ├── WEB-INF/
│           ├── login.jsp
│           └── profile.jsp
│
└── Referenced Libraries/
    └── mysql-connector-j-26.1.0.jar
```

*Note: Update the structure above according to your actual project folders and filenames.*

## 🛠️ Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github/your-username/Login-Project.git
   ```

2. Open the project in Eclipse IDE.

3. Configure Apache Tomcat Server.

4. Create a MySQL database.

5. Configure the database URL, username, and password in the JDBC connection code.

6. Add the MySQL Connector/J dependency to the project.

7. Run the project on Apache Tomcat.

8. Open the application in your browser.

## 🗄️ Database Configuration

Create a MySQL database and a user table according to the SQL queries used in the project.

Update your JDBC connection details:

```java
String url = "jdbc:mysql://localhost:3306/your_database";
String username = "root";
String password = "your_password";
```

## 🎯 Learning Outcomes

- Understanding JSP and Servlet integration
- Handling HTTP GET and POST requests
- Connecting Java web applications with MySQL using JDBC
- Performing database operations
- Understanding the flow of requests between JSP, Servlets, and the database

## 👨‍💻 Author

**Bestha Dinesh**

GitHub: [dinesh-ux285](https://github.com/dinesh-ux285)
