# ✨ Full-Stack Satinder Poetry Management System

---

Full-Stack Poetry Publishing & Content Management Platform

MERN-Based Poetry Publishing Platform with Admin Dashboard & Subscriber System

---

A modern full-stack poetry platform built with the MERN ecosystem.

This project provides:

- Public poetry website
- User authentication system
- Newsletter subscription system
- Admin dashboard
- Poetry management system
- User management
- Responsive UI/UX
- RESTful backend API

---

# 📸 Project Overview

The **Full-Stack Satinder Poetry Management System** is a production-style MERN application designed for publishing and managing poetry content.

The platform includes:

## 🌐 Public Platform

Users can:

- Explore poems
- Read poem details
- Register/login
- Subscribe to newsletters
- View profile pages

## 🛠️ Admin Dashboard

Admins can:

- Add poems
- Edit poems
- Delete poems
- Manage users
- Manage subscribers
- View analytics/dashboard

---

# 🧱 Tech Stack

## Frontend

| Technology      | Purpose             |
| --------------- | ------------------- |
| React 18        | Frontend library    |
| Vite            | Build tool          |
| Tailwind CSS v4 | Styling             |
| ShadCN UI       | UI components       |
| React Router v7 | Routing             |
| Axios           | API requests        |
| Sonner          | Toast notifications |
| Recharts        | Charts & analytics  |
| Lucide React    | Icons               |

---

## Backend

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Node.js    | Runtime                   |
| Express.js | Backend framework         |
| MongoDB    | Database                  |
| Mongoose   | ODM                       |
| JWT        | Authentication            |
| bcryptjs   | Password hashing          |
| Nodemailer | Email service             |
| Resend     | Email API                 |
| dotenv     | Environment configuration |

---

# 📂 Project Structure

```bash
Full-Stack Satinder Poetry/
├── backend/
├── frontend/
└── README.md
```

````

# File Tree: Full-Stack Satinder Poetry

