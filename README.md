# 🛍️ Inventory Management System (IMS) - Backend

## 📌 Overview
The **Inventory Management System (IMS)** is a backend project built with Python to efficiently manage inventory, track stock levels, handle supplier details, and manage customer orders. It is designed for small businesses to streamline product management and improve sales tracking.

---

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Framework**: Django
- **Database**: PostgreSQL
- **API**: RESTful API
- **Authentication**: JWT

---

## 🌟 Features
✅ User Authentication & Role Management  
✅ Product Management (Add, Update, Delete)  
✅ Real-time Inventory Tracking  
✅ Supplier Management  
✅ Sales Order Management  
✅ Reports and Analytics  
✅ Notification System for Low Stock Alerts  

---

## 📂 Project Structure
inventory_management_system/ │ ├── backend/ │ ├── app/ │ │ ├── models/ │ │ ├── views/ │ │ ├── controllers/ │ │ ├── services/ │ │ └── utils/ │ ├── config/ │ ├── routes/ │ ├── tests/ │ └── static/ │ ├── database/ │ ├── migrations/ │ └── seed_data/ │ └── docs/

---

## 🚀 API Endpoints
| Endpoint            | Method | Description           |
|-----------------|---------|-------------------|
| `/api/auth/register` | POST   | Register a new user |
| `/api/product/add` | POST   | Add a new product |
| `/api/inventory/update` | PATCH | Update stock |
| `/api/orders/all` | GET   | Retrieve all orders |
| `/api/reports/sales` | GET   | Generate sales report |

---

## 💡 Installation Guide
1. Clone the repository:
```bash
git clone https://github.com/yourusername/inventory-management-system.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the database migrations:
```bash
python manage.py migrate
```
4. Start the development server:
```bash
python manage.py runserver
```

---

## ✅ Future Enhancements
- Implement role-based access control (RBAC)
- Add API documentation with Swagger
- Integrate cloud storage for product images

---

## 👤 Author
Elmar T. Panganiban
- 📧 pngnbn.elmar@gmail.com
- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/elmar-panganiban/)

---

## 📄 License
This project is licensed under the MIT License.