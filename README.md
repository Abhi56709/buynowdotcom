# 🛒 BuyNowDotCom

**BuyNowDotCom** is a full-stack e-commerce web application designed to simulate the core features of a modern online shopping platform. This project was developed as part of the **Kodnest Full Stack Java Training Program** and serves as a practical implementation of full-stack web development using Java. The platform provides functionalities such as user registration, product browsing, cart management, and admin functionalities for managing products.

---

## 📌 Project Highlights

- 🎯 Real-world e-commerce platform with focus on core features.
- 🔐 Secure login & registration system for both customers and admins.
- 📦 Complete shopping cart, checkout, and order management system.
- 🧑‍💼 Admin dashboard for managing inventory, users, and orders.
- 🧾 Integration of MySQL database for persistent data storage.
- 🎨 Clean, responsive UI using Bootstrap for seamless user experience.

---

## 🛠️ Tech Stack

### Frontend
- **HTML5, CSS3, JavaScript**
- **React.js** (or plain JavaScript/jQuery, if applicable)
- **Bootstrap** – for responsive design and UI components
- **JSP** (Java Server Pages) – for server-side rendering (if applicable)

### Backend
- **Java**
- **Spring Boot** / **Servlets & JSP** (depending on your setup)
- **JDBC / Hibernate** – for database connectivity and ORM (Object-Relational Mapping)

### Database
- **MySQL** – used for data persistence (users, products, orders, etc.)
- **JDBC** (Java Database Connectivity) – for database interaction

### Tools & Environment
- **Apache Tomcat** – web server to deploy the application
- **Eclipse / IntelliJ IDEA** – IDE for Java development
- **Git & GitHub** – for version control and collaboration
- **Postman** – to test and verify APIs

---

## 📁 Project Structure

buynowdotcom/ ├── src/ │ ├── com/buynowdotcom/controller/ # All controller classes for routing and business logic │ ├── com/buynowdotcom/model/ # Model classes representing the database structure │ ├── com/buynowdotcom/dao/ # Data access objects (DAO) for database interactions │ └── com/buynowdotcom/utils/ # Utility classes and helpers ├── WebContent/ (or frontend/) │ ├── css/ # CSS styles for the frontend UI │ ├── js/ # JavaScript files to handle frontend logic │ ├── images/ # Image assets (logos, product images, etc.) │ └── *.jsp # JSP files for the UI (if applicable) ├── database/ │ └── schema.sql # SQL script for setting up the database schema ├── .gitignore # List of files/folders to be ignored by Git └── README.md # Project documentation


---

## 🚀 How to Run the Project

### Prerequisites

Before you can run the project locally, you’ll need the following:

- **Java 8 (or later)**: The application is built using Java.
- **Apache Tomcat**: For running the Java web application.
- **MySQL Server**: For database persistence.
- **Git**: To clone the repository and track changes.
- **Postman (Optional)**: To test RESTful APIs.

### Setup Instructions

1. **Clone the Repository**
   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Abhi56709/buynowdotcom.git
   cd buynowdotcom
