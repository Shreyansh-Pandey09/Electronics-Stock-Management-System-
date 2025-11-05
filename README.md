# ⚡ Electronics Stock Management System  

---

## 📘 Description  

This project is a **web-based Electronics Stock Management System** developed using **JSP, JDBC, and MySQL** as a part of backend development practice.  
It is designed to help manage and track the stock of electronic items efficiently.  
The system allows the user to **add new items**, **update stock quantities**, **record sales**, and **automatically reduce stock after each sale**.  

It also checks for **item availability** and prevents transactions when stock is insufficient, ensuring accurate and up-to-date records.  
All database operations (Insert, Update, Delete, Select) are handled using **PreparedStatement** to maintain data security and prevent SQL injection.  

---

## ⚙️ Technologies Used  

- **Frontend:** HTML, CSS, JSP  
- **Backend:** Java (JSP + JDBC)  
- **Database:** MySQL  
- **Server:** Apache Tomcat  

---

## 💡 Key Features  

- ➕ Add and update electronic items with brand and quantity  
- 🔄 Auto-update stock after each sale  
- ✅ Validate stock before confirming sale  
- 🧾 Store customer details with each sale  
- 🧹 Simple and clean interface for managing stock  
- 🔐 Database connection managed separately using `DBconn.jsp`  

---

## 🎯 Project Purpose  

This project was created as a **personal practice project** to learn backend logic using JSP and MySQL.  
It helped in understanding how real-time stock management systems work — including **CRUD operations**, **data validation**, and **server-side logic handling** in JSP.  

---

## 🧩 Modules  

- 📦 Stock Entry Module  
- 💰 Sales Entry Module  
- 👨‍💼 Customer Details Module  
- 🔍 Stock Update & Validation Module  

---

## 📍 How it Works (Flow Summary)  

1. 🧾 User adds new items into the stock list.  
2. 📉 When a sale is recorded, the system automatically checks if enough quantity is available.  
3. ✅ If sufficient stock exists, the system updates the quantity (reduces it).  
4. 🚫 If not, it shows a **“Not Enough Stock”** message.  
5. 💾 Sale details and customer information are stored in the database.  

---

## 👨‍💻 Developer  

**Shreyansh Pandey**  
🎓 Practice Project | ☕ JSP & MySQL Learner | 💻 Exploring Backend Development  
