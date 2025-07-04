# 📚 StudySphere – AI-Powered Personalized Learning Assistant

## 🚀 Project Overview

**StudySphere** is an all-in-one AI-powered study companion built to help learners break down topics, generate flashcards, plan weekly goals, and engage via voice. Designed using **Next.js** and **Groq LLaMA via v0.dev**, StudySphere transforms raw study content into personalized, interactive formats — all hosted serverlessly on **Vercel**.

Students can upload text or topics and instantly receive:

- 📄 Smart concept breakdowns  
- 🧠 Flashcards, MCQs & deep questions  
- 🗓️ Personalized weekly study plans  
- 🎙️ Voice-based interaction *(via StudySuno)*

---

## 🎯 Purpose

StudySphere empowers learners who struggle with static PDFs, linear revision, or time management by offering dynamic, interactive, and voice-enabled tools.

### With StudySphere, learners can:
- Break down complex topics using **StudyScan**
- Create flashcards & practice MCQs using **StudyBits**
- Plan and track progress with **StudyPlan**
- Interact with AI voice using **StudySuno** *(Speech + TTS)*

---

## 🔍 Core Modules

| Module       | Description                                                                 | Tech Stack Used                                   |
|--------------|-----------------------------------------------------------------------------|--------------------------------------------------|
| **StudyScan** | Breaks down any topic into weekly learning phases, concepts & resources    | Groq LLaMA (via v0), Structured JSON              |
| **StudyBits** | Converts text into flashcards, MCQs, and long-answer questions              | Groq LLaMA (via v0), Groq API                     |
| **StudyPlan** | Builds AI-generated weekly study schedules based on time & difficulty       | Groq Mixtral + LLaMA via v0.dev                   |
| **StudySuno** | Voice interaction: speech to text + voice responses (multilingual)          | AssemblyAI (STT), Azure Speech (TTS), Clerk Auth  |

---

## 🌟 Key Features

- ✅ Topic-to-syllabus breakdown via AI  
- ✅ Auto-generated flashcards & MCQs  
- ✅ Personalized study planning  
- ✅ Voice query → spoken answer support  
- ✅ Supports multiple learning styles (text + audio)  
- ✅ Structured JSON for consistent rendering  
- ✅ Deployed & scaled using **Vercel v0.dev**

---

## 🧠 Tech Stack

### 🎨 Frontend
- **Next.js** – React-based SSR framework  
- **Tailwind CSS** – Utility-first styling  
- **Clerk.dev** – User authentication & session handling  
- **Vercel v0.dev** – AI-backed generation & full hosting  

### 🧠 AI & NLP
- **Groq LLaMA / Mixtral (via v0)** – For reasoning, breakdowns, questions  
- **v0.dev** – AI UI + action routing  
- **Microsoft Azure TTS** – English voice response *(StudySuno)*  
- **AssemblyAI** – Speech-to-text input understanding *(StudySuno)*  

### 🔧 Backend / Utilities
- **Vercel Serverless Functions** – API routes  
- **Structured JSON** – For frontend data modeling  
- **No DB (for now)** – Fully stateless (optional: Firebase/Planetscale in future)

---

## 🌍 Use Cases

### ✅ Current
- 📘 **Understand any topic** – Break it down by phases and concepts  
- 🧠 **Revise smarter** – Practice flashcards, MCQs, and recall questions  
- 📆 **Plan better** – Get AI-generated weekly study goals  
- 🎤 **Learn by voice** – Ask anything, get spoken answers instantly  

### 🧩 Upcoming
- 🔗 **Study Rooms** – Collaborate with friends in real time  
- 📱 **Mobile-first experience** – Optimized PWA or app sync  
- 👨‍🏫 **Teacher view** – Batch topic upload + student progress  
- 🧠 **Personalized AI feedback** – Strengths, weak areas, AI tutor suggestions  
- 🌍 **Full multilingual support** – English + Indian/regional languages


> 🌐 Live: **[StudySphere on Vercel](https://v0-fork-of-study-sphere-v0-requirem-dusky.vercel.app/)**  
---

## ⚙️ Local Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/studysphere.git
cd studysphere

# Install dependencies
npm install

# Add your API keys to `.env.local`
cp .env.example .env.local



