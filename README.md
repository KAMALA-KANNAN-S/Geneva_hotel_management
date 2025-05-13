

# 🏨 Geneva Hotel Management

**Geneva Hotel Management** is a comprehensive, enterprise-level hotel management system built with Java. Designed for performance, scalability, and ease of use, it covers everything from reservations and billing to staff management and real-time analytics.

![Dashboard Preview](https://via.placeholder.com/1000x400.png?text=Geneva+Hotel+Management+System)

---

## 🚀 Key Features

* 🔑 **Room Booking & Reservations**
* 🛏️ **Room & Inventory Management**
* 👨‍💼 **Staff & Role-Based Access Control**
* 📊 **Advanced Reporting & Analytics**
* 💳 **Invoicing & Payment Tracking**
* 🌐 **RESTful API for Integration**
* 🛡️ **Secure Authentication (JWT / Spring Security)**
* 🧪 **Robust Unit & Integration Testing**

---

## 🧰 Tech Stack

| Layer      | Technology                   |
| ---------- | ---------------------------- |
| Language   | Java 17+                     |
| Framework  | Spring Boot, Spring Security |
| ORM        | Hibernate / JPA              |
| Database   | PostgreSQL / MySQL           |
| Build Tool | Maven / Gradle               |
| Testing    | JUnit, Mockito               |
| API        | RESTful, Swagger/OpenAPI     |
| Packaging  | JAR / WAR                    |

---

## 📦 Installation

### Prerequisites

* Java 17+
* Maven or Gradle
* PostgreSQL or MySQL
* Git

### Clone the Repository

```bash
git clone https://github.com/your-org/geneva_hotel_management.git
cd geneva_hotel_management
```

### Setup Database

Create a database named `geneva_hotel_db` and configure credentials in `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/geneva_hotel_db
spring.datasource.username=root
spring.datasource.password=your_password
```

### Run the App

Using **Maven**:

```bash
./mvnw spring-boot:run
```

Using **Gradle**:

```bash
./gradlew bootRun
```

Visit: [http://localhost:8080](http://localhost:8080)

---

## 🧪 Running Tests

```bash
./mvnw test
```

or

```bash
./gradlew test
```

---

## 📁 Project Structure

```
geneva_hotel_management/
├── src/
│   ├── main/
│   │   ├── java/com/geneva/hotel/      # Main application code
│   │   └── resources/                   # Application config, SQL, static files
│   └── test/                           # Unit and integration tests
├── pom.xml / build.gradle              # Build config
└── README.md
```

---

## 🧬 API Documentation

After running the app, access Swagger UI at:

📚 [http://localhost:8080/swagger-ui.html](http://localhost:8080/swagger-ui.html)

---

## 🛠 Configuration

Customize environment settings in:

```bash
src/main/resources/application.properties
```

---

## 🤝 Contributing

Contributions are welcome! Please:

1. Fork the repo
2. Create a new branch
3. Commit your changes
4. Submit a Pull Request

Read the [CONTRIBUTING.md](CONTRIBUTING.md) for more info.

---

## 🛡 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

* Email: [info@genevahoteltech.com](mailto:info@genevahoteltech.com)
* Website: [www.genevahoteltech.com](https://www.genevahoteltech.com)

I can help tailor those sections too.
