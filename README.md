---

# GDG Solutions

A full-stack TypeScript application built with modern web tooling. This project is structured into `client`, `server`, and `shared` modules, using Vite for development, TailwindCSS for styling, and Drizzle ORM for database access.

---

## 🚀 Tech Stack

### **Frontend**

* Vite
* React / TypeScript
* Tailwind CSS
* PostCSS

### **Backend**

* Node.js
* TypeScript
* Drizzle ORM

### **Other**

* Replit environment support
* Shared TypeScript types
* Environment-based configuration

---

## 📁 Project Structure

```
gdg-solutions/
│
├── client/          # Frontend source code (Vite + Tailwind)
├── server/          # Backend logic & API
├── shared/          # Shared types / utilities between client & server
│
├── drizzle.config.ts
├── tailwind.config.ts
├── vite.config.ts
├── tsconfig.json
├── package.json
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/gdg-solutions.git
cd gdg-solutions
```

### 2. Install dependencies

```bash
npm install
```

---

## 🧩 Environment Setup

Create a `.env` file in the project root (if required by the backend).

Typical example:

```
DATABASE_URL=postgres://user:password@localhost:5432/dbname
PORT=5000
```

---

## 🛠️ Development

### Start client (Vite)

```bash
npm run dev
```

### Run backend

```bash
npm run server
```

> Check the scripts in `package.json` for exact command names — adjust as needed.

---

## 🗄️ Database (Drizzle)

### Generate migration files

```bash
npm run db:generate
```

### Push schema to database

```bash
npm run db:push
```

### View Drizzle Studio

```bash
npm run db:studio
```

---

## 🧪 Scripts

Common useful commands:

| Command               | Description                       |
| --------------------- | --------------------------------- |
| `npm run dev`         | Start frontend development server |
| `npm run server`      | Start backend server              |
| `npm run build`       | Build production bundle           |
| `npm run db:generate` | Create migration based on schema  |
| `npm run db:push`     | Apply migration to DB             |
| `npm run db:studio`   | Visual database explorer          |

---

## 📦 Production Build

```bash
npm run build
```

Output files go into the configured Vite build directory (usually `/dist`).

---

