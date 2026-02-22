# 🎓 VidyaAI — Personalized AI Learning Platform

VidyaAI is an AI-powered personalized learning platform for Indian students (Class 10, 11, 12 & Engineering). It provides step-by-step concept coaching, multilingual support in 10 Indian languages, and an adaptive 3-panel learning experience — all in one beautifully designed web app.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🤖 **AI Concept Coach** | Step-by-step hints and explanations powered by LLaMA 3 via Groq API |
| 🌐 **Multilingual Support** | Learn in English, Hindi, Tamil, Telugu, Bengali, Kannada, Marathi, Gujarati, Malayalam, and Punjabi |
| 📚 **NCERT-Aligned Curriculum** | Curated content for Class 10, Class 11/12 (PCM & PCB streams), and Engineering CS |
| 🔐 **Firebase Auth** | Secure email/password authentication with user profiles stored in Firestore |
| 🎯 **Personalized Onboarding** | Users select their class and stream; curriculum adapts accordingly |

---

## 🛠️ Tech Stack

- **Frontend**: React 18, Vite, Tailwind CSS, Framer Motion
- **Routing**: React Router v6
- **Backend / Auth**: Firebase Authentication + Firestore
- **AI**: LLaMA 3 via [Groq API](https://console.groq.com) (free tier)
- **Icons**: Lucide React

---


---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher
- A [Firebase](https://console.firebase.google.com) project with **Authentication** and **Firestore** enabled
- A free [Groq API key](https://console.groq.com)

### 1. Clone the repository

```bash
git https://github.com/TheprogrammerRohith/Personalized-AI-Learning-Platform.git
cd Personalized-AI-Learning-Platform/frontend
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Copy the example file and fill in your credentials:

```bash
cp .env.example .env
```

### 4. Run the development server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### 5. Build for production

```bash
npm run build
```

---

## 🗺️ Application Routes

| Route | Access | Description |
|---|---|---|
| `/` | Public | Landing page |
| `/auth` | Public | Login / Sign-up |
| `/onboarding` | Protected | Class & stream selection (first login) |
| `/subjects` | Protected | Browse available subjects |
| `/chapters/:subjectId` | Protected | View chapters for a subject |
| `/learn/:subjectId/:chapterId` | Protected | 3-panel learning experience |
| `/profile` | Protected | User profile & progress |

---

## 🌍 Supported Languages

English · हिंदी · தமிழ் · తెలుగు · বাংলা · ಕನ್ನಡ · मराठी · ગુજરાતી · മലയാളം · ਪੰਜਾਬੀ

---

## 📦 Curriculum Coverage

| Level | Subjects |
|---|---|
| **Class 10** | Maths, Science, Social Studies, English, Hindi |
| **Class 11 & 12 PCM** | Physics, Chemistry, Mathematics |
| **Class 11 & 12 PCB** | Physics, Chemistry, Biology |
| **Engineering / B.Tech** | DSA, Operating Systems, DBMS, Computer Networks, OOP |

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

