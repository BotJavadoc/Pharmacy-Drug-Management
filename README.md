# Pharmacy-Drug-Mangement

Welcome to the Online Medicine Shop project! This web application is designed to facilitate the online purchase and restocking of medicines. Built using JSP, MySQL, and other Java technologies, it provides a comprehensive solution for vendors and customers.
## Screen Shots
![VendorHomepage](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/98823596-ed92-4ebc-9dec-5b6f8104479d)
![SellerRegister](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/e23a28c5-cf7e-4ff3-85ab-a7b1827a4064)
![Restock](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/d8f29f45-506a-4571-97ba-64929dd8fa67)
![Login](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/f8cd507a-78ad-4009-a4cb-5885c520fa98)
![Index](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/7baaf69d-4b30-4f5d-871c-a14106a0532f)
![CustomerHomepage](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/47b09401-aec4-438d-9d38-029f17ebfda0)
![Buy 2](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/1b7ed277-bd1c-47a7-9c86-0da0abaff74e)
![Buy 1](https://github.com/BotJavadoc/Pharmacy-Drug-Management/assets/78670888/f724046b-f9f9-434f-8f5e-218c929a0135)





## Table of Contents

- [Introduction](#introduction)
- [Project Modules](#project-modules)
- [Technologies Used](#technologies-used)
- [Supported Operating Systems](#supported-operating-systems)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Online Medicine Shop project is a web-based application that allows customers to purchase medicines and vendors to manage their stock. This project uses JSP for the front-end logic, Java for the business logic, and MySQL as the database. The application runs on a Tomcat server and can be configured on various operating systems.

## Project Modules

- **Login Pages:** Separate login pages for vendor and customer.
- **Register Page:** Registration page for new customers.
- **Customer Homepage:** Dashboard for customer activities.
- **Vendor Homepage:** Dashboard for vendor activities.
- **Buy Page:** Page for customers to purchase medicines.
- **Vendor Restock Page:** Page for vendors to restock medicines.
- **Home Page:** Landing page of the application.
- **Products:** Display all available products.
- **Add Product:** Functionality for vendors to add new products.
- **Purchase Medicine:** Process of buying medicine by customers.
- **View Order:** Customers can view their order history.

## Technologies Used

- **HTML:** Page layout design.
- **CSS:** Styling and design.
- **JavaScript:** Validation tasks and animations.
- **JSP:** Front-end logic.
- **Java:** Business logic.
- **MySQL:** Database management.
- **Tomcat:** Server to run the project.

## Supported Operating Systems

- **Windows:** Compatible with Windows systems. Requires Tomcat 7, JDK 7, MySQL 5.
- **Linux:** Compatible with all versions of Linux.
- **Mac:** Easily configurable on Mac OS.

## Installation

### Prerequisites

- JDK 7 or higher
- Apache Tomcat 7 or higher
- MySQL 5 or higher
- Maven (for dependency management)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/online-medicine-shop.git
   ```

2. **Import the project into your IDE:**
   Open your IDE (e.g., Eclipse, IntelliJ IDEA), and import the project as a Maven project.

3. **Configure the database:**
   - Create a database in MySQL.
   - Update the `db.properties` file with your database credentials.

4. **Build the project:**
   ```bash
   mvn clean install
   ```

5. **Deploy on Tomcat:**
   - Copy the WAR file from the `target` directory to the Tomcat `webapps` directory.
   - Start the Tomcat server.

6. **Access the application:**
   Open your browser and navigate to `http://localhost:8080/online-medicine-shop`.

## Usage

### Vendor

- **Login:** Vendors can log in using their credentials.
- **Add Product:** Add new products to the inventory.
- **Restock:** Update stock levels of existing products.

### Customer

- **Register/Login:** Customers can register for an account and log in.
- **Browse Products:** View and search for available medicines.
- **Purchase Medicine:** Buy medicines and view order history.

## Contact

If you have any questions or suggestions, feel free to reach out:

- **Email:** abhishekabu0155@gmail.com


Thank you for using the Online Medicine Shop! We hope it helps in managing your medicine purchases and inventory efficiently.
