# 🛍️ Shopfinity – Full-Stack E-commerce Platform

A modern, feature-rich, and scalable e-commerce web application built with cutting-edge technologies. Shopfinity offers tailored experiences for **customers**, **vendors**, and **admins**, with robust functionalities, a sleek UI, and secure payment integration.

---

## 📌 Table of Contents
- [🛠️ Technology Stack](#️technology-stack)
- [🏷️ Features & Functionalities](#features--functionalities)
- [🔄 Workflow Overview](#workflow-overview)
- [📦 Folder Structure](#folder-structure)
- [🚀 Getting Started](#getting-started)
- [✅ Testing](#testing)
- [🌐 Deployment](#deployment)
- [📊 Performance & SEO](#performance--seo)
- [📝 Summary](#summary)
- [👨‍💻 Maintainer](#maintainer)

---

## 🛠️ Technology Stack

### 🔹 Frontend
- ⚛️ **Next.js** (React + TypeScript) – SEO-friendly, fast rendering
- 🎨 **Tailwind CSS** – Utility-first CSS for responsive design
- 🌍 **Context API / Redux** – Global state management
- 🔗 **Axios** – API client for handling HTTP requests

### 🔹 Backend
- 🧠 **Node.js + Express.js** – RESTful API architecture
- 🗃️ **PostgreSQL** – Relational database
- 🛠️ **Prisma** (or Mongoose) – ORM/ODM for DB operations
- 🔐 **JWT (JSON Web Tokens)** – Authentication & authorization
- ☁️ **Cloudinary** – Media (image/video) upload and management
- 💳 **Stripe / Aamarpay** – Secure and localized payment gateway

---

## 🏷️ Features & Functionalities

### 1. 👤 Authentication & Authorization
- Secure login/register for customers, vendors, and admins.
- JWT-based role detection and route guarding.

### 2. 🛒 Product Catalog
- Browse paginated product lists with real-time search and filters (category, price, brand).
- Product detail pages with image gallery, reviews, related items.

### 3. 🧾 Shopping Cart & Checkout
- Add/update/remove cart items with live total calculation.
- Apply promo/coupon codes.
- Checkout via **Stripe or Aamarpay** with success/failure confirmation.

### 4. 🔍 Product Comparison
- Compare up to 3 products from the same category side-by-side.
- Instant comparison and easy removal.

### 5. 📦 Order Management
- Customers place and track orders.
- Vendors view/manage their orders.
- Admins monitor platform-wide transactions.

### 6. ⭐ Ratings & Reviews
- Users can leave ratings and reviews after purchase.
- Vendors can respond to reviews to build trust.

### 7. 🧑‍💼 Vendor Dashboard
- Add/edit/delete products.
- Duplicate product listing.
- Monitor inventory and receive stock alerts.
- Manage shop profile.

### 8. 🛠️ Admin Dashboard
- Manage users and vendors (ban/unban/delete).
- Approve or moderate product listings.
- Manage categories dynamically.
- Monitor all financial transactions and platform analytics.

### 9. 🕘 Recently Viewed
- Tracks and shows the last 10 products a user viewed for quick navigation.

### 10. 📱 Fully Responsive Design
- Seamless experience on all devices — desktop, tablet, mobile.

---

## 🔄 Workflow Overview

### 👥 User Journey:
`Register/Login → Browse Products → Add to Cart/Compare → Checkout → Review`

### 🛍️ Vendor Journey:
`Register as Vendor → Setup Shop → Add Products → Manage Orders → Respond to Reviews`

### 🛡️ Admin Journey:
`Login → Manage Users & Vendors → Approve Products → Monitor Transactions`

### 🔄 Data Flow:
- Frontend communicates with backend via **Axios + RESTful API**
- Backend handles business logic, authorization, and database operations
- Assets uploaded to **Cloudinary**, payments handled via **Stripe / Aamarpay**

---

## 📦 Folder Structure (Next.js-based)

```
Shopfinity/
├── public/                 # Static files (images, favicon, etc.)
├── src/
│   ├── assets/             # Custom images/icons
│   ├── components/         # Reusable components (ProductCard, CompareCard, etc.)
│   ├── context/            # Global context (Auth, Cart, etc.)
│   ├── hooks/              # Custom React hooks
│   ├── pages/              # Routing and pages (Next.js)
│   ├── styles/             # Tailwind and global styles
│   └── utils/              # Helper functions (validation, API calls, etc.)
```

---

## 🚀 Getting Started

### ✅ Prerequisites
- Node.js ≥ 18.x
- PostgreSQL
- Cloudinary Account
- Stripe or Aamarpay API Keys

### 📥 Installation

```bash
git clone https://github.com/yourusername/shopfinity.git
cd shopfinity
npm install
```

### ⚙️ Environment Variables

Create a `.env.local` file with:

```env
DATABASE_URL=your_database_url
JWT_SECRET=your_jwt_secret
CLOUDINARY_API_KEY=xxx
STRIPE_SECRET_KEY=xxx
AAMARPAY_STORE_ID=xxx
...
```

### ▶️ Run Locally

```bash
npm run dev
```

Visit: `http://localhost:3000`

---

## ✅ Testing

```bash
npm test
```

- Uses **Jest** and **React Testing Library**.
- More testing features coming soon.

---

## 🌐 Deployment

You can deploy Shopfinity using:

| Service    | Purpose     | Example                        |
|------------|-------------|--------------------------------|
| **Vercel** | Frontend    | `https://shopfinity.vercel.app` |
| **Render** | Backend/API | `https://shopfinity-api.render.com` |
| **PlanetScale** | DB    | MySQL alternative if needed     |
| **Railway** | All-in-one | Backend + DB hosting           |

---

## 📊 Performance & SEO

- ✅ **Image Optimization** – via `next/image`
- ✅ **Server-Side Rendering (SSR)** – for SEO & speed
- ✅ **Lazy Loading** – images/components load when needed
- ✅ **Structured Data + Meta Tags** – improves Google indexing

---

## 📝 Summary

> **Shopfinity** is more than just a shopping app — it's a powerful, modular, and production-ready platform for vendors and customers alike. With advanced features like product comparison, vendor-specific dashboards, secure payments, and responsive design, Shopfinity is built to scale and impress.

---

## 👨‍💻 Maintainer

**👋 Roman Hasan Sourab**  
🎓 ID: 24205066, Canadian University of Bangladesh  
📧 [Email](mailto:sowravhasan101@gmail.com)  
🌐 [Portfolio](https://sowrav-hasan.netlify.app/)  
🔗 [GitHub](https://github.com/romanhasansourab)
