# 📱 SalesBuddy

SalesBuddy is a mobile-focused e-commerce web application designed for selling smartphones online. It provides a seamless shopping experience for customers along with a powerful admin panel for complete product, order, and inventory management.

The platform is built with scalability, performance, and security in mind, making it suitable for real-world e-commerce use cases.

---

## 🚀 Features

### 👤 User Features
- User authentication (Sign up / Login)
- Browse smartphones by brand, price, RAM, and storage
- Product search and filtering
- Product details with images and specifications
- Add to cart & checkout
- Order history and tracking
- Mobile-first, responsive UI

### 🛠️ Admin Features
- Secure admin authentication
- Add, update, and delete products
- Manage product inventory
- Order management (view & update status)
- Price and stock control
- Dashboard for business insights

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript (ES6+)
- HTML5, CSS3 / Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- RESTful APIs

### Database
- SQL

### Authentication & Security
- JWT (JSON Web Tokens)
- Role-based access (User / Admin)

---

## 📂 Project Structure
```
SalesBuddy/
│
├── Frontend
│ ├── src/
│ ├── components/
│ ├── pages/
│ └── services/
│
├── Backend
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── middlewares/
│ └── utils/
│
├── .env
├── package.json
└── README.md

```
---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js
- SQL
- Git

### Clone the Repository
```bash
git clone https://github.com/your-username/salesbuddy.git
cd salesbuddy
Backend Setup
cd server
npm install
npm run dev
Frontend Setup
cd client
npm install
npm start
