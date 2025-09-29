

# Online Quiz Portal for College

## 📌 Project Overview
This is a **full-stack online quiz platform** built with **Flask and SQLite**, featuring **Teacher** and **Student** portals. Teachers can create, manage, and share quizzes, while students can join quizzes, attempt them in real-time, and view their scores. The platform is designed to make learning **interactive, fun, and hassle-free**, while keeping a clean and intuitive interface.

---

## 🚀 Features

### Teacher Portal
- Create quizzes with multiple-choice questions (MCQs)  
- Set timers for quizzes  
- Share quizzes with unique codes  
- View student results in real-time  
- Delete quizzes when needed  

### Student Portal
- Join quizzes using a **share code**  
- Attempt quizzes with a timer  
- View past quiz results and scores  
- Interactive and simple interface for easy navigation  

### Shared Features
- User authentication (signup/login) with **secure password hashing**  
- Dynamic dashboard based on user type  
- Flash messages for real-time notifications  
- Lightweight and easy-to-deploy using Flask & SQLite  

---

## 🛠️ Tech Stack
- **Backend:** Flask, Python  
- **Database:** SQLite, SQLAlchemy ORM  
- **Frontend:** HTML, CSS, Jinja2 Templates  
- **Security:** Password hashing with Werkzeug  

---

## 🎯 How It Works
1. **Teachers** sign up → create quizzes → generate share codes → monitor results  
2. **Students** sign up → enter share code → attempt quiz → view results  
3. Scores are automatically calculated and stored in the database  

---

## 📂 Repository Structure

### Online-Quiz-App/
#### │
#### ├── templates/ .................. HTML templates for all pages
#### ├── static/    .................. CSS, JS, images
#### ├── quiz.db    .................. SQLite database
#### ├── app.py     .................. Main Flask app
#### └── README.md  .................. Project documentation


---

## 💡 Key Learning Points
- Handling user authentication and session management in Flask  
- Creating relational models with SQLAlchemy  
- Implementing dynamic dashboards based on roles  
- Timer-based quiz functionality  
- CRUD operations for quizzes and questions  

---

## ⚡ Future Improvements
- Add **leaderboards** and gamification  
- Implement **real-time notifications** with WebSockets  
- Add **analytics dashboards** for teachers  
- Deploy to a cloud service (Heroku / AWS)  

---

## 👤 Author
**Aditya Kumar Pandey (Lazyfox)**  
Building cool apps that make learning smarter and fun! 🚀  
GitHub: github.com/lazyfoxadddd  
Contact: coderakp@gmail.com




