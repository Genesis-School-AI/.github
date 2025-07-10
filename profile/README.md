# 🌱 Genesis-School-AI

> Making school learning smarter with AI, voice, and chatbot systems.

---

## 🎯 Vision

Genesis-School-AI aims to revolutionize classroom learning by using artificial intelligence to enhance the way students interact with lessons. Instead of relying solely on traditional materials, we capture real-time teaching, summarize it, and allow students to ask intelligent questions later — as if they were still in class.

We believe in:
- Equal learning access for all students.
- Helping students review anytime with AI.
- Blending real teaching with smart technology.

---

## 🧠 What is Genesis-School-AI?

Genesis-School-AI is a 3-part system designed for schools:

1. **Web Interface (Next.js)**  
   - A modern website interface with a chatbot for student Q&A and a quick quiz feature.

2. **AI API Server (Python with Gemini API)**  
   - Uses Retrieval-Augmented Generation (RAG) to fetch information from stored transcripts and give AI-powered responses based on real classroom data.

3. **Raspberry Pi App (Recording Tool)**  
   - Runs on a Raspberry Pi to record teachers' voices in class, transcribe them into text, and automatically store them in the database for AI use.

---

## ⚙️ Technologies Used

| Part             | Tech Stack                              |
|------------------|------------------------------------------|
| Web Interface    | Next.js, JavaScript, TailwindCSS         |
| AI API           | Python, FastAPI, Gemini Pro (RAG)        |
| Recording System | Python, SpeechRecognition, Whisper API   |
| Storage          | JSON + Vector DB (Chroma / FAISS)        |
| AI Model         | Gemini Pro / Local LLM w/ Embeddings     |
| Hosting          | GitHub, Raspberry Pi (Edge), Render/VPS  |

---

## ✨ Features

- 🎙️ **Auto Voice-to-Text Recording** from teachers' lessons
- 🧠 **AI Chatbot with RAG** based on real classroom context
- 📚 **Summarized Knowledge** for each subject automatically
- ❓ **Student Quiz Generator** for learning reinforcement
- 🌐 **Web Dashboard** for students to ask questions anytime

---

## 🎓 Who is this for?

This project is built for **schools** that want to integrate AI in a meaningful way. It empowers:
- Students to review and understand better.
- Teachers to store knowledge without extra work.
- Schools to modernize learning without replacing the human touch.

---

## 👨‍👩‍👦‍👦 Team

Developed by students from  
**Yupparaj Wittayalai School** 🏫  
With a passion for merging education and artificial intelligence to shape the future of learning.

---

> 📌 _This project is currently in private development. We aim to open source core modules soon for wider community collaboration._

