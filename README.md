<p align="center">
  <img src="https://github.com/krishna17092004/SkillUp/blob/main/assets/SkillUp%20Logo.png" alt="SkillUp Logo" height="200" style="vertical-align:middle; margin-right: 10px;"/><br>
  <span style="font-size:180px; vertical-align:middle;"><strong>SkillUp – Learn2Earn: AI Mentor 🚀</strong></span>
</p>


## 📌 Project Overview

SkillUp is an AI-powered personalized learning mentor designed for students who are uncertain about their career path. It analyzes a user’s current skillset and career goals, then generates a custom, step-by-step roadmap integrated with curated learning resources and progress tracking.

## 🧠 Meet Riya — Our Inspiration

> Riya is a 2nd-year CS student. She wants to become a Data Analyst but doesn’t know what to learn, where to start, or how to track progress. She’s looking for a career GPS — and SkillUp is the answer. ✨

## 🎯 Objectives

  🔍 Assess students’ current skills via resume, quiz, or GitHub profile<br>
  🎯 Help them choose a target career role<br>
  🧭 Generate a weekly, personalized learning roadmap<br>
  🎥 Integrate resources from YouTube, Coursera, edX, etc.<br>
  📊 Track progress and suggest actions based on achievements<br>
  🧑‍🤝‍🧑 (Optional) Offer peer comparison, mentor suggestions & certifications<br>

## 🛠️ Tech Stack

Frontend       | Backend         | AI & NLP           | APIs & Tools
-------------- | --------------- | ------------------ | ----------------------------
React + Tailwind CSS | FastAPI / Flask | spaCy, HuggingFace, Scikit-learn | OpenAI / Gemini API, YouTube Data API, Firebase
MongoDB / Firebase | JWT Auth | PyMuPDF (resume parsing), GitHub API | Chart.js, Recharts, RapidAPI

## 📐 System Architecture

![Architecture Diagram](https://github.com/krishna17092004/SkillUp/blob/main/assets/WhatsApp%20Image%202025-04-11%20at%2018.48.58_b393b56b.jpg)
<details>
<summary>🧩 Click to view Architecture Diagram</summary>

📦 Modules:

1. Skill Assessment Engine
2. Career Goal Selector
3. Roadmap Generator
4. Resource Integration Engine
5. Progress Tracker
6. (Optional) Peer Comparison & Mentor Match

</details>

## 🧩 Features Breakdown

### 📘 Skill Assessment

- Resume PDF parsing using NLP (PyMuPDF + spaCy)
- GitHub + Kaggle scraping to detect tech stack
- Self-assessment form for students with little portfolio
- Auto-generate a skill vector across areas like Python, SQL, Statistics, etc.

### 🎓 Career Goal Selector

- Dropdown of predefined roles (Data Analyst, ML Engineer, Web Dev)
- OR quiz-based recommender for freshers
- Maps to NSDC / ONET standardized career paths

### 🧭 Roadmap Generator (AI Mentor)

- Compares current skills vs. role’s required skills
- Generates learning path with:
  - Week-wise plan
  - Resource links
  - Expected outcomes

### 🔗 Resource Integration

- YouTube tutorials via Data API
- Coursera/edX courses via search APIs
- Free PDFs, GitHub Repos, Kaggle Notebooks
- Community-curated resource DB (CSV/NoSQL)

### 📈 Progress Tracker

- Weekly check-in dashboard
- Visualize roadmap timeline (Gantt or horizontal timeline)
- Smart nudges for delayed progress
- Gamified streaks & rewards (optional)

### 🎁 Bonuses

- Peer Progress Comparison 📊
- Mentor Matching via LinkedIn or Alumni DB 🤝
- Certification Suggestions (e.g., Google Data Analyst Cert) 🎓

## 📷 Sample Output: For Riya

💬 “Hi Riya! Based on your current skillset and your interest in Data Analytics, here’s your personalized 10-week learning roadmap 📚👇”

Week | Topic | Resources | Goal
---- | ----- | --------- | ----
1–2 | SQL Basics | YouTube: Alex the Analyst | Master SELECT & JOINs
3 | Excel for Analytics | Coursera | Pivot Tables + Charts
4–5 | Python & Pandas | edX, YouTube | Data Wrangling
6 | EDA Practice | Kaggle – Titanic Dataset | Hands-on Project
… | … | … | …

## 🧪 Getting Started (for Devs)

Clone the repo:
```bash
git clone https://github.com/yourusername/SkillUp.git
cd SkillUp
```
Frontend:
```bash
cd frontend
npm install
npm start
```
Backend:
```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```
Set API keys in ```.env``` file (YouTube, OpenAI/Gemini, Firebase)

## 🧠 Powered By

- OpenAI GPT-4 & Gemini Pro
- Google Firebase
- GitHub & Kaggle APIs
- ONET Career DB & NSDC

## 👨‍💻 Team SkillUp

- Krishna Teja K — AI & Architecture 🧠
- Vasundhara G — Frontend & User Experience 🎨
- Bhoomika D Janardhan — Backend & APIs ⚙️
- Prerana V U — NLP & Resource Curation 🧾

## 🪄 Want to Contribute?

Fork it 🍴 → Star it ⭐ → Clone it 📥 → Build it 💡  
Read CONTRIBUTING.md for details.

## 📄 License
MIT License © 2025 Team SkillUp<br>
Feel free to use, share, and remix with credits 🙌
