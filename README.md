# JSONLab

JSONLab is a web-based platform for developers to create, host, and manage fake APIs using JSON.  
It helps you test and prototype applications quickly without needing a real backend.  
In the future, JSONLab will also support AI-powered JSON generation for realistic mock data. 🚀

---

## ✨ Features

- 🔹 Create and host your own fake API endpoints.
- 🔹 Upload or write custom JSON data.
- 🔹 Get a public API URL for frontend/backend integration.
- 🔹 Supports multiple collections/resources (users, posts, products, etc.).
- 🔹 Future-ready with AI-generated JSON support.

---

## 🛠️ Tech Stack

- **Frontend**: Vite + React + TailwindCSS
- **Backend**: Node.js + Express
- **Database**: MongoDB

---

## 📦 Installation

### 1. Clone Repository

```bash
git clone https://github.com/reddylaxman/JSONLab.git
cd jsonlab
```

### 2. Setup Frontend (Vite + React)

```bash
npm install
npm run dev
```

👉 Frontend runs at: [http://localhost:5173](http://localhost:5173)

### 3. Setup Backend (Express + MongoDB)

```bash
cd server
npm install
node server.js
```

👉 Backend runs at: [http://localhost:3133](http://localhost:3133)

---

## 📌 Usage

1. Start frontend and backend servers.
2. Open the frontend dashboard.
3. Create a new JSON collection (e.g., `users`).
4. Add or upload JSON data.
5. Access your fake API at:

```
http://localhost:3133/api/users
```

**Example Response:**

```json
[
  { "id": 1, "name": "Anand Sai", "email": "anandsai@example.com" },
  { "id": 2, "name": "laxman", "email": "laxman@example.com" }
]
```

---

## 🧩 Roadmap

- ✅ Manual JSON creation & hosting
- ✅ Public API endpoints
- 🔜 AI-powered JSON generation
- 🔜 User authentication & private APIs

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repo
2. Create a new branch (`feature/new-feature`)
3. Commit changes and submit a PR

---

## 📄 License

MIT License – free to use and modify.

---

## 🚀 Future Vision

JSONLab aims to become the one-stop solution for fake and AI-generated APIs, making development and testing faster and smarter.
