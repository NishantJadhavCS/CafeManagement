# ☕ Cafe Management System

Welcome to the **Cafe Management System** – a web-based application for managing users, menu items, and orders in a cafe. This system allows the **admin** to efficiently handle operations and track order insights through interactive charts.

---

## 🌟 Features  

✔ **Admin Panel:** Manage users, menu items, and orders  
✔ **CRUD Operations:** Create, read, update, and delete users & items  
✔ **Order Management:** Place multiple orders at once  
✔ **Analytics & Insights:** Track orders using bar charts  
✔ **User Authentication:** Secure login system  
✔ **Django Tailwind UI:** Responsive & modern design  

---

## 🛠️ **Installation Guide**  

Follow these steps to set up the project on your local machine.  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/NishantJadhavCS/CafeManagement.git
cd CafeManagement
```
### 2️⃣ **Create a Virtual Environment**

For Linux & macOS
```bash
python -m venv venv
source venv/bin/activate
```

For Windows(CMD)
```bash
python -m venv venv
venv\Scripts\activate
```

## **3️⃣ Install Required Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Set Up Environment Variables**

Create a .env file in the project root (where manage.py is located) and add:

DATABASE_NAME=mydatabase
DATABASE_USER=myuser
DATABASE_PASSWORD=mypassword
DATABASE_HOST=localhost
DATABASE_PORT=5432

### **5️⃣ Install & Build Tailwind Theme**
This project uses Django Tailwind for styling. Run:
```bash
python manage.py tailwind install
python manage.py tailwind build
```


### **6️⃣ Run Database Migrations**
```bash
python manage.py migrate
```

### **7️⃣ Collect Static Files**
```bash
python manage.py collectstatic --noinput
```

### **8️⃣ Create a Superuser (For Admin Access)**
```bash
python manage.py createsuperuser
```

### **9️⃣ Run the Development Server**
```bash
python manage.py runserver
```

**Open http://127.0.0.1:8000/ in your browser 🎉**

### **🎯 How to Use the System**

**🔹 Admin Functionalities**
✅ Log in to the Admin Dashboard
✅ Manage Users (Create, Update, Delete)
✅ Manage Menu Items (Add, Edit, Delete items)
✅ Place Orders for customers
✅ View Order Insights (Bar charts for sales & trends)

**🔹 Customers**
Customers can view available items and place orders.

📊 Order Insights & Analytics
The system provides visual insights into cafe operations:
📊 Order Trends: Track orders based on date ranges
📊 Most Ordered Items: See popular items in bar charts
📊 Customer Insights: View orders by customer
