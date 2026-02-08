# 📜 Full-Stack Satinder PoetryMS

A modern **full-stack poetry management system** built using the **MERN stack**. This platform allows admins to manage poems, users, and subscribers, while readers can explore poetry and subscribe to newsletters.

---

## 🚀 Features

### 🌐 Frontend (React + Vite)

- Beautiful landing page with hero, featured poems, and testimonials
- Poem listing & detailed poem view
- Newsletter subscription
- User authentication (Login / Register)
- Responsive UI

### 🛠️ Admin Panel

- Secure admin authentication
- Add, update, and delete poems
- View registered users
- Manage newsletter subscribers
- Dashboard with stats & charts

### 🔧 Backend (Node + Express)

- RESTful API architecture
- JWT-based authentication
- Role-based access (Admin/User)
- MongoDB database with Mongoose
- Email subscription system

---

## 🧱 Tech Stack

**Frontend:**

- React
- Vite
- Tailwind CSS / Custom CSS
- Axios

**Backend:**

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Nodemailer

---

## 📁 Project Structure

```
Full-Stack Satinder Poetry
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── server.js
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   └── api
│   └── vite.config.js
```

# File Tree: Full-Stack Satinder Poetry

**Generated:** 2/8/2026, 7:15:25 PM
**Root Path:** `e:\My Projects\Full-Stack Poetry Managament System\Full-Stack Satinder Poetry`

```
├── 📁 backend
│   ├── 📁 config
│   │   └── 📄 mailer.js
│   ├── 📁 controllers
│   │   ├── 📄 authController.js
│   │   ├── 📄 poemController.js
│   │   └── 📄 subscribeController.js
│   ├── 📁 database
│   │   └── 📁 config
│   │       └── 📄 db.js
│   ├── 📁 middleware
│   │   └── 📄 authMiddleware.js
│   ├── 📁 models
│   │   ├── 📄 Poem.js
│   │   ├── 📄 SubscribeEmail.js
│   │   └── 📄 User.js
│   ├── 📁 routes
│   │   ├── 📄 authRoutes.js
│   │   ├── 📄 emailRoutes.js
│   │   ├── 📄 poemRoutes.js
│   │   └── 📄 subscribeRoutes.js
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   └── 📄 server.js
└── 📁 frontend
    ├── 📁 public
    │   ├── 📁 assets
    │   │   └── 📁 images
    │   │       └── 🖼️ main-background.jpg
    │   └── 🖼️ vite.svg
    ├── 📁 src
    │   ├── 📁 api
    │   │   └── 📄 api.js
    │   ├── 📁 assets
    │   │   └── 🖼️ react.svg
    │   ├── 📁 components
    │   │   ├── 📁 admin
    │   │   │   ├── 📁 charts
    │   │   │   │   └── 📄 OverviewChart.jsx
    │   │   │   ├── 📁 forms
    │   │   │   │   └── 📄 PoemForm.jsx
    │   │   │   ├── 📁 tables
    │   │   │   │   ├── 📄 SubscribersTable.jsx
    │   │   │   │   └── 📄 UsersTable.jsx
    │   │   │   ├── 📄 AdminLayout.jsx
    │   │   │   ├── 📄 AdminSidebar.jsx
    │   │   │   └── 📄 StatCard.jsx
    │   │   ├── 📁 home
    │   │   │   ├── 📄 About.jsx
    │   │   │   ├── 📄 CTA.jsx
    │   │   │   ├── 📄 FeaturedPoems.jsx
    │   │   │   ├── 📄 Hero.jsx
    │   │   │   ├── 📄 SocialLinks.jsx
    │   │   │   └── 📄 Testimonial.jsx
    │   │   ├── 📁 ui
    │   │   │   ├── 📄 badge.jsx
    │   │   │   ├── 📄 button.jsx
    │   │   │   ├── 📄 card.jsx
    │   │   │   ├── 📄 dialog.jsx
    │   │   │   ├── 📄 input.jsx
    │   │   │   └── 📄 skeleton.jsx
    │   │   ├── 📄 Navbar.jsx
    │   │   └── 📄 PoemCard.jsx
    │   ├── 📁 context
    │   │   └── 📄 AuthContext.jsx
    │   ├── 📁 lib
    │   │   └── 📄 utils.js
    │   ├── 📁 pages
    │   │   ├── 📁 admin
    │   │   │   ├── 📄 AddPoem.jsx
    │   │   │   ├── 📄 AdminLayout.jsx
    │   │   │   ├── 📄 Dashboard.jsx
    │   │   │   ├── 📄 Subscribers.jsx
    │   │   │   └── 📄 Users.jsx
    │   │   ├── 🎨 AdminPanel.css
    │   │   ├── 📄 AdminPanel.jsx
    │   │   ├── 📄 Home.jsx
    │   │   ├── 📄 Login.jsx
    │   │   ├── 📄 NewsletterSignup.jsx
    │   │   ├── 📄 PoemDetail.jsx
    │   │   ├── 📄 Poems.jsx
    │   │   └── 📄 Register.jsx
    │   ├── 🎨 App.css
    │   ├── 📄 App.jsx
    │   ├── 🎨 index.css
    │   └── 📄 main.jsx
    ├── ⚙️ .gitignore
    ├── 📝 README.md
    ├── ⚙️ components.json
    ├── 📄 eslint.config.js
    ├── 🌐 index.html
    ├── ⚙️ jsconfig.json
    ├── ⚙️ package-lock.json
    ├── ⚙️ package.json
    ├── ⚙️ vercel.json
    └── 📄 vite.config.js
```

---

_Generated by FileTree Pro Extension_

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/full-stack-satinder-poetry.git
cd full-stack-satinder-poetry
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create `.env` file in `backend` folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

Backend will run on:

```
http://localhost:5000
```

---

## 🔐 Authentication

- JWT-based authentication
- Protected admin routes
- Auth context on frontend

---

## 📬 Newsletter System

- Email subscription stored in database
- Admin can view all subscribers
- Ready for email campaigns

---

## 🚀 Deployment (Optional)

- **Frontend:** Vercel / Netlify
- **Backend:** Render / Railway
- **Database:** MongoDB Atlas

---

## 🧪 Future Improvements

- Role management
- Comments on poems
- Like / bookmark poems
- SEO optimization
- Dark mode

---

## 👨‍💻 Author

**Satinder Singh**
Poet ✍️ | Full-Stack Developer 💻

---

## ⭐ Support

If you like this project:

- ⭐ Star this repository
- 🍴 Fork it
- 🧑‍💻 Contribute

---

> _“Where poetry meets technology.”_
