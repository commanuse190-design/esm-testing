# Chocolate Shop – Website Development 🍫

An end-to-end e-commerce web application for managing and selling chocolate products.  
Built with scalability, performance, and clean UX in mind.

---

## 📌 Overview 1.0

The **Chocolate Shop** project is a modern web-based platform that allows users to browse, purchase, and manage chocolate products online.  
It also provides administrative capabilities for managing products, orders, and users.

---

## ✨ Key Features

- User authentication and authorization
- Product listing and detailed product pages
- Shopping cart and checkout flow
- Order and payment management
- Admin dashboard for product CRUD operations
- Task and time tracking support
- Third-party integrations (Harvest, Toggl, etc.)
- Responsive and mobile-friendly UI

---

## 🛠 Tech Stack

### Frontend
- React / Next.js
- TypeScript
- Tailwind CSS / MUI

### Backend
- Node.js
- NestJS
- TypeORM

### Database
- PostgreSQL

### DevOps & Tools
- Docker
- PM2
- GitHub Actions
- Harvest / Toggl (Time Tracking)

---

## 📁 Project Structure

```text
.
├── src
│   ├── modules
│   │   ├── auth
│   │   ├── users
│   │   ├── products
│   │   └── orders
│   ├── common
│   ├── config
│   └── main.ts
├── public
├── test
├── .env.example
├── docker-compose.yml
├── package.json
└── README.md
