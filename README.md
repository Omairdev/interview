## MIDIO — Interview Q&A Module  

The **Interview Q&A Module** of MIDIO is a simplified version of the virtual interview experience. Instead of using an LLM, this module relies on a curated set of **100 pre-stored interview questions** across various categories. The system presents these questions to the user one by one, simulating the flow of a real interview.  

This approach provides a lightweight, fast, and accessible way for candidates to practice answering interview questions without needing a heavy AI backend.  

---

## ✨ Features  
- Database of **100 curated interview questions**.  
- Covers categories like **HR, Technical, Aptitude, and Behavioral**.  
- Questions served in a **sequential or randomized order**.  
- Users can **type or speak their answers** (if STT is enabled).  
- Simple **mock interview simulation** without requiring an LLM.  

---

## 🛠 Tech Stack  
- **Frontend:** React / Next.js (UI for interview flow).  
- **Backend:** Node.js / Python (serves question bank API).  
- **Database / Storage:** JSON, SQLite, or PostgreSQL (for questions).  
- **Speech-to-Text (optional):** Web Speech API or Whisper.  

---

## 🚀 How It Works  
1. User selects **Interview Practice Mode**.  
2. System pulls a set of **questions** from the stored bank (JSON/DB).  
3. Questions are displayed one by one.  
4. User answers either by typing or speaking.  
5. After finishing, user can review all questions and their answers.  

---

## 📊 Example Question Categories  
- **HR Questions:** “Tell me about yourself”, “Why should we hire you?”  
- **Technical Questions:** Role-specific coding / theory-based.  
- **Behavioral Questions:** “Describe a challenge you faced in a team.”  
- **Aptitude Questions:** Logic puzzles, reasoning, number problems.  

---

## 📌 Future Scope  
- Add **scoring metrics** (e.g., completeness, keywords matched).  
- Expand question bank beyond 100 questions.  
- Integrate with **LLM module** for dynamic follow-ups.  
- Provide analytics on strengths and weaknesses.  

---

## 📌 About  
This module was built as an **early prototype** of MIDIO’s interview system. It demonstrates the concept of a **virtual interviewer** using a static question set, laying the foundation for future AI-driven improvements.  