**Generated:** 5/23/2026, 4:46:44 PM
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
│   │   ├── 📄 subscribeRoutes.js
│   │   └── 📄 userRoutes.js
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   └── 📄 server.js
├── 📁 frontend
│   ├── 📁 public
│   │   ├── 📁 assets
│   │   │   └── 📁 images
│   │   │       ├── 🖼️ bird.jpg
│   │   │       ├── 🖼️ chair.png
│   │   │       ├── 🖼️ dog.png
│   │   │       ├── 🖼️ leaves.png
│   │   │       └── 🖼️ main-background.jpg
│   │   ├── 📄 robots.txt
│   │   ├── ⚙️ sitemap.xml
│   │   └── 🖼️ vite.svg
│   ├── 📁 src
│   │   ├── 📁 api
│   │   │   └── 📄 api.js
│   │   ├── 📁 assets
│   │   │   ├── 📁 images
│   │   │   │   ├── 🖼️ Image1.png
│   │   │   │   ├── 🖼️ Image2.png
│   │   │   │   ├── 🖼️ Image3.png
│   │   │   │   ├── 🖼️ Image4.png
│   │   │   │   └── 🖼️ Satinder Poetry - Logo.png
│   │   │   └── 🖼️ react.svg
│   │   ├── 📁 components
│   │   │   ├── 📁 admin
│   │   │   │   ├── 📁 charts
│   │   │   │   │   └── 📄 OverviewChart.jsx
│   │   │   │   ├── 📁 forms
│   │   │   │   │   └── 📄 PoemForm.jsx
│   │   │   │   ├── 📁 tables
│   │   │   │   │   ├── 📄 SubscribersTable.jsx
│   │   │   │   │   └── 📄 UsersTable.jsx
│   │   │   │   ├── 📄 AdminLayout.jsx
│   │   │   │   ├── 📄 AdminSidebar.jsx
│   │   │   │   ├── 📄 DeleteDialog.jsx
│   │   │   │   └── 📄 StatCard.jsx
│   │   │   ├── 📁 home
│   │   │   │   ├── 📄 About.jsx
│   │   │   │   ├── 📄 CTA.jsx
│   │   │   │   ├── 📄 FeaturedPoems.jsx
│   │   │   │   ├── 📄 Hero.jsx
│   │   │   │   ├── 📄 SocialLinks.jsx
│   │   │   │   ├── 📄 StoriesSection.jsx
│   │   │   │   └── 📄 Testimonial.jsx
│   │   │   ├── 📁 ui
│   │   │   │   ├── 📄 alert-dialog.jsx
│   │   │   │   ├── 📄 badge.jsx
│   │   │   │   ├── 📄 button.jsx
│   │   │   │   ├── 📄 card.jsx
│   │   │   │   ├── 📄 dialog.jsx
│   │   │   │   ├── 📄 input.jsx
│   │   │   │   └── 📄 skeleton.jsx
│   │   │   ├── 📄 AuthRoute.jsx
│   │   │   ├── 📄 AuthToast.jsx
│   │   │   ├── 📄 DeveloperCredit.jsx
│   │   │   ├── 📄 Footer.jsx
│   │   │   ├── 📄 Navbar.jsx
│   │   │   ├── 📄 PoemCard.jsx
│   │   │   ├── 📄 ProtectedRoute.jsx
│   │   │   ├── 📄 ScrollToTop.jsx
│   │   │   ├── 📄 ScrollToTopButton.jsx
│   │   │   ├── 📄 SubscriptionErrorModal.jsx
│   │   │   └── 📄 SubscriptionSuccessModal.jsx
│   │   ├── 📁 context
│   │   │   └── 📄 AuthContext.jsx
│   │   ├── 📁 layouts
│   │   │   └── 📄 PublicLayout.jsx
│   │   ├── 📁 lib
│   │   │   └── 📄 utils.js
│   │   ├── 📁 pages
│   │   │   ├── 📁 admin
│   │   │   │   ├── 📄 AddPoem.jsx
│   │   │   │   ├── 📄 AdminLayout.jsx
│   │   │   │   ├── 📄 Dashboard.jsx
│   │   │   │   ├── 📄 EditPoem.jsx
│   │   │   │   ├── 📄 Poems.jsx
│   │   │   │   ├── 📄 Subscribers.jsx
│   │   │   │   └── 📄 Users.jsx
│   │   │   ├── 🎨 AdminPanel.css
│   │   │   ├── 📄 AdminPanel.jsx
│   │   │   ├── 📄 Home.jsx
│   │   │   ├── 📄 Login.jsx
│   │   │   ├── 📄 NewsletterSignup.jsx
│   │   │   ├── 📄 NotFound.jsx
│   │   │   ├── 📄 PoemDetail.jsx
│   │   │   ├── 📄 Poems.jsx
│   │   │   ├── 📄 Profile.jsx
│   │   │   └── 📄 Register.jsx
│   │   ├── 🎨 App.css
│   │   ├── 📄 App.jsx
│   │   ├── 🎨 index.css
│   │   └── 📄 main.jsx
│   ├── ⚙️ .gitignore
│   ├── 📝 README.md
│   ├── ⚙️ components.json
│   ├── 📄 eslint.config.js
│   ├── 🌐 index.html
│   ├── ⚙️ jsconfig.json
│   ├── ⚙️ package-lock.json
│   ├── ⚙️ package.json
│   ├── ⚙️ vercel.json
│   └── 📄 vite.config.js
└── 📝 README.md
```

---

_Generated by FileTree Pro Extension_

---

# 📁 Backend Structure

```bash
backend/
├── config/
├── controllers/
├── database/
├── middleware/
├── models/
├── routes/
├── server.js
└── package.json
```

## Backend Features

### 🔐 Authentication System

- User registration
- User login
- JWT authentication
- Protected routes
- Password hashing

### 📝 Poetry CRUD System

- Create poems
- Read poems
- Update poems
- Delete poems

### 📧 Newsletter System

- Email subscriptions
- Subscriber management
- Email sending

### 👤 User Management

- User data handling
- Admin protection

---

# 📁 Frontend Structure

```bash
frontend/
├── public/
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── layouts/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
├── package.json
└── vite.config.js
```

---

# 🎨 Frontend Features

## 🌐 Public Website

- Hero section
- Featured poems
- About section
- Stories section
- Testimonials
- Newsletter signup

## 🔐 Authentication

- Login
- Register
- Protected routes
- Auth context

## 📝 Poetry Pages

- All poems page
- Individual poem details
- Dynamic rendering

## 👤 User Features

- User profile page
- Authentication persistence

## 🛠️ Admin Dashboard

- Dashboard overview
- Charts & analytics
- Manage poems
- Manage users
- Manage subscribers

---

# 🛣️ API Routes

## Authentication

```bash
/api/auth
```

## Poems

```bash
/api/poems
```

## Newsletter

```bash
/api/subscribe
```

## Email

```bash
/api/email
```

## Users

```bash
/api/users
```

---

# 🔒 Authentication Flow

Authentication system includes:

- JWT token authentication
- Password hashing using bcryptjs
- Protected admin routes
- Auth middleware
- Cookie parsing support

---

# 📧 Email System

Integrated email services:

- Nodemailer
- Resend API

Used for:

- Newsletter subscriptions
- Email notifications

---

# ⚡ Environment Configuration

The backend dynamically loads environment files:

```js
const envFile =
  process.env.NODE_ENV === "production"
    ? ".env.production"
    : ".env.development";
