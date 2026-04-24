# 🚀 InterviewPrep AI (SkillGap Analyzer)

A full-stack AI-powered web application that helps users analyze resumes, identify skill gaps, and prepare for interviews with personalized AI-generated questions and ATS-optimized resumes.

---

## 📌 Features

- 🔐 JWT Authentication with Token Blacklisting  
- 📄 Resume Upload & Parsing  
- 🧠 AI-Based Skill Extraction (Gemini API)  
- 📊 Skill Gap Analysis (Resume vs Job Description)  
- 🎯 AI-Generated Interview Questions  
- 📑 ATS-Friendly Resume Generation  
- 🖨 PDF Resume Generation using Puppeteer  
- 📁 Interview Report Management  

---

## 🛠 Tech Stack

### Frontend
- React.js (Vite)
- React Router
- Context API
- Axios

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose

### Other Tools
- Gemini API (AI)
- Puppeteer (PDF generation)
- Multer (file uploads)
- Zod (validation)

---

## 📂 Project Structure

```
interview-ai-yt/
│
├── Backend/     # Node.js + Express API
├── Frontend/    # React application
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/manaspl707-pixel/SkillGap-Analyzer.git
cd SkillGap-Analyzer/interview-ai-yt
```

---

### 2️⃣ Backend Setup

```bash
cd Backend
npm install
```

Create `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
GEMINI_API_KEY=your_api_key
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash
cd Frontend
npm install
npm run dev
```

---

## 🔐 Authentication Flow

- User registers / logs in  
- JWT token is generated  
- Protected routes use middleware  
- Logout → token is blacklisted  

---

## 🤖 AI Workflow

1. Upload Resume  
2. Extract Skills using AI  
3. Compare with Job Description  
4. Detect Skill Gaps  
5. Generate:
   - Interview Questions  
   - Suggestions  
   - Improved Resume  

---

## 📄 PDF Generation

AI Response → HTML → Puppeteer → PDF

---

## 👨‍💻 About This Project

This is a personal full-stack project built to practice real-world development by integrating Generative AI with web applications.

The goal was to understand how AI can be used to enhance job preparation by automating resume analysis, identifying missing skills, and generating interview-ready content.

---
