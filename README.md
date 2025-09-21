# Retail POS & Inventory Manager

A full-stack Retail Point of Sale (POS) and Inventory Management system built for small to medium businesses. This desktop-style web application helps manage sales, inventory, customers, and reports efficiently.

---

## Features

- User roles & authentication (Admin, Manager, Cashier)
- Product management with SKU, barcode, categories, suppliers
- Sales processing with barcode scanning, discounts, taxes, receipts
- Real-time inventory tracking & stock alerts
- Customer management and purchase history
- Detailed sales, profit, and inventory reporting
- Data backup and restore functionality

---

## Technology Stack

### Frontend
- React with TypeScript & Vite
- Tailwind CSS with Shadcn/UI & Radix UI
- React Hook Form & Zod for validation
- TanStack Query for server state management
- Wouter for routing

### Backend
- Node.js with Express.js
- TypeScript & ES Modules
- Drizzle ORM with PostgreSQL
- BCrypt password hashing
- Session-based authentication

### Database
- PostgreSQL (Neon Serverless)
- Drizzle Kit for migrations & schema management

---

## Setup Instructions

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/retail-pos-inventory.git
   cd retail-pos-inventory
