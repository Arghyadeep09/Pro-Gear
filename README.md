Pro Gear 🏏⚽🏀

A Real-Time Sports Marketplace — Buy, Sell & Bid on Sports Gear

<p align="center"> <img src="https://img.shields.io/badge/React-18.0-blue?style=for-the-badge&logo=react" /> <img src="https://img.shields.io/badge/Node.js-Express-green?style=for-the-badge&logo=node.js" /> <img src="https://img.shields.io/badge/MongoDB-Atlas-brightgreen?style=for-the-badge&logo=mongodb" /> <img src="https://img.shields.io/badge/Socket.IO-Real--Time-black?style=for-the-badge&logo=socket.io" /> <img src="https://img.shields.io/badge/TailwindCSS-Design-blueviolet?style=for-the-badge&logo=tailwind-css" /> <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" /> </p>
📌 Overview

Pro Gear is a real-time sports marketplace built using the MERN stack with Socket.IO integration.
It allows users to buy, sell, and bid on new or used sports products seamlessly.
With secure payments, real-time chat, live bidding, and a responsive UI, Pro Gear delivers a modern e-commerce experience for sports enthusiasts.

✨ Features
Core Features

✅ User Authentication (JWT + bcrypt)
✅ Product Listings (Buy / Sell sports gear)
✅ Live Auctions with real-time bidding via Socket.IO
✅ One-to-One Chat between buyers & sellers
✅ Secure Payments via Razorpay/Stripe
✅ Image uploads using Multer + Cloudinary
✅ Ratings & Reviews System
✅ Wishlist & Favorites (Future Release)

Additional Features

🔹 Responsive UI with Tailwind CSS
🔹 Advanced Search & Filtering
🔹 Notifications (in-app + email)
🔹 Admin Dashboard for moderation & analytics (Phase 4)

🛠️ Tech Stack
Category	Technology
Frontend	React, Vite, React Router, Axios, Tailwind CSS, React Toastify
Backend	Node.js, Express.js, Socket.IO
Database	MongoDB Atlas + Mongoose
Auth	JWT, bcrypt.js
Payments	Razorpay / Stripe
Image Upload	Multer + Cloudinary
Deployment	Vercel (frontend) + Render/Railway (backend)
Real-Time	WebSockets via Socket.IO
🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Pro-Gear.git
cd Pro-Gear

2️⃣ Setup Backend
cd server
npm install


Create a .env file inside server/:

PORT=5000
MONGO_URI=your_mongo_connection
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
RAZORPAY_KEY=your_key
RAZORPAY_SECRET=your_secret


Start the backend:

npm run dev

3️⃣ Setup Frontend
cd ../client
npm install


Create a .env file inside client/:

VITE_API_URL=http://localhost:5000
VITE_RAZORPAY_KEY=your_razorpay_key


Start the frontend:

npm run dev

4️⃣ Build for Production
cd client
npm run build


This generates an optimized dist/ folder for deployment.

📌 Project Structure
Pro Gear/
│── client/              # React + Vite frontend
│── server/              # Express + Socket.IO backend
│── .gitignore
│── README.md


For the full folder structure → Click Here

📸 Screenshots (Coming Soon)

UI previews will be added after initial development.

🤝 Contribution

Want to contribute? Follow these steps:

# Fork the repository
# Create a new branch
git checkout -b feature-name
# Commit your changes
git commit -m "Added a new feature"
# Push your branch
git push origin feature-name
# Create a Pull Request 🎉

📜 License

This project is MIT Licensed — free to use and modify.

📧 Contact

Developer: Arghyadeep Hari
Email: arghyahari2001@gmail.com

LinkedIn: ["https://www.linkedin.com/in/arghyadeep22/"]

⭐ Support

If you find this project helpful, don’t forget to star the repository ⭐
Your support motivates me to build more awesome projects!
