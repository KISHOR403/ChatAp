# 💬 ChatApp

A real-time full-stack chat application built with Node.js, React, and Socket.io. Users can sign up, log in, and exchange messages instantly in real time.

![GitHub stars](https://img.shields.io/github/stars/KISHOR403/ChatAp?style=social)
![GitHub forks](https://img.shields.io/github/forks/KISHOR403/ChatAp?style=social)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

---


## ✨ Features

- 🔐 User authentication (Sign up / Login)
- 💬 Real-time messaging with Socket.io
- 👥 Online user status indicator
- 📱 Responsive UI for mobile and desktop
- 🐳 Docker support for easy setup
- ☁️ Deployable on Render

---

## 🛠️ Tech Stack

| Layer        | Technology              |
|--------------|-------------------------|
| Frontend     | React, CSS, HTML        |
| Backend      | Node.js, Express        |
| Real-time    | Socket.io               |
| Database     | MongoDB                 |
| Auth         | JWT (JSON Web Tokens)   |
| Container    | Docker / Docker Compose |
| Deployment   | Render                  |

---

## 📁 Project Structure
```
ChatAp/
├── backend/          # Express + Socket.io server
├── frontend/         # React client app
├── docker-compose.yml
├── render.yaml       # Render deployment config
├── .gitignore
└── README.md
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18+
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Docker](https://www.docker.com/) *(optional)*

---

### 🐳 Run with Docker (Recommended)
```bash
git clone https://github.com/KISHOR403/ChatAp.git
cd ChatAp
docker-compose up --build
```

App will be running at: `http://localhost:3000`

---

### 🖥️ Run Manually

#### 1. Clone the repository
```bash
git clone https://github.com/KISHOR403/ChatAp.git
cd ChatAp
```

#### 2. Setup Backend
```bash
cd backend
npm install
```

Create a `.env` file inside `/backend`:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

Start the backend:
```bash
npm start
```

#### 3. Setup Frontend
```bash
cd ../frontend
npm install
npm start
```

Frontend runs at: `http://localhost:3000`  
Backend runs at: `http://localhost:5000`

---

## 🌐 Deployment on Render

This project includes a `render.yaml` file for one-click deployment on [Render](https://render.com).

1. Push your code to GitHub
2. Go to [Render Dashboard](https://dashboard.render.com)
3. Click **New** → **Blueprint**
4. Connect your GitHub repo (`KISHOR403/ChatAp`)
5. Render will auto-detect `render.yaml` and deploy both services

---

## 📸 Screenshots

> *(Add screenshots of your app here)*
```
![Login Page](screenshots/login.png)
![Chat Page](screenshots/chat.png)
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the project
2. Create your feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Kishor**  
GitHub: [@KISHOR403](https://github.com/KISHOR403)
