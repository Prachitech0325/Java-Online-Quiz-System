
---

# 📘 Java Quiz Platform – Dynamic Web Application

The **Java Quiz Platform** is a fully functional dynamic web application designed to conduct online assessments with secure login, automated scoring, and an administrative panel for quiz management. Built using **Java (JSP, Servlets)** and **MySQL**, the platform demonstrates strong understanding of web development, MVC design patterns, database management, and server-side programming.

This project is ideal for educational institutions, training centers, and developers looking to understand Java-based web application development. It includes complete backend–frontend integration, session handling, validation, and database operations through JDBC. The system is optimized for clarity, modularity, and extensibility.

---

## ✨ Key Features

### 🔐 **User Authentication**

* Secure login and registration
* Session-based authentication
* Personalized user dashboard

### 🧑‍💼 **Admin Module**

* Add, edit, and delete quiz questions
* Manage quiz categories
* View and maintain question bank

### 📝 **Quiz Management**

* Timed quizzes with controlled navigation
* Automatic score evaluation
* Result display at completion

### 📊 **Database Integration**

* MySQL database using JDBC
* Fully implemented CRUD operations
* Optimized SQL schema for performance

### 🎨 **User Interface**

* JSP-based dynamic pages
* Clean and responsive layout
* Structured navigation for users and admins

---

## 🏗️ Architecture

The project follows the **MVC (Model–View–Controller)** architecture:

* **Model:** JavaBeans & DAO classes
* **View:** JSP pages, HTML, CSS
* **Controller:** Servlets managing request–response lifecycle

This structure improves scalability, readability, and maintainability.

---

## 🛠️ Technologies and Tools

* **Java (JSP, Servlets)**
* **JDBC**
* **MySQL**
* **Apache Tomcat 9**
* **HTML, CSS, JavaScript**
* **Eclipse IDE**

---

## 📂 Project Structure

```
src/
 ├── controller/     # Servlets
 ├── dao/            # Database Access Layer
 ├── model/          # JavaBeans
 └── DBUtil.java     # DB Connection Utility

WebContent/
 ├── jsp/            # JSP Pages
 ├── css/            # Stylesheets
 ├── js/             # Client Scripts
 └── WEB-INF/        # Deployment Descriptor
```

---

## ⚙️ Setup & Installation

### 1. Import in Eclipse

```
File → Import → Existing Projects into Workspace
```

### 2. Configure Apache Tomcat v9

```
Window → Preferences → Server → Runtime Environments
```

### 3. Create MySQL Database

Run the script:

```sql
schema.sql
```

This creates the database **quiz_db** and required tables.

### 4. Update DB Credentials

Modify:

```
src/dao/DBUtil.java
```

### 5. Run the Application

Start Tomcat and open:

```
http://localhost:8080/JavaQuizPlatform/jsp/login.jsp
```

---

## 📶 Future Enhancements

* Student performance history
* Leaderboard functionality
* Export results as PDF
* REST APIs for mobile integration
* Responsive UI redesign

---

## 📝 License

This project is open-source and intended for academic learning, practice, and demonstration purposes.

---
