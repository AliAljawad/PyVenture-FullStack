# 🚀 PyVenture FullStack Project

> **A storyline-driven learning experience:**  
> Explore levels, solve coding challenges, and progress through a galaxy of knowledge — all powered by real-time feedback and adaptive learning.

---

## 🗂️ Project Structure

```
pyventure-backend/   # Laravel backend (API, business logic, database)
pyventure-frontend/  # React frontend (Vite, Tailwind CSS, TypeScript)
```

---

## ⚙️ Tech Stack

- **Frontend:** React.js, Vite, Tailwind CSS, TypeScript, Phaser.js(for gamified interactions)
- **Backend:** Laravel (PHP)
- **Database:** MySQL
- **AI Feedback:** Qwen-Coder:7B via Ollama

---

## 🚦 Getting Started

### 🛠️ Prerequisites

- PHP >= 8.1
- Composer
- Node.js & npm
- MySQL
- [Ollama](https://ollama.com/) (for local AI)

---

### 🔧 Backend Setup

1. **Install dependencies:**
   ```sh
   cd pyventure-backend
   composer install
   ```
2. **Configure environment:**
   ```sh
   cp .env.example .env
   # Edit .env for your DB and environment
   ```
3. **Generate app key:**
   ```sh
   php artisan key:generate
   ```
4. **Run migrations:**
   ```sh
   php artisan migrate
   ```
5. **Start server:**
   ```sh
   php artisan serve
   ```

---

### 🎨 Frontend Setup

1. **Install dependencies:**
   ```sh
   cd pyventure-frontend
   npm install
   ```
2. **Start dev server:**
   ```sh
   npm run dev
   ```

---

### 🤖 AI Model (Qwen-Coder:7B via Ollama)

1. **Install Ollama:** [Download here](https://ollama.com/download)
2. **Pull the model:**
   ```sh
   ollama pull qwen2.5-coder:7b
   ```
3. **Start Ollama:**
   ```sh
   ollama serve
   ```

---

## 🧑‍🚀 Features

- Storyline-driven progression through coding challenges
- Real-time, AI-powered feedback and hints
- Gamified levels built using Phaser.js
- Achievements & leaderboards
- Fully responsive design
- Achievements & leaderboards

---

## 🤝 Contributing

Contributions are welcome! Please open issues or submit pull requests.

---

## 🙏 Acknowledgements

- [Laravel](https://laravel.com/)
- [React](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Phaser.js](https://phaser.io/)
- [Ollama](https://ollama.com/)
- [Qwen-Coder](https://github.com/QwenLM/Qwen) (Qwen2.5-Coder:7B)
- [MySQL](https://www.mysql.com/)
- [TypeScript](https://www.typescriptlang.org/)
