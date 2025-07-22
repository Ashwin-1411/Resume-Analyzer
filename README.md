# 🧠 Resumind - AI-Powered Resume Analyzer

Resumind is a full-stack AI web application that analyzes your resume and gives smart feedback based on tone, structure, ATS compatibility, and job relevance. Upload your resume, get scored, and improve instantly using AI suggestions.

---

## ✨ Features

- 📄 Upload resume (PDF)
- 🔍 Get detailed **ATS (Applicant Tracking System) score**
- 🧠 Receive AI-powered feedback (via Claude Sonnet 4)
- 🎯 Analyze resume relevance for a given job description
- 📷 Resume preview using PDF-to-image conversion
- 🔒 Auth via Puter.js
- 🧰 Built with **React**, **Vite**, **Tailwind CSS**, **Zustand**, and **React Router**

---

## 🖼️ Screenshots

| Resume Upload | Resume Feedback |
|---------------|-----------------|
| ![Upload](https://your-upload-screenshot-url) | ![Feedback](https://your-feedback-screenshot-url) |

---

## ⚙️ Tech Stack

**Frontend:**
- React 19
- React Router 7
- Tailwind CSS 4
- TypeScript
- Zustand (state management)

**Backend/Infra:**
- Server-Side Rendering (SSR via React Router)
- PDF.js (pdf-to-image conversion)
- Docker (multi-stage production setup)
- Puter.js (Auth, FS, KV, AI)

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/Ashwin-1411/Resume-Analyzer.git
cd Resume-Analyzer
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run the development server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📂 Project Structure

```
Resume-Analyzer/
├── app/                 # Frontend source code
│   ├── components/      # UI Components (ScoreGauge, ATS, Summary...)
│   ├── routes/          # Pages (auth, home, upload, resume review)
│   ├── lib/             # Utility functions, pdf/image conversion
├── public/              # Public assets (PDF.js worker)
├── constants/           # Static constants
├── types/               # TypeScript types
├── package.json
├── tsconfig.json
├── Dockerfile
├── vercel.json
└── README.md
```

---

## ✍️ Author

Made with ❤️ by **Ashwin K**  
GitHub: [@Ashwin-1411](https://github.com/Ashwin-1411)

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 🙌 Acknowledgments

- [React Router](https://reactrouter.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Puter.js](https://puter.com/)
- [Claude Sonnet AI](https://www.anthropic.com/index/claude)
