# 🎓 LMS - Learning Management System

A full-stack Learning Management System that empowers users to register, explore courses, track progress, and grow their skills. Built with **React**, **Redux Toolkit**, **Express**, and **MongoDB**.

> 📡 Live Project: [Frontend](https://lms-frontend-5g2b.onrender.com) • [Backend](https://lms-backend-54gz.onrender.com)

---

## 🚀 Features

* 🧑‍💼 User Authentication (Login/Register)
* 📚 Browse and Purchase Courses
* 🎥 Video Streaming & Playback
* �� Track Learning Progress
* 📝 Profile Update & Management
* 🔐 Secure API with Cookie-based Auth
* ⚙️ Admin-ready Backend APIs

---

## 🛠️ Tech Stack

### 🔹 Frontend

* **React.js + Vite**
* **Redux Toolkit** for state management
* **Tailwind CSS** for responsive UI
* **RTK Query** for API requests

### 🔸 Backend

* **Node.js + Express.js**
* **MongoDB + Mongoose**
* **JWT & Cookies** for secure auth
* **Cloudinary** (or similar) for media handling

---

## 📦 Folder Structure

```
/frontend
  ├── components/
  ├── pages/
  ├── redux/
  └── App.jsx

/backend
  ├── routes/
  ├── controllers/
  ├── models/
  ├── database/
  └── index.js
```

---

## ⚙️ Environment Variables

Create a `.env` file in your backend root:

```env
PORT=8080
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
COOKIE_NAME=your_cookie_name
```

---

## 🧪 Installation & Run Locally

### 📦 Backend

```bash
cd backend
npm install
npm run dev
```

### 💻 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 🔐 API Routes

### User

* `POST /api/v1/user/register` - Register
* `POST /api/v1/user/login` - Login
* `GET /api/v1/user/profile` - Load Profile
* `PUT /api/v1/user/profile/update` - Update Profile

### Courses

* `GET /api/v1/course/` - Get all courses
* `POST /api/v1/course/` - Add course (admin)

### Purchases

* `POST /api/v1/purchase/:id` - Purchase a course
* `GET /api/v1/purchase/user` - Get purchased courses

### Progress

* `PUT /api/v1/progress/:id` - Update video progress

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

[MIT](LICENSE)

---

## 💡 Author

> Built by [Prit Patel](https://github.com/pritpatel2412)
