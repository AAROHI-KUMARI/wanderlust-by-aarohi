# 🌍 Wanderlust

A full-stack travel listing web application inspired by platforms like Airbnb, built while learning and implementing modern web development concepts.

> 🚧 **Project Status: In Progress**
>
> Wanderlust is currently under development. New features, improvements, and UI enhancements will be added as I continue building the project.

---

## 📌 About the Project

Wanderlust is a travel listing platform where users can explore different stays and destinations through visually appealing listing cards.

The project is being built as a hands-on full-stack web development project to understand how the frontend, backend, database, routing, templates, and CRUD operations work together.

---

## ✨ Current Features

- 🏠 View all available listings
- 🔍 View individual listing details
- ➕ Create a new listing
- ✏️ Edit existing listings
- 🗑️ Delete listings
- 💰 Display listing prices in Indian currency format
- 🌍 Display location and country information
- 🖼️ Display listing images
- 📱 Responsive Bootstrap-based UI
- 🧩 Reusable layouts using EJS
- 🧭 Navigation bar and footer
- 🗄️ MongoDB database integration
- 🔄 RESTful routing
- 📝 Method Override for PUT/DELETE requests

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- Bootstrap
- EJS

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Other Tools
- Git
- GitHub
- VS Code
- EJS-Mate
- Method-Override

---

## 📂 Project Structure

```text
wanderlust/
│
├── models/
│   └── listing.js
│
├── public/
│   └── css/
│       └── style.css
│
├── views/
│   ├── includes/
│   │   ├── footer.ejs
│   │   └── navbar.ejs
│   │
│   ├── layouts/
│   │   └── boilerplate.ejs
│   │
│   └── listings/
│       ├── edit.ejs
│       ├── index.ejs
│       ├── new.ejs
│       └── show.ejs
│
├── app.js
├── package.json
├── package-lock.json
└── README.md
