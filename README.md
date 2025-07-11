# 🍕 Kanbanaria Agile – ENGR302 Project

A Kanban-style pizza preparation game developed as part of **ENGR302: Engineering Project Management 2** at **Victoria University of Wellington** in 2024.

Players manage pizza orders by dragging them across a Kanban board through various pizza-making stages. The system simulates a simplified agile workflow in a fun, interactive way.

---

## 🧠 Project Overview

The game was design and implement as a **multiplayer game** where players work together to make and serve pizzas to customers.

The game features a **Kanban board** that helps players track the progress of each pizza through the workflow. Each team member is assigned to a kitchen station:

- **Order**
- **Prepare**
- **Cooking and Cutting**
- **Cut**
- **Review**
- **Service** *(not implemented)*

This setup reflects a real-life team environment, encouraging collaboration and responsibility. Some of these features are fully implemented; others are still in progress. For more information, see the **Design** section.

Each pizza is represented as a draggable ticket that moves between these stations. The game was built using:

- **JavaScript**
- **HTML**
- **[Phaser](https://phaser.io/)** (game framework)
- **Node.js / Express** (backend)
- **Visual Studio Code** (development)

Developed by a team of 6 students.

---

## 🎯 Motivation

Learning agile software engineering techniques is an essential part of becoming a software engineer. Teaching these practices early helps students avoid bad habits and adopt effective development workflows.

---

## ❗ Problem Statement

First-year software engineering students often work independently. When they encounter **group work** in their second year, the shift can be difficult.

This project addresses that challenge by introducing a **proof-of-concept multiplayer game** that teaches students how to:

- Work in teams
- Use **Kanban boards**
- Allocate and track tasks effectively

The game will help them develop vital **collaboration, organization, communication,** and **workflow management** skills.

---

## 🎓 Educational Goals

The game introduces students to **Kanban boards** and their benefits, including:

- **Task Visualization**  
  Clearly showing all tasks and their progress.

- **Work Organization**  
  Teaching students how to divide and assign tasks across a team.

- **Performance Insights**  
  Providing feedback in the form of a **final score**, summarizing the team's workflow efficiency and output.

---

## 🛠️ Prerequisites

Make sure you have the following installed:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js & NPM](https://nodejs.org/)
- **Live Server extension** (by Ritwick Dey) in Visual Studio Code

---

## 🚀 How to Run the Project

### 📦 1. Clone the Repository

Open your terminal or command prompt and run:

```bash
git clone https://github.com/kng-04/kanbanaria-agile.git
```

### 💻 2. Open the Project in Visual Studio Code

- Navigate to the folder you just cloned  
- **Right-click** the folder → **Show more options** → **Open with Code**

> This will open the project in Visual Studio Code.

### 🔄 3. Start the Backend Server

In Visual Studio Code:

- Go to **Terminal** → **New Terminal**

In the terminal that appears, run the following commands:

```bash
cd server
npm install
npm run dev
```

### 🌐 4. Launch the Frontend with Live Server

- Ensure the **Live Server extension** is installed in Visual Studio Code
- In the Explorer panel, navigate to: server/public/index.html
- **Right-click** `index.html` → **Open with Live Server**

> A browser tab will open with the **Kanbanaria Agile Game**.

---

### 🔍 Known Issues / Improvements

- Multiplayer functionality was **planned but not implemented**
- The **Service** station is currently **not functional**
- Station visuals and animations could be **enhanced**




