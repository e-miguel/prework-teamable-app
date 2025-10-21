### 🧩 Teamable App

My demo full-stack web application built as part of the IT Beginners Course by TechWorld with Nana.
The goal of this project is to understand the complete Software Development Lifecycle (SDLC) — from planning to deployment — while taking up multiple IT roles (Product Owner, Developer, Tester, and System Administrator).

### 📘 Table of Contents

1. Project Overview
2. Learning Objectives
3. Tech Stack
4. System Architecture
5. Features
6. Project Phases
7. Setup Instructions
8. Code Structure
9. Testing
10. Deployment
11. Key Learnings
12. Author

### 🚀 Project Overview

Teamable App is a simple full-stack web application designed to simulate a real-world software project.
It demonstrates how frontend, backend, and database components interact in a cloud-based environment.

This project was built step-by-step throughout the IT Beginners Course:

- Planned with Jira (Agile/Scrum)
- Developed using HTML, CSS, JavaScript, VueJS, and NodeJS
- Tested with Jest
- Deployed on a Linux Cloud Server

### 🎯 Learning Objectives

- Understand how the software development lifecycle (SDLC) works.
- Learn how to plan, code, test, and deploy an app.
- Gain hands-on experience with frontend, backend, and cloud deployment.
- Practice version control using Git and GitHub.

### 🧠 Tech Stack

| Category           | Technologies                 |
| ------------------ | ---------------------------- |
| Frontend           | HTML, CSS, JavaScript, VueJS |
| Backend            | NodeJS, Express              |
| Database           | MongoDB                      |
| Testing            | Jest                         |
| Cloud / Server     | Linux Ubuntu (Cloud VM)      |
| Version Control    | Git & GitHub                 |
| Project Management | Jira (Agile / Scrum)         |

### 🏗️ System Architecture

Frontend (VueJS)
      ↓ (HTTP / API Calls)
Backend (NodeJS + Express)
      ↓
Database (MongoDB)
      ↓
Cloud Server (Ubuntu VM)

### 🔄 Project Phases

| Phase           | Description                                                     | Role                 |
| --------------- | --------------------------------------------------------------- | -------------------- |
| **1. Plan**     | Created Jira board, defined tasks and sprints.                  | Product Owner        |
| **2. Develop**  | Built frontend (VueJS) and backend (NodeJS), connected MongoDB. | Developer            |
| **3. Test**     | Implemented Jest tests for features.                            | Tester               |
| **4. Deploy**   | Packaged and deployed app on Linux Cloud Server.                | System Administrator |
| **5. Maintain** | Managed version control and future updates using Git.           | DevOps / Maintainer  |

### 🧩 Setup Instructions
#### 1️⃣ Clone the Repository
git clone https://github.com/<yourusername>/teamable-app.git
cd teamable-app

#### 2️⃣ Install Dependencies
npm install

#### 3️⃣ Run the Application
npm start

#### 4️⃣ Open in Browser
http://localhost:3000

#### 📂 Code Structure
teamable-app/
│
├── frontend/                # VueJS components
│   ├── index.html
│   ├── src/
│   └── assets/
│
├── backend/                 # NodeJS + Express API
│   ├── server.js
│   ├── routes/
│   └── models/
│
├── tests/                   # Jest test files
│
├── package.json
├── README.md
└── .gitignore

### 🧪 Testing

Unit and integration tests are written in **Jest.**

Run all tests:

npm test

Example test:

test("calculates correct age", () => {

  expect(getAge("2000-01-01")).toBe(25)

})


