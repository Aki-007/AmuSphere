# AmuSphere 🚀

A **3D virtual classroom** platform built using **Three.js** and **Socket.IO**, enabling immersive real-time interaction with avatar support, classroom rooms, and voice communication.

Live demo not available yet — this is a work-in-progress project.

---

## 🧠 Project Overview

AmuSphere aims to reimagine online learning by simulating a **real classroom experience** in a 3D environment, where:

- Users join classrooms via **rooms** (like Google Meet).
- Students and teachers appear as **3D avatars**.
- Interactions and movement are **real-time** with positional updates.
- Voice is handled via **mediasoup (SFU)** for scalable group communication.
- Designed to run smoothly even on **low-end devices** using view modes & optimizations.

---

## 🔑 Key Features

### 🎓 Classroom Experience
- Create & join virtual rooms.
- Persistent 3D classroom environment.
- Movement and interaction sync via Socket.IO.

### 🧍‍♂️ Avatars
- 3D character avatars for users.
- Server-side sprite generation planned for optimized views.

### 🎤 Voice Communication
- mediasoup integration for scalable voice channels.
- SFU architecture for stable group voice chat.

### 📐 Multiple View Modes
- Full 3D Perspective.
- Orthographic (2D-like) view.
- 2.5D Isometric view.

Optimized to run smoothly on devices without dedicated GPUs.

---

## 📁 Repo Structure
````
AmuSphere/
├── backend/               # Server code
├── frontend/              # Client (React + Three.js)
└── README.md

````

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React, Three.js |
| Realtime | Socket.IO |
| Voice | mediasoup (SFU) |
| Server | Node.js |
| 3D Models & Sprites | Three.js |
| Authentication | Local + Google |

---

## 🛠 Getting Started

### Prerequisites

Make sure you have:

- Node.js (v16+)
- npm or yarn

---

### Install Backend

```bash
cd backend
npm install
````

### Install Frontend

```bash
cd ../frontend
npm install
```

---

### Run (Development)

Start backend:

```bash
cd backend
npm start
```

Start frontend:

```bash
cd frontend
npm start
```