```

---

# 📄 Environment Variables

## Backend `.env.development`

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret
CLIENT_URL=http://localhost:5173
RESEND_API_KEY=your_resend_key
```

---

## Frontend `.env.development`

```env
VITE_API_URL=http://localhost:5000/api
```

---

# 🚀 Installation Guide

# 1️⃣ Clone Repository

```bash
git clone <repository-url>
```

---

# 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

---

# 3️⃣ Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

# ▶️ Running the Project

# Backend Development

```bash
cd backend
npm run dev
```

Backend runs on:

```bash
http://localhost:5000
```

---

# Frontend Development

```bash
cd frontend
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# 🏗️ Production Build

## Frontend Build

```bash
npm run build
```

---

## Frontend Preview

```bash
npm run preview
```

---

## Backend Production

```bash
npm start
```

---

# 📱 Responsive Design

The application is optimized for:

- Desktop
- Laptop
- Tablet
- Mobile devices

---

# 🎨 UI Features

## Modern UI Stack

Using:

- Tailwind CSS v4
- ShadCN UI
- Sonner Toasts
- Lucide Icons

---

# 📊 Admin Dashboard Features

Includes:

- Statistics cards
- User analytics
- Subscriber analytics
- Charts
- Poem management

---

# 🛡️ Security Features

Implemented:

- JWT authentication
- Password hashing
- Protected routes
- Environment variables
- Auth middleware

Recommended future improvements:

- Helmet
- Rate limiting
- Input validation
- CSRF protection

---

# 🧪 Testing

Current testing status:

```bash
No tests yet
```

Recommended tools:

- Jest
- Supertest
- React Testing Library

---

# 🌍 Deployment

## Frontend Deployment

Recommended:

- Vercel
- Netlify

## Backend Deployment

Recommended:

- Render
- Railway
- Fly.io

---

# 📈 Future Improvements

Potential future upgrades:

## Frontend

- Dark mode
- React Query
- React Hook Form
- Zod validation
- Search functionality
- Likes & comments
- Pagination

## Backend

- Role-based authorization
- Swagger API docs
- Refresh tokens
- Unit testing
- Email templates
- File uploads

---

# 👨‍💻 Developer

Developed by:

## Satinder Singh Sall

---

# 📄 License

Licensed under the ISC License.

---

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
````

# Frontend README.md

````md
# 🎨 Full-Stack Satinder Poetry — Frontend

A modern React-based frontend for the **Full-Stack Satinder Poetry Management System**.

Built with:

- React 18
- Vite
- Tailwind CSS v4
- ShadCN UI
- React Router v7
- Axios
- Recharts
- Sonner Toasts

This frontend provides:

- Public poetry website
- Authentication system
- Newsletter subscription
- User profile management
- Responsive UI/UX
- Admin dashboard
- Protected admin routes
- Poetry management system

---

# 📂 Project Structure

```bash
frontend/
├── public/
├── src/
│   ├── api/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── layouts/
│   ├── lib/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
├── vite.config.js
└── README.md
```
````

---

# 🚀 Features

## 🌐 Public Website

- Beautiful landing page
- Featured poems section
- About section
- Stories section
- Testimonials
- Newsletter signup
- Social media integration

## 🔐 Authentication

- User registration
- User login
- Protected routes
- Auth context management
- Secure token-based authentication

## 📝 Poetry System

- View all poems
- Individual poem detail pages
- Responsive poem cards
- Dynamic poem rendering

## 👤 User Features

- Profile page
- Session persistence
- Authentication-based navigation

## 🛠️ Admin Dashboard

- Dashboard analytics
- Manage poems
- Add poems
- Edit poems
- Manage users
- Manage subscribers
- Overview charts

## 🎨 UI/UX

- Responsive design
- Smooth scrolling
- Scroll-to-top button
- Toast notifications
- Loading skeletons
- Clean modern UI

---

# ⚙️ Tech Stack

| Technology      | Purpose             |
| --------------- | ------------------- |
| React 18        | Frontend library    |
| Vite            | Build tool          |
| Tailwind CSS v4 | Styling             |
| ShadCN UI       | UI components       |
| React Router v7 | Routing             |
| Axios           | API requests        |
| Sonner          | Toast notifications |
| Recharts        | Admin charts        |
| Lucide React    | Icons               |
| React Icons     | Additional icons    |

---

# 📦 Installed Dependencies

## Main Dependencies

```json
{
  "react": "^18.3.1",
  "react-dom": "^18.3.1",
  "react-router-dom": "^7.2.0",
  "axios": "^1.8.1",
  "recharts": "^2.15.4",
  "sonner": "^2.0.7",
  "lucide-react": "^0.563.0",
  "tailwindcss": "^4.1.18"
}
```

---

# 🧩 Important Components

## Layout Components

### `PublicLayout.jsx`

Handles:

- Navbar
- Footer
- Public page layout

### `AdminLayout.jsx`

Handles:

- Sidebar
- Admin navigation
- Dashboard structure

---

# 🔒 Route Protection

## `ProtectedRoute.jsx`

Protects admin-only routes.

## `AuthRoute.jsx`

Protects authenticated user routes.

---

# 🛣️ Routes

## Public Routes

| Route         | Description       |
| ------------- | ----------------- |
| `/`           | Home page         |
| `/login`      | Login page        |
| `/register`   | Register page     |
| `/poems`      | Poems listing     |
| `/poems/:id`  | Poem detail       |
| `/newsletter` | Newsletter signup |
| `/profile`    | User profile      |

---

## Admin Routes

| Route                  | Description        |
| ---------------------- | ------------------ |
| `/admin`               | Dashboard          |
| `/admin/poems`         | Manage poems       |
| `/admin/add-poem`      | Add new poem       |
| `/admin/edit-poem/:id` | Edit poem          |
| `/admin/users`         | Manage users       |
| `/admin/subscribers`   | Manage subscribers |

---

# 🔌 API Integration

API calls are handled through:

```bash
src/api/api.js
```

Using Axios for:

- Authentication
- CRUD operations
- Newsletter subscriptions
- User management

---

# 📱 Responsive Design

The frontend is fully responsive and optimized for:

- Desktop
- Laptop
- Tablet
- Mobile devices

---

# 🔥 Toast Notifications

Using Sonner:

```jsx
<Toaster richColors position="top-right" />
```

Used for:

- Success messages
- Error handling
- Authentication feedback
- Subscription notifications

---

# 📊 Admin Dashboard

Features:

- Statistics cards
- Charts
- User overview
- Subscriber overview
- Poetry analytics

---

# 🎯 State Management

Using React Context API:

```bash
src/context/AuthContext.jsx
```

Handles:

- User authentication state
- Login/logout
- Session persistence
- Protected access

---

# ⚡ Development Setup

## 1. Clone Repository

```bash
git clone <repository-url>
```

---

## 2. Navigate to Frontend

```bash
cd frontend
```

---

## 3. Install Dependencies

```bash
npm install
```

---

## 4. Create Environment File

Create:

```bash
.env.development
```

Example:

```env
VITE_API_URL=http://localhost:5000/api
```

---

# ▶️ Running the Frontend

## Development Mode

```bash
npm run dev
```

Runs on:

```bash
http://localhost:5173
```

---

## Production Build

```bash
npm run build
```

---

## Preview Production Build

```bash
npm run preview
```

---

# 🧹 Linting

Run ESLint:

```bash
npm run lint
```

---

# 🌍 Deployment

Recommended platforms:

- Vercel
- Netlify
- Render

---

# 📈 Future Improvements

Potential future upgrades:

- Dark mode
- Rich text editor
- Markdown support
- Poem categories/tags
- Search functionality
- Likes & comments
- Pagination
- React Query integration
- Zod validation
- React Hook Form

---

# 👨‍💻 Developer

Developed by:

**Satinder Singh Sall**

---

# 📄 License

This project is licensed under the ISC License.

````

---

# Backend README.md

```md
# ⚙️ Full-Stack Satinder Poetry — Backend

