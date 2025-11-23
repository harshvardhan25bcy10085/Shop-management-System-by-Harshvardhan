# Shop Management System

## 📌 Project Title
**Shop Management System (Tkinter + MySQL)**

## 📘 Overview of the Project
This project is a simple GUI-based Shop Management System developed using **Python (Tkinter)** and **MySQL**.  
It allows shop owners to manage products, generate customer bills, and store sales data.  
The interface is beginner‑friendly and demonstrates CRUD operations with a database.

## ⭐ Features
- Add new products  
- Delete existing products  
- View all available products  
- Generate bills for customers  
- Store sale history in the database  
- Interactive GUI built with Tkinter

## 🛠️ Technologies / Tools Used
- **Python 3**
- **Tkinter** (Graphical User Interface)
- **MySQL Database**
- **mysql-connector-python** (DB Connector)

## 🏗️ Steps to Install & Run the Project

### **1. Install Dependencies**
```
pip install mysql-connector-python
```

### **2. Start MySQL Server**
Ensure MySQL is running and update credentials inside the Python script if needed:
- user="root"
- password="Your Password for SQL"
- host="localhost"

### **3. Create/Initialize Database**
The program automatically creates:
- Database: `Shop`
- Tables: `products`, `sale`

### **4. Run the Python Script**
```bash
python shop.py
```

## 🧪 Instructions for Testing
1. Launch the application  
2. Use **Add Product** to insert sample products  
3. Use **View Products** to confirm entries  
4. Use **Delete Product** to remove any item  
5. Use **New Customer** to generate a bill  
6. Enter quantity values and check the generated bill window  

---


