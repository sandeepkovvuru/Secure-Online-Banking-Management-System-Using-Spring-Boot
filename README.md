
# 🔐 Secure Online Banking Management System

A secure, full-stack online banking application built with **Java, Spring Boot, Spring Security, Hibernate (JPA), MySQL**, and **Thymeleaf**. This system simulates real-world banking functionality such as user account management, transactions, and loan processing—emphasizing security, scalability, and clean architecture.

---

## 🚀 Features

- ✅ **User Authentication & Role-Based Access** (Admin & Customer)
- ✅ **Account Management** – Create, view, and manage bank accounts
- ✅ **Secure Transactions** – Deposit, withdraw, and transfer funds
- ✅ **Loan Application System** – Apply for loans, admin approval
- ✅ **Transaction History** – View all past activity
- ✅ **Spring Security Integration** – Secure login and authorization
- ✅ **Password Encryption** – Stored using **BCrypt**
- ✅ **Dynamic Frontend** using Thymeleaf Templates

---

## 🛠 Technology Stack

| Layer        | Technology                         |
|--------------|------------------------------------|
| Language     | Java                               |
| Backend      | Spring Boot, Spring Security       |
| Database     | MySQL                              |
| ORM          | Hibernate (JPA)                    |
| Frontend     | Thymeleaf, HTML, CSS               |
| Build Tool   | Maven                              |
| IDE          | VS Code / IntelliJ IDEA            |

---

## ⚙️ Setup Instructions

### 1. **Clone the Repository**
```bash
git clone https://github.com/your-username/online-banking.git
cd online-banking
````

### 2. **Set Up MySQL Database**

* Create a database:

```sql
CREATE DATABASE bankingdb;
```

* Update your `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/bankingdb
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
```

### 3. **Build and Run**

```bash
mvn clean install
mvn spring-boot:run
```

### 4. **Open in Browser**

Navigate to:
📍 [http://localhost:8080/login](http://localhost:8080/login)

---

## 👤 Default Users

| Role  | Username | Password   |
| ----- | -------- | ---------- |
| Admin | `admin`  | `admin123` |
| User  | `user`   | `user123`  |

---

## 🖥️ Screens Available

* 🔐 Login Page
* 🏠 Dashboard Page
* 🏦 Accounts View
* 💸 Transactions Page
* 💼 Loan Application Page
* 📊 Transaction History

---

## 📁 Project Structure

```
online-banking/
├── controller/         # MVC Controllers
├── model/              # JPA Entities
├── repository/         # Data Repositories
├── service/            # Business Logic
├── config/             # Security Configuration
├── templates/          # Thymeleaf HTML Templates
├── application.properties
└── OnlineBankingApplication.java
```

---

## 📌 Future Enhancements

* ✅ JWT-based token authentication for REST APIs
* ✅ User registration module
* ✅ PDF export for statements
* ✅ React-based frontend for better UI/UX
* ✅ SMS/email alerts on transactions

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

**Author:** Sandeep Kovvuru
📧 Email: [your-email@example.com](mailto:sandeep.kovvuru23@gmail.com)
🌐 GitHub: [your-github-username](https://github.com/sandeepkovvuru)

```

---
