
---

# 📁 File Hider Java Project

Welcome to the *File Hider Java Project*!  
This project demonstrates how to create a secure file-hiding system using *Java* and *MySQL, with additional features like **email authentication, **OTP verification, **user login, and **encryption*.  
Perfect for beginners and advanced Java programmers looking to sharpen their skills in security-focused applications.

---

## ✨ Features

- 🔒 *User Login System* (Java + MySQL)
- ✉ *Email Authentication* with OTP (One-Time Password)
- 🔐 *File Encryption and Decryption*
- 🗄 *File Hiding Mechanism*
- 📊 *User Database Management* (MySQL)
- 📧 *Send OTP via Email* (using JavaMail API)
- 🧩 *Clean and Modular Code*

---

## 🛠 Technologies Used

- *Java SE*
- *MySQL Database*
- *JavaMail API* (for email functionality)
- *JDBC* (for database connectivity)
- *Java Swing* (for GUI, optional if added)
- *Encryption Techniques* (e.g., AES or simple custom encryption)

---

## 📚 Learning Objectives

By building this project, you will learn:
- How to send *emails* using Java
- How to implement *OTP verification*
- How to *encrypt and decrypt* files
- How to perform *CRUD operations* using JDBC with MySQL
- Best practices in *Java project structuring* and *error handling*

---

## 📋 Project Setup

1. *Clone the repository:*
   bash
   git clone https://github.com/yourusername/file-hider-java.git
   cd file-hider-java
   

2. *Set up MySQL database:*
   - Create a database (e.g., file_hider_db).
   - Import the provided SQL file or manually create tables for users and file records.

3. *Configure database credentials:*
   - Open the project.
   - Update the database connection details (DB_URL, USERNAME, PASSWORD) in the Java files.

4. *Add JavaMail library:*
   - Download or add the *javax.mail.jar* to your project's classpath.

5. *Run the Project:*
   - Compile and run the project using your preferred IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or terminal.

---

## 📸 Screenshots (Optional)

Add screenshots here if you want to show login screen, OTP verification, file selection UI, etc.

---

## 📂 Project Structure


file-hider-java/
├── src/
│   ├── auth/
│   │   └── EmailSender.java
│   │   └── OTPManager.java
│   ├── db/
│   │   └── DatabaseConnector.java
│   ├── encryption/
│   │   └── FileEncryptor.java
│   ├── ui/
│   │   └── LoginScreen.java
│   │   └── MainScreen.java
│   ├── utils/
│   │   └── FileUtils.java
│   └── Main.java
├── README.md
├── database.sql
└── libs/
    └── javax.mail.jar


---

## 🚀 Future Improvements

- Implement two-factor authentication (2FA).
- Use stronger encryption algorithms like *AES-256*.
- Add a *desktop GUI* with JavaFX or Swing.
- Build an *admin dashboard* for managing users.
- Encrypt the database fields as well.

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to open issues, submit pull requests, or suggest improvements.

---

## 📜 License

This project is licensed under the *MIT License*.  
See the [LICENSE](LICENSE) file for more details.

---
