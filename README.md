# Shuvo Bites Server 🍽️

Backend API for the **Shuvo Bites** restaurant management platform.

## 🔗 Links

- **Live API:** https://shuvo-bites-server.vercel.app
- **Client Repository:** https://github.com/saheen-shuvo/shuvo-bites-client
- **Server Repository:** https://github.com/saheen-shuvo/shuvo-bites-server

## 🚀 Features

- JWT-based authentication and role-based authorization
- Menu CRUD APIs
- User management APIs (including admin role updates)
- Cart, booking, and review APIs
- Stripe payment intent and payment history APIs
- Admin dashboard stats and order analytics APIs

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- JWT (`jsonwebtoken`)
- Stripe

## 📦 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/saheen-shuvo/shuvo-bites-server.git
   cd shuvo-bites-server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the project root and add:
   ```env
   PORT=5000
   DB_USER=your_mongodb_username
   DB_PASS=your_mongodb_password
   ACCESS_TOKEN_SECRET=your_jwt_secret
   STRIPE_SECRET_KEY=your_stripe_secret_key
   ```
4. Start the server:
   ```bash
   npm start
   ```

## 📜 Available Scripts

- `npm start` → Run the server
- `npm test` → Placeholder test script (currently not implemented)