Backend API for the **Full-Stack Satinder Poetry Management System**.

Built with:
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Nodemailer
- Resend Email API

This backend provides:
- Authentication APIs
- Poetry CRUD APIs
- Newsletter subscription APIs
- User management APIs
- Email services
- Protected admin APIs

---

# 📂 Project Structure

```bash
backend/
├── config/
├── controllers/
├── database/
├── middleware/
├── models/
├── routes/
├── server.js
├── package.json
└── README.md
````

---

# 🚀 Features

## 🔐 Authentication System

- User registration
- User login
- JWT authentication
- Protected routes
- Password hashing

## 📝 Poetry Management

- Create poems
- Read poems
- Update poems
- Delete poems
- Admin-only management

## 📧 Newsletter System

- Email subscriptions
- Subscriber management
- Email sending functionality

## 👤 User Management

- Manage users
- Authentication handling
- Admin authorization

## 🌐 REST API

Well-structured RESTful API architecture.

---

# ⚙️ Tech Stack

| Technology    | Purpose               |
| ------------- | --------------------- |
| Node.js       | Runtime environment   |
| Express.js    | Backend framework     |
| MongoDB       | Database              |
| Mongoose      | ODM                   |
| JWT           | Authentication        |
| bcryptjs      | Password hashing      |
| Nodemailer    | Email service         |
| Resend        | Email API             |
| dotenv        | Environment variables |
| cors          | Cross-origin requests |
| cookie-parser | Cookie handling       |

---

# 📦 Installed Dependencies

## Main Dependencies

```json
{
  "express": "^4.21.2",
  "mongoose": "^8.11.0",
  "jsonwebtoken": "^9.0.2",
  "bcryptjs": "^3.0.2",
  "cors": "^2.8.5",
  "cookie-parser": "^1.4.7",
  "dotenv": "^16.4.7",
  "nodemailer": "^6.10.0",
  "resend": "^6.9.1"
}
```

---

# 🧱 Architecture

The backend follows a modular MVC-inspired structure.

## Controllers

Handle business logic.

### Available Controllers

| Controller             | Purpose                       |
| ---------------------- | ----------------------------- |
| authController.js      | Authentication logic          |
| poemController.js      | Poetry CRUD operations        |
| subscribeController.js | Newsletter subscription logic |

---

## Models

### Available Models

| Model             | Purpose           |
| ----------------- | ----------------- |
| User.js           | User schema       |
| Poem.js           | Poetry schema     |
| SubscribeEmail.js | Subscriber schema |

---

## Middleware

### `authMiddleware.js`

Handles:

- JWT verification
- Protected routes
- Authentication checks

---

# 🛣️ API Routes

## Authentication Routes

Base Route:

```bash
/api/auth
```

Possible endpoints:

| Method | Endpoint    | Description   |
| ------ | ----------- | ------------- |
| POST   | `/register` | Register user |
| POST   | `/login`    | Login user    |
| GET    | `/profile`  | Get profile   |

---

## Poetry Routes

Base Route:

```bash
/api/poems
```

Possible endpoints:

| Method | Endpoint | Description     |
| ------ | -------- | --------------- |
| GET    | `/`      | Get all poems   |
| GET    | `/:id`   | Get single poem |
| POST   | `/`      | Create poem     |
| PUT    | `/:id`   | Update poem     |
| DELETE | `/:id`   | Delete poem     |

---

## Subscription Routes

Base Route:

```bash
/api/subscribe
```

| Method | Endpoint | Description     |
| ------ | -------- | --------------- |
| POST   | `/`      | Subscribe email |
| GET    | `/`      | Get subscribers |

---

## User Routes

Base Route:

```bash
/api/users
```

---

# 🔌 Database Connection

Database connection handled in:

```bash
database/config/db.js
```

Using MongoDB with Mongoose.

---

# 🔥 Environment Configuration

The backend supports:

- Development environment
- Production environment

Dynamic environment loading:

```js
const envFile =
  process.env.NODE_ENV === "production"
    ? ".env.production"
    : ".env.development";
