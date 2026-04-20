# 📒 Notes Management System (No Database)

## 🔥 Project Overview

This is a simple **Notes Management Web Application** built using **Java Servlets and JSP**.
The application allows users to **add, edit, delete, and search notes** without using any database.

All notes are stored using **file handling (notes.txt)**.

---

## 🚀 Features

* 🔐 Login System (Session-based authentication)
* ➕ Add Notes
* ✏️ Edit Notes
* ❌ Delete Notes
* 🔍 Search Notes
* 💾 File-based storage (No SQL)
* 🎨 Simple and Clean UI

---

## 🛠️ Technologies Used

* Java (JDK 11+)
* JSP & Servlets (Jakarta)
* Apache Tomcat 10+
* Maven
* HTML, CSS, Bootstrap

---

## 📁 Project Structure

```
src/main/java/com/notes/
    LoginServlet.java
    LogoutServlet.java
    NoteServlet.java
    DeleteServlet.java
    EditServlet.java

src/main/webapp/
    index.jsp
    login.jsp
    addNote.jsp
    editNote.jsp
    notes.txt
    WEB-INF/web.xml
```

---

## ▶️ How to Run

1. Import project into **Apache NetBeans**
2. Set server to **Apache Tomcat**
3. Right click project → **Run Project**
4. Open in browser:

```
http://localhost:8080/NotesApp/
```

---

## 🔑 Login Credentials

```
Username: admin
Password: 123
```

---

## 💡 Key Concepts

* Servlet handling
* Session management
* File handling instead of database
* CRUD operations

---

## 📌 Future Improvements

* User Registration System
* Multiple users support
* Dark Mode UI
* Cloud deployment

---

## 👨‍💻 Author

Vikky
(Java Web Project – Notes App)
