# Enterprise Banking System

<p align="center">
<img width="1031" height="515" alt="Banner" src="https://github.com/user-attachments/assets/36c8bd31-5aa6-417c-937e-cff718bd2f09" />

</p>

A JavaFX-based desktop banking application that simulates the core workflows of a modern retail banking platform. The application supports user authentication, account management, transaction processing, and persistent local data storage while demonstrating object-oriented software design, modular architecture, and financial transaction workflows.

The application runs locally and stores application data using Java object serialization, allowing account information and transaction history to persist between sessions.

---

## Author

Developed as a software engineering project focused on desktop application development, object-oriented design, and financial system simulation using Java and JavaFX.

---

# Features

- User registration and login authentication
- User profile management
- Chequing and savings account creation
- Deposit and withdrawal processing
- Account-to-account transfers
- Transaction history tracking
- Persistent local data storage
- JavaFX graphical user interface
- Object-oriented class architecture

---

# Technology Stack

| Technology                  | Purpose                          |
|-----------------------------|----------------------------------|
| Java                        | Core application development     |
| JavaFX                      | Desktop graphical user interface |
| Object-Oriented Programming | Application architecture         |
| Java Serialization          | Local data persistence           |

---

# System Architecture

The application follows a modular architecture separating user interface components, business entities, and application logic.

## Core Models

- User
- Account
- SavingsAccount
- ChequingAccount
- Transaction
- Bank

## User Interface Components

JavaFX views provide interfaces for:

- Login and registration
- Account dashboard
- Deposits
- Withdrawals
- Transfers
- Transaction history

The separation between models and views improves maintainability and allows future expansion into a larger banking platform.

---

# Key Capabilities

## Authentication

Users can create accounts and access their banking profile through the JavaFX interface.

Future improvements include implementing password hashing and enhanced authentication security.

## Account Management

Users can:

- Create chequing and savings accounts
- View account balances
- Manage multiple accounts

## Transaction Processing

The system supports:

- Deposits
- Withdrawals
- Internal account transfers

All transactions are recorded and stored for account history tracking.

## Data Persistence

Application data is stored through Java object serialization, allowing users to continue using their accounts after restarting the application.

---

# Skills Demonstrated

- Java Application Development
- Object-Oriented Programming
- Desktop GUI Development
- Software Architecture
- Financial Transaction Modeling
- Data Serialization
- File-Based Persistence
- UI Design
- State Management

---

# Future Improvements

- PostgreSQL/MySQL database integration
- Password hashing and improved authentication
- Spring Boot backend services
- REST API development
- Role-based authorization
- Unit testing with JUnit
- Maven/Gradle build automation
- Docker containerization
- Cloud deployment

---

# Prerequisites

Before running the application, ensure you have:

- Java Development Kit (JDK) 17 or higher
- JavaFX SDK installed
- Proper JavaFX module configuration

---

# Running the Application

## Clone Repository

```bash
git clone https://github.com/ADMSI14/enterprise-banking-platform.git
```
Navigate into the project:

```bash
cd enterprise-banking-platform
```

Windows

```bash
win.bat
```

Linux

```bash
sh linux.sh
```

macOS

```bash
sh mac.sh
```
---

# Screenshots

- Login screen
<img width="328" height="364" alt="Login screen" src="https://github.com/user-attachments/assets/1087b2bf-7ffd-417a-8728-87aa908be53c" />

- Registration screen
<img width="378" height="512" alt="Registration screen" src="https://github.com/user-attachments/assets/8ebfbe0c-ef30-4480-aeaf-8fb9a1fd9559" />

- Error screen
<img width="484" height="342" alt="Error screen" src="https://github.com/user-attachments/assets/91367085-b53a-4ddc-9996-d7862c220bf8" />

- Chequing account dashboard
<img width="1028" height="520" alt="Chequing account dashboard" src="https://github.com/user-attachments/assets/1a584046-0a60-4160-b21c-a0146886432a" />

- Deposit screen 
<img width="1032" height="526" alt="Deposit screen" src="https://github.com/user-attachments/assets/1c495cdb-f585-4237-bdaa-939c8c9bc756" />

- Transfer money screen
<img width="1039" height="526" alt="Transfer money screen" src="https://github.com/user-attachments/assets/46f05e91-90da-4d9b-8e9c-139fd76ee145" />

- All transaction screen
<img width="1091" height="547" alt="All transaction screen" src="https://github.com/user-attachments/assets/42c9ce1d-7a32-4d10-9204-25804c1f5fa0" />

---
# License 
This project is licensed under the MIT License.

