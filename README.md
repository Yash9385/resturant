# 🍽️ QuickDine – Restaurant Management & Food Ordering Platform

QuickDine is a full-stack restaurant platform designed to make food ordering and restaurant management simple and convenient. It provides a modern user experience with a structured backend and database integration.

## 🚀 Features

- User-friendly restaurant interface
- Food browsing and ordering
- Backend REST API integration
- User authentication
- MongoDB database integration
- Secure password hashing with bcrypt
- Image management using Cloudinary
- Modular backend architecture
- Responsive frontend design

## 🛠️ Tech Stack

**Frontend**
- React.js
- JavaScript
- CSS

**Backend**
- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- JWT Authentication
- Cloudinary

## 📁 Project Structure

```text
QuickDine/
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── server.ts
│   └── package.json
│
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/Yash9385/resturant.git
cd resturant
```

### 2. Setup Backend

```bash
cd server
npm install
```

Create a `.env` file inside the server folder and configure your environment variables.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the backend:

```bash
npm run server
```

### 3. Setup Frontend

Open another terminal:

```bash
cd client
npm install
npm run dev
```

## 🔐 Environment Variables

Never upload `.env` files or expose database credentials, API keys, or JWT secrets publicly.

## 👨‍💻 Developer

**Yash Singh**

- GitHub: [@Yash9385](https://github.com/Yash9385)
- Email: yashsingh0120@gmail.com

## 📄 License

This project is available for learning and development purposes.
