# Book Store Management System

A full-stack web application built with Spring Boot, Spring Data JPA, and Thymeleaf for managing book inventories and personal reading lists.

---

## Features

* **Book Catalog Management:** View available books, add new entries, edit existing details, and delete entries from the system.
* **My Books Collection:** Add books from the store catalog to a personalized reading list and manage saved titles.
* **Dynamic Web UI:** Built using Thymeleaf templates with responsive views for seamless browser interaction.
* **Database Integration:** Spring Data JPA persistence for seamless entity relational mapping and repository management.

---

## Tech Stack

* **Framework:** Spring Boot
* **Persistence & ORM:** Spring Data JPA, Hibernate
* **View Layer:** Thymeleaf HTML Templates
* **Build Tool:** Apache Maven
* **Language:** Java 17+

---

## Repository Structure

```text
bookstore_spring_boot_project-main/bookStore/
├── src/
│   ├── main/
│   │   ├── java/com/bookStore/
│   │   │   ├── controller/      # BookController & MyBookListController
│   │   │   ├── entity/          # Book & MyBookList models
│   │   │   ├── repository/      # Spring Data JPA repositories
│   │   │   └── service/         # Business logic layer
│   │   └── resources/
│   │       ├── static/          # Assets (CSS/Images)
│   │       ├── templates/       # HTML views (home, bookList, bookRegister, myBooks, bookEdit)
│   │       └── application.properties # Database & server configs
│   └── test/                    # Spring Boot integration tests
├── pom.xml                      # Maven dependencies
└── mvnw / mvnw.cmd              # Maven wrapper scripts
