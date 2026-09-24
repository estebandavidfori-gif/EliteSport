# 🏆 EliteSport

### Full-Stack Sports Management Platform

EliteSport is a full-stack web application designed to manage sports organizations, athletes, coaches, teams, training sessions, attendance, and tournaments from a centralized platform.

The project was developed as a final academic project with a focus on **REST APIs, role-based access control, database management, and modern web development**.

---

## 🚀 Features

* 🔐 JWT-based authentication
* 👥 Role-based access control
* 🛡️ Administrator, Coach, and Athlete roles
* 🏅 Sports management
* 🧑‍🤝‍🧑 Athlete and coach management
* ⚽ Team management and athlete assignment
* 🏋️ Training session scheduling
* ✅ Attendance management
* 🏆 Tournament management
* 📊 Role-based dashboard and statistics
* 🔄 Frontend integration with a REST API

---

## 🛠️ Technologies

### Frontend

* Next.js
* React
* JavaScript
* CSS

### Backend

* Node.js
* Express.js
* REST API
* JWT Authentication

### Database

* PostgreSQL

### Tools

* Git
* GitHub
* Visual Studio Code

---

## 📂 Project Structure

```text
EliteSport/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── routes/
│   │   └── services/
│   ├── scripts/
│   └── server.js
│
├── frontend/
│   ├── app/
│   │   ├── dashboard/
│   │   ├── login/
│   │   ├── globals.css
│   │   ├── layout.js
│   │   └── page.js
│   └── lib/
│       └── api.js
│
├── database/
│   └── EliteSport_PostgreSQL.sql
│
├── COMO_EJECUTAR.md
└── .gitignore
```

---

## 🔑 User Roles

| Role                | Main Responsibilities                                    |
| ------------------- | -------------------------------------------------------- |
| 👨‍💼 Administrator | Manage sports, athletes, coaches, teams and tournaments  |
| 🧑‍🏫 Coach         | Manage training sessions and athlete activities          |
| 🏃 Athlete          | View personal information, teams and training activities |

---

## 🏗️ Architecture

EliteSport follows a **client-server architecture**:

```text
┌─────────────────────┐
│      Next.js        │
│      Frontend       │
└──────────┬──────────┘
           │
           │ REST API
           ▼
┌─────────────────────┐
│   Node.js + Express │
│       Backend       │
└──────────┬──────────┘
           │
           │ SQL
           ▼
┌─────────────────────┐
│     PostgreSQL      │
│      Database       │
└─────────────────────┘
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/estebandavidfori-gif/EliteSport.git
cd EliteSport
```

### 2. Configure the backend

Navigate to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Configure the required environment variables according to your local PostgreSQL configuration.

### 3. Configure the database

Create a PostgreSQL database and execute:

```text
database/EliteSport_PostgreSQL.sql
```

### 4. Start the backend

```bash
npm start
```

### 5. Start the frontend

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Then open the application in your browser.

> For detailed setup instructions, see [`COMO_EJECUTAR.md`](./COMO_EJECUTAR.md).

---

## 🔐 Demo Credentials

Demo accounts are available for local development and testing.

> ⚠️ Credentials should be configured locally and are intentionally not published in this repository.

---

## 📸 Screenshots

Screenshots of the application can be added here to showcase:

* Login
* Administrator dashboard
* Sports management
* Teams
* Athletes
* Training sessions
* Tournaments

---

## 🎯 Project Goals

The main goals of EliteSport were to:

* Apply full-stack development concepts.
* Build and consume a REST API.
* Implement authentication using JWT.
* Apply role-based authorization.
* Connect a modern frontend with a relational database.
* Practice Git and GitHub collaborative workflows.
* Develop a complete application from frontend to database.

---

## 👨‍💻 Contributors

* **Esteban Fori**
* **davidfori135-spec**

---

## 📌 Project Status

🚧 **Academic project — actively developed and improved.**

---

## 📄 License

This project was developed for academic and portfolio purposes.
