# MERN Stack Blog Project

## 📌 Introduction
The **MERN Stack Blog** is a full-stack web application that allows users to create, read, update, and delete blog posts. It includes user authentication, comments, and category-based filtering. This project is built using **MongoDB, Express.js, React.js, and Node.js**.

## 🚀 Features
- 📝 Create, Edit, Delete, and View Blog Posts
- 🔐 User Authentication (clerk)
- 💬 Commenting System
- 📌 Categories & Tags for Blogs
- 🏷️ Save Post Feature
- 📄 Rich Text Editor for Blog Content
- 📷 Image Uploads for Blogs
- 🌐 Responsive UI with Tailwind CSS

## 🛠️ Tech Stack
### **Frontend**
- React.js
- Tailwind CSS
- React Router
- Axios

### **Backend**
- Node.js
- Express.js
- MongoDB & Mongoose

## 📂 Folder Structure
```
mern-blog-project/
│── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── lib/
│   ├── index.js
│
│── client/
│   ├── src/
│   │   ├── components/
│   │   ├── routes/
│   │   ├── layouts/
│   │   ├── App.js
│   │   ├── index.js
│   ├── public/
│   ├── package.json
│
│── README.md
│── .env
│── package.json
```

## ⚙️ Installation & Setup
### **Backend Setup**
```sh
cd backend
npm install
```
- Create a `.env` file in the `backend` folder and add the following:
```env
MONGO=mongodb+srv://<your>@cluster0.o1vwq.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0&dbName=blog
CLERK_WEBHOOK_SECRET = 
CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLIENT_URL = 


IK_URL_ENDPOINT = 
IK_PUBLIC_KEY = 
IK_PRIVATE_KEY = 
```
- Start the backend server:
```sh
npm start
```

### **Frontend Setup**
```sh
cd client
npm install
npm run dev
```
## 🔥 Features to Improve
- Search functionality
- Dark mode
- User profile settings
- Email notifications
- Likes on comments
- Making Filter Functionable


---
Made with ❤️ by **Ashwani Kumar**
