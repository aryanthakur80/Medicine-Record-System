# 💊 Medicine Record System

A simple **Java + MySQL console-based application** to manage medicine records with full CRUD operations.

---

## 🚀 Features

* ➕ Add new medicine
* 📋 View all medicines
* ✏️ Update medicine details
* ❌ Delete medicine
* 🗄️ MySQL database integration

---

## 🛠️ Tech Stack

* **Java (Core Java)**
* **JDBC (Java Database Connectivity)**
* **MySQL**
* **SQL**

---

## 📂 Project Structure

```
Medicine-Record-System/
│
├── src/
│   ├── Main.java
│   ├── Medicine.java
│   ├── MedicineDAO.java
│   ├── DatabaseConnection.java
│   └── scripts/
│       ├── schema_script.sql
│       └── data_script.sql
│
├── mysql-connector-j-9.2.0.jar
├── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```
git clone https://github.com/aryanthakur80/Medicine-Record-System.git
cd Medicine-Record-System
```

---

### 2️⃣ Setup MySQL Database

Run the SQL scripts:

```
src/scripts/schema_script.sql
src/scripts/data_script.sql
```

---

### 3️⃣ Configure Database Connection

Open `DatabaseConnection.java` and update:

```
String url = "jdbc:mysql://localhost:3306/MedicineDB";
String user = "root";
String password = "your_password";
```

---

### 4️⃣ Compile and Run

```
cd src
javac *.java
java -cp ".;../mysql-connector-j-9.2.0.jar" Main
```

---

## 📸 Sample Output

```
Medicine Record System
1. Add Medicine
2. View All Medicines
3. Update Medicine
4. Delete Medicine
5. Exit
```

---

## 🎯 Learning Outcomes

* Understanding of **JDBC**
* Implementation of **DAO Design Pattern**
* Hands-on with **MySQL integration**
* CRUD operations in Java

---

## 🔮 Future Improvements

* Convert to **Spring Boot REST API**
* Add **Login Authentication**
* Build **Frontend UI (React / HTML)**
* Add validation & exception handling

---

## 👨‍💻 Author

**Neeraj Mishra**

* Java Backend Developer
* Passionate about Spring Boot & DSA

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
