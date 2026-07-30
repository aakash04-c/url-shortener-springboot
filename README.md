# 🔗 Spring Boot URL Shortener

A lightweight and efficient URL Shortener application built with **Spring Boot**, **Spring Data JPA**, **Thymeleaf**, and **MySQL**. It allows users to convert long URLs into compact, shareable links and automatically redirects users to the original destination when the shortened URL is accessed.

## ✨ Features

- 🔗 Generate unique short URLs
- 🚀 Instant redirection to original URLs
- 💾 Store URL mappings in MySQL
- ✅ Server-side input validation
- 🎨 Clean and responsive user interface
- ⚡ Fast and lightweight Spring Boot backend
- 🏗️ Layered architecture following Spring Boot best practices
- 📱 Responsive design for desktop and mobile devices

---

## 🛠️ Tech Stack

### Backend
- Java 21
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Frontend
- HTML5
- CSS3
- Thymeleaf

### Database
- MySQL

### Build Tool
- Gradle

---

## 📂 Project Structure

```
src
├── main
│   ├── java
│   │   └── com.example.urlshortener
│   │       ├── controller
│   │       ├── entity
│   │       ├── repository
│   │       ├── service
│   │       └── UrlShortenerApplication.java
│   │
│   └── resources
│       ├── static
│       ├── templates
│       └── application.properties
└── test
```

---

## 🚀 Getting Started

### Prerequisites

- Java 21 or later
- MySQL
- Gradle
- Git

### Clone the Repository

```bash
git clone https://github.com/aakash04-c/url-shortener-springboot.git
cd url-shortener-springboot
```

### Configure Database

Create a MySQL database.

```sql
CREATE DATABASE urlshortener;
```

Update your `application.properties` file.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/urlshortener
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
```

---

### Run the Application

```bash
./gradlew bootRun
```

or on Windows

```bash
gradlew.bat bootRun
```

Open your browser and visit

```
http://localhost:8081
```

---

## 📸 Screenshots

### Home Page

> Add a screenshot here

```
screenshots/home.png
```

### Short URL Generated

> Add a screenshot here

```
screenshots/result.png
```

---

## ⚙️ How It Works

1. Enter a long URL.
2. The application validates the URL.
3. A unique short code is generated.
4. The mapping is stored in the database.
5. Visiting the short URL automatically redirects to the original URL.

---

## 📈 Future Enhancements

- 👤 User Authentication
- 📊 URL Click Analytics
- 📅 URL Expiration
- ✏️ Custom Short URLs
- 📱 QR Code Generation
- 📋 Copy Short URL Button
- 🌙 Dark Mode
- 🔍 Search History
- 📄 REST API Support
- 🐳 Docker Deployment
- ☁️ Cloud Deployment

---

## 💡 Learning Outcomes

This project helped me understand:

- Spring Boot Project Structure
- Spring MVC Architecture
- CRUD Operations using Spring Data JPA
- Database Integration with MySQL
- Thymeleaf Template Engine
- URL Redirection Logic
- Dependency Injection
- Layered Application Design
- Exception Handling
- Form Validation

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Aakash Malviya**

- GitHub: https://github.com/aakash04-c

---

### ⭐ If you found this project useful, consider giving it a Star!
