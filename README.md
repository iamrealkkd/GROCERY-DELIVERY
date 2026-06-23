# 🛒 Instacart - Grocery Delivery App

A full-stack grocery delivery platform built with the PERN Stack. Browse products, manage orders, and track deliveries — with background job processing via Inngest and image uploads via Cloudinary.

---

## 🚀 Features

- 🔐 User Authentication & Authorization
- 🛍️ Browse Products by Category
- 🔍 Search Products
- 🛒 Shopping Cart
- 📦 Order Management
- 🔧 Admin Dashboard
- ✏️ Product CRUD Operations
- 🖼️ Cloudinary Image Uploads
- 💳 Stripe Payments
- 💅 Responsive Design

---

## 🏠 Home Page
<img width="1291" height="660" alt="image" src="https://github.com/user-attachments/assets/1b52b897-fd4f-4040-a508-582b9e129e26" />

---

## 🛍️ Products Page
<img width="1086" height="661" alt="image" src="https://github.com/user-attachments/assets/63f76282-41a0-4fc5-986c-7d8322f6879e" />

---

## 🔧 Admin Dashboard
<img width="1158" height="681" alt="image" src="https://github.com/user-attachments/assets/d26066fe-3d56-4ae4-8140-bdba30b38f61" />

---

## 🛠️ Tech Stack

| Frontend | Backend | Database | Services |
|----------|---------|----------|----------|
| React JS | Node.js | PostgreSQL (Neon) | Cloudinary |
| Tailwind CSS | Express.js | | Inngest |
| | | | Stripe |

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v18+
- PostgreSQL / Neon Database URL
- Cloudinary Account
- Inngest Account
- Stripe Account

### Installation

```bash
git clone https://github.com/iamrealkkd/GROCERY-DELIVERY.git
cd GROCERY-DELIVERY
```

```bash
# Install server dependencies
cd server
npm install

# Install client dependencies (new terminal)
cd ../client
npm install
```

### Run Locally

```bash
# Start server
cd server
npm run dev

# Start client (new terminal)
cd client
npm run dev
```

---

## 🔑 Environment Variables

**server/.env**
```env
DATABASE_URL=your_neon_postgres_url
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
INNGEST_EVENT_KEY=
INNGEST_SIGNING_KEY=
STRIPE_SECRET_KEY=
```

**client/.env**
```env
VITE_API_URL=http://localhost:5000
```

---

## 📦 Deployment

Deploy on Vercel:

```bash
vercel
```

---

## 👨‍💻 Author

Made with ❤️ by [Krishna](https://github.com/iamrealkkd)