```

---

# 📄 Environment Variables

## `.env.development`

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
RESEND_API_KEY=your_resend_api_key
EMAIL_USER=your_email
EMAIL_PASS=your_password
```

---

# ▶️ Running the Backend

## Install Dependencies

```bash
npm install
```

---

## Development Mode

```bash
npm run dev
```

Runs with:

- Nodemon
- Development environment

---

## Production Mode

```bash
npm start
```

---

# 🌐 Server Information

Default Port:

```bash
5000
```

Health Check:

```bash
GET /
```

Response:

```txt
🚀 API is running & LIVE...
```

---

# 🔒 Authentication Flow

Authentication includes:

- JWT token generation
- Password hashing using bcryptjs
- Protected routes middleware
- Cookie parsing support

---

# 📧 Email System

Supports:

- Newsletter emails
- Contact emails
- Subscription notifications

Using:

- Nodemailer
- Resend API

---

# 🛡️ Security Features

Implemented:

- Password hashing
- JWT authentication
- Protected routes
- Environment variables

Recommended future additions:

- Helmet
- Rate limiting
- Input validation
- CSRF protection

---

# ⚡ Error Handling

Global error handler implemented:

```js
app.use((err, req, res, next) => {
  console.error(err.stack);
  res.status(500).json({ message: "Something went wrong!" });
});
```

---

# 📈 Future Improvements

Potential future upgrades:

- Role-based authorization
- Zod/Joi validation
- Unit testing
- Integration testing
- Swagger API docs
- Refresh token auth
- Email templates
- File uploads
- Rich text editor support

---

# 🧪 Testing

Current status:

```bash
No tests yet
```

Recommended:

- Jest
- Supertest

---

# 🌍 Deployment

Recommended backend deployment platforms:

- Render
- Railway
- Fly.io
- VPS hosting

---

# 👨‍💻 Developer

Developed by:

**Satinder Singh Sall**

---

# 📄 License

Licensed under the ISC License.
