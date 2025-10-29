# 🎬 Filmbuddy — AI-Powered Movie Recommendation Platform

Filmbuddy is a full-stack web application that delivers **AI-powered movie recommendations** with a focus on **user control and social interaction**.  
Developed as part of my Bachelor’s Degree project at **University Politehnica of Bucharest**, it aims to solve the “filter bubble” problem found in traditional streaming platforms.

---

## 🚀 Features
- **Hybrid Recommendation Engine** — Combines content-based filtering (movie genres) and collaborative filtering (user behavior) with a tunable `α` parameter for personalization.
- **AI Virtual Assistant** — Integrated **LLaMA model** that interacts with users in natural language, delivering personalized suggestions and analyzing sentiment.
- **Social Layer** — Users can add friends, chat, and share their favorite movies directly within the app.
- **Secure Authentication** — Passwords encrypted with Bcrypt, and sensitive data stored safely in PostgreSQL.
- **Dynamic Frontend** — Built with **React + TypeScript + Bootstrap** for a clean and responsive user experience.
- **FastAPI Backend** — RESTful API that connects the frontend, recommendation engine, and database.

---

## 🧠 Tech Stack
**Backend:** Python, FastAPI, Pandas, Surprise SVD, Bcrypt  
**Frontend:** React, TypeScript, Vite, Bootstrap  
**Database:** PostgreSQL  
**AI:** LLaMA (via Ollama) for conversational and sentiment capabilities  
**Tools:** Anaconda, GitHub, Uvicorn

---

## ⚙️ System Architecture




Flimbuddy architecture:
<img width="893" height="366" alt="Filmbuddy" src="https://github.com/user-attachments/assets/21deec48-4fa8-4b86-9933-8d6b6fed0c93" />








Data base arhitecture



<img width="893" height="421" alt="DB_Architecture" src="https://github.com/user-attachments/assets/3b168879-e828-4ff5-9cf8-645e56e76b55" />


How to run:

Anaconda env

FilmbuddyUI
npm run dev 


Filmbuddy2
uvicorn filmbuddy:app --host 0.0.0.0 --port 5000 --reload


Load data into DB with load_ml100k
Need to do that only once
