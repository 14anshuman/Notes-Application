# 📝 Notes Application (MERN + Tailwind CSS)

[![GitHub Repo](https://img.shields.io/badge/Repo-Notes--Application-blue?logo=github)](https://github.com/14anshuman/Notes-Application)
[![Stars](https://img.shields.io/github/stars/14anshuman/Notes-Application?style=social)](https://github.com/14anshuman/Notes-Application/stargazers)
[![Forks](https://img.shields.io/github/forks/14anshuman/Notes-Application?style=social)](https://github.com/14anshuman/Notes-Application/network/members)

A full-stack **Notes Application** built using the **MERN stack** (**MongoDB, Express.js, React.js, Node.js**) and styled with **Tailwind CSS**.  
It lets users **create, update, delete, and manage notes** efficiently with a clean and modern interface.  


📂 **Repository**: [Notes Application](https://github.com/14anshuman/Notes-Application)

---

## ✨ Features

- ✅ **Add Notes** – Create new notes easily.  
- ✅ **Edit Notes** – Update existing notes.  
- ✅ **Delete Notes** – Remove notes you no longer need.  
- ✅ **View Notes** – Organized list of all saved notes.  
- ✅ **Responsive UI** – Built with **Tailwind CSS** for mobile-first design.  
- ✅ **Fast & Scalable** – Powered by **MERN stack** with RESTful APIs.  

---

## 🛠️ Tech Stack

**Frontend**  
- ⚛️ React.js  
- 🎨 Tailwind CSS
- 📦 Redux (state management) 

**Backend**  
- 🟢 Node.js  
- ⚡ Express.js  

**Database**  
- 🍃 MongoDB (NoSQL database to store notes)  

---

## 📂 Project Structure

```
Notes-Application/
│
├── backend/ # Express + Node.js backend
│ ├── models/ # Mongoose models
│ ├── routes/ # API routes
│ └── server.js # Main server entry point
│
├── frontend/ # React + Tailwind CSS frontend
│ ├── src/
│ │ ├── components/ # Reusable components
│ │ ├── pages/ # Application pages
│ │ └── App.js # Root component
│
└── README.md # Documentation 
```
## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/14anshuman/Notes-Application.git
cd Notes-Application
```
### 2️⃣ Install Dependencies
## Backend
```bash
cd backend
npm install
```
## Frontend
```bash
cd frontend
npm install
```
### 3️⃣ Setup Environment Variables
In backend/.env file:
```bash
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4️⃣ Run the Application

Start backend
```bash
cd backend
npm run dev
```
Start frontend
```bash
cd frontend
npm start
```
The app will be available at:

Frontend → http://localhost:3000

Backend API → http://localhost:5000


## 📈 Future Enhancements
🔒 User authentication (login & register)
🌙 Dark mode support
📂 Organize notes with categories/tags
☁️ Cloud deployment (Vercel / Render / Netlify + MongoDB Atlas)
