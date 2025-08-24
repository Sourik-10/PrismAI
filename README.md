# PrismAI

[![GitHub Stars](https://img.shields.io/github/stars/Sourik-10/PrismAI?style=flat&color=yellow)](https://github.com/Sourik-10/PrismAI/stargazers)
[![GitHub License](https://img.shields.io/github/license/Sourik-10/PrismAI?style=flat&color=blue)](./LICENSE)
[![Deployment](https://img.shields.io/badge/deployed%20on-Vercel-black?logo=vercel)](https://quick-ai-eight-xi.vercel.app/)

PrismAI is a full-stack AI-powered web application built with a modular **client–server architecture**.  
The project is primarily written in JavaScript, with separate frontend and backend folders for better scalability and maintainability.  
It is designed to serve as a foundation for experimenting with and deploying AI-driven applications.

---

## 🚀 Features

- **Full-stack architecture** with dedicated `client` and `server` modules  
- **AI-powered interactions** for intelligent responses  
- **Scalable structure** for future enhancements  
- **Modern web technologies** for smooth development and deployment  
- **Vercel deployment** support for quick hosting  

---

## 🛠️ Tech Stack

- **Frontend:** JavaScript, React (if included), TailwindCSS (if included)  
- **Backend:** Node.js, Express.js  
- **AI Integration:** OpenAI API / Custom AI Models (depending on your setup)  
- **Deployment:** Vercel  

---

## 📂 Project Structure

```
PrismAI/
│
├── client/        # Frontend code
│   ├── src/       # React components, pages, styles
│   └── ...
│
├── server/        # Backend code
│   ├── routes/    # API routes
│   ├── models/    # Database models (if any)
│   └── ...
│
└── README.md      # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sourik-10/PrismAI.git
   cd PrismAI
   ```

2. **Install dependencies**
   - For server:
     ```bash
     cd server
     npm install
     ```
   - For client:
     ```bash
     cd client
     npm install
     ```

3. **Set environment variables**  
   Create a `.env` file in the `server/` directory and add your API keys (e.g., OpenAI, DB connection).

   Example:
   ```env
   PORT=5000
   OPENAI_API_KEY=your_api_key_here
   ```

4. **Run the application**
   - Start backend:
     ```bash
     cd server
     npm run dev
     ```
   - Start frontend:
     ```bash
     cd client
     npm start
     ```

---

## 🌐 Live Demo

👉 [Hosted on Vercel](https://quick-ai-eight-xi.vercel.app/)

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to **fork** this repo and submit a **pull request** with improvements.

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
