# CampusHub 🎓

**CampusHub** is a College Event Management Platform developed as part of the **Technical Team Recruitment Process**, one of the clubs at **BMSCE (B.M.S. College of Engineering)**.

The platform aims to provide a centralized system for managing college events and connecting students with event organizers.

## 🌐 Live Demo

**Website:** https://campus-erp-w0qn.onrender.com/

## 🛠️ Tech Stack

- **Frontend:** React, Vite
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL

## ⚙️ Requirements

- Node.js 22 (recommended)
- PostgreSQL 17 (or a compatible PostgreSQL version)

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/adityaram738/campus-hub.git
cd campus-hub
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up PostgreSQL

Start PostgreSQL:

```bash
brew services start postgresql@17
```

Create the database:

```bash
createdb "Campus ERP"
```

If the database already exists, do not create it again.

### 4. Start the application

```bash
npm run dev
```

The application runs locally at:

- **Frontend:** http://localhost:5173
- **Backend API:** http://localhost:4000

By default, the backend connects to:

```text
postgresql://<your-mac-username>@localhost:5432/Campus%20ERP
```

You can override the database connection using `DATABASE_URL`:

```bash
DATABASE_URL='postgresql://localhost:5432/Campus%20ERP' npm run dev
```

## 🔑 Demo Accounts

| Role | Email | Password |
|---|---|---|
| Student | student@campuserp.dev | demo1234 |
| Organizer | organizer.org@campuserp.dev | demo1234 |

The backend automatically creates the PostgreSQL tables and demo data on first startup when the users table is empty.

**Note:** This package does not automatically migrate data from an earlier SQLite database.

## 🎯 Project Context

CampusHub was developed as part of the **Technical Team Recruitment Process for Team CodeLocked**, a club at BMSCE.

The project demonstrates practical full-stack web development skills through the development of a college event management platform.

---

**Project:** CampusHub

**Category:** Full-Stack Web Development
