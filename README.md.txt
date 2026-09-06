# Rural Connect – One Platform for Rural Communities

A full-stack web application for rural communities to access information, report problems, and connect with government services.

## 🚀 Quick Start

```bash
# Backend setup
cd backend
npm install
cp .env.example .env
# Edit .env with your MongoDB URI and OpenWeather API key
npm run seed
npm start

# Open browser
http://localhost:5000
Save and close.

***

## 📝 Step 2: Backend Core Files

### **FILE: `backend/package.json`**

Open `backend/package.json` and paste:

```json
{
  "name": "rural-connect-backend",
  "version": "1.0.0",
  "description": "Backend for Rural Connect",
  "main": "server.js",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "seed": "node seed.js"
  },
  "dependencies": {
    "bcryptjs": "^2.4.3",
    "cors": "^2.8.5",
    "dotenv": "^16.4.5",
    "express": "^4.19.2",
    "express-validator": "^7.2.0",
    "jsonwebtoken": "^9.0.2",
    "mongoose": "^8.5.0",
    "multer": "^1.4.5-lts.1",
    "node-fetch": "^2.7.0"
  },
  "devDependencies": {
    "nodemon": "^3.1.4"
  }
}