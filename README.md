# Electrabill

## Introduction  
**Electrabill** is a Java Swing–based Electricity Billing System designed to manage customer records, meter information, billing calculations, payments, and receipt generation. It provides both admin-level and customer-level functionality, allowing smooth handling of electricity billing operations.  

This project is developed using **Java**, **Swing**, **JDBC**, and **MySQL**, and runs as a desktop application with a clean graphical user interface.

---

## Features  

### 🔐 User & Admin  
- Admin login  
- User login  
- Users can view their bill and receipts  
- Users can check payment details and current amount  

### 👥 Customer Management  
- New customer registration  
- Customer details update  
- Customer deletion  
- Meter assignment & management  

### ⚡ Billing System  
- Automatic calculation of units consumed  
- Charge calculation based on tariff rules  
- Generate monthly electricity bills  
- Download and view receipts  
- View previous bill history  

### 🗂 Database Operations  
- MySQL database integration using JDBC  
- Store customer, meter, and billing data  
- Secure update/delete operations  

---

## Technology Stack  
- **Language:** Java  
- **UI Framework:** Java Swing  
- **Database:** MySQL  
- **Database Connectivity:** JDBC  
- **IDE Used:** IntelliJ IDEA  

---

## Installation  

### 📌 Prerequisites  
Ensure the following are installed:  
- Java (JDK 8 or above)  
- MySQL Server  
- IntelliJ IDEA  
- MySQL Connector/J (JDBC driver)  

---

## Setup Instructions  

### 1. Clone the Repository  
git clone https://github.com/Pritishdeygit/Electrabill.git


### 2. Open the Project in IntelliJ  
- Go to **File → Open**  
- Select the Electrabill project folder  
- Let IntelliJ load dependencies  

---

## Database Configuration  

1. Create database:  


2. Create necessary tables (customers, meters, billing, login) manually  
   or import your SQL script (if available).  

3. Open your JDBC connection file (example: `DBConnection.java`) and update:  

DB_URL = "jdbc:mysql://localhost:3306/electrabill";
DB_USER = "your_username";
DB_PASSWORD = "your_password";



---

## Running the Application  

1. Open `Main.java`  
2. Click **Run** in IntelliJ  
3. The Swing GUI will launch with full functionality  

---

## Usage  

### 👤 Customer  
- Login to view bill  
- Check payment status  
- View and download receipts  
- View previous bills  

### 🛠 Admin  
- Add new customer  
- Delete customer  
- Update details  
- Assign meters  
- Generate bills  
- View all billing records  

---




---

## Future Enhancements  
- PDF export for bills  
- Online payment integration  
- Email/SMS bill reminders  
- Role-based dashboards  

---

## About  
A Java Swing desktop application for electricity billing, customer management, and automated bill generation.


