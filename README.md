# 🍔 BellyBus - Food Delivery Web App

**BellyBus** is a full-featured **Food Delivery Web Application** developed using the powerful **MERN Stack** (MongoDB, Express.js, React.js, and Node.js). This project offers a seamless experience for customers to explore restaurants, place orders, and track deliveries — all in real-time.

---

## 🚀 Features

- 🔐 **User Authentication** (Signup/Login)
- 🍽️ **Browse Restaurants & Menus**
- 🛒 **Add to Cart** and **Order Management**
- 📍 **Live Order Tracking**
- 💳 **Online Payment Gateway Integration**
- 📦 **Admin Dashboard** for managing restaurants, orders & deliveries
- 📱 **Fully Responsive UI** (Mobile + Desktop)
- 📊 **Real-Time Status Updates** using WebSockets
- 🔔 **Smart Notifications** for order status
- 🌐 **Google Maps API Integration** for location & delivery tracking
- 🌟 **Review & Rating System**

---

## 🛠️ Tech Stack

| Frontend      | Backend     | Database    | Others                     |
|---------------|-------------|-------------|----------------------------|
| React.js      | Node.js     | MongoDB     | Express.js, Mongoose       |
| Redux Toolkit |             |             | Socket.IO, JWT             |
| Tailwind CSS  |             |             | Stripe/PayPal API (for payments) |
| React Router  |             |             | Google Maps API            |

---



## 🧑‍💻 How to Run Locally

# Clone the repository
git clone https://github.com/your-username/BellyBus_Food_Delivery_app.git
cd BellyBus_Food_Delivery_app

# Install backend dependencies
cd server
npm install

# Create .env file
echo "PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_config" > .env

# Start backend server
npm run dev &

# Install frontend dependencies
cd ../client
npm install

# Start frontend
npm start &

# (Optional) If admin panel exists
cd ../admin
npm install
npm start &


# Folder Structure
Food_Delivery_App/
├── client/         # React frontend
├── server/         # Node + Express backend
├── admin/          # Admin dashboard (optional)
├── README.md
└── server/.env     # Environment file
