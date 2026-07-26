# 🎓 StudyMate AI

> An AI-powered study management platform built with Django that helps students organize subjects, generate personalized study plans, monitor progress, and improve learning productivity.

---

# 📖 About the Project

StudyMate AI is a web-based application designed to simplify academic planning and improve study habits. The platform allows students to manage their subjects, set exam dates, prioritize learning goals, and automatically generate personalized study schedules using AI.

In addition to study planning, the application provides task management, progress tracking, gamification features, collaborative study rooms, and email notifications, creating a complete learning management experience for students.

---

# ✨ Key Features

## 🔐 User Authentication

- Secure user registration and login
- Session-based authentication
- User profile management

## 📚 Subject Management

- Add new subjects
- Edit and delete subjects
- Set exam dates
- Assign study priorities

## 🤖 AI Study Planner

- Personalized AI-generated study plans
- Weekly study schedule generation
- Balanced task allocation based on available study hours

## ✅ Task Management

- Daily study tasks
- AJAX-based task completion
- Pending and completed task tracking

## 📊 Dashboard

- Overview of study progress
- Study streak tracking
- Learning statistics

## 🏆 Gamification

- XP reward system
- Achievement badges
- Learning streaks

## 👥 Study Rooms

- Join subject-specific study rooms
- Collaborate with other students
- Community-based learning

## 📧 Email Support

- Study reminder emails
- Contact Us form

## 📱 Responsive Design

- Mobile-friendly interface
- Built with Bootstrap 5

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Backend | Python, Django |
| Database | MySQL |
| Frontend | HTML, CSS, Bootstrap 5 |
| Client-side | JavaScript, AJAX |
| AI Integration | GROQ API |
| Email Service | SMTP |
| Deployment | AWS |
| Version Control | Git & GitHub |

---

# 📁 Project Structure

```text
StudyMate-AI/
│
├── study_mate_ai/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── study_mate_app/
│   ├── migrations/
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   │   └── images/
│   ├── templates/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   └── admin.py
│
├── Screenshots/
├── requirements.txt
├── manage.py
├── .gitignore
└── README.md
```

---

# 🗄️ Database Models

The application includes the following models:

- User
- Subject
- UserSubject
- StudyPlan
- StudyPlanItem
- StudySession
- ProgressSummary
- Notification
- StudyRoom
- RoomMember
- Badge
- UserBadge
- ContactMessage

---

# ⚙️ Installation

## 1. Clone the repository

```bash
git clone https://github.com/Jayanth1129/StudyPlanner.git
cd StudyPlanner
```

## 2. Create a virtual environment

```bash
python -m venv env
```

## 3. Activate the virtual environment

### Windows

```bash
env\Scripts\activate
```

### macOS / Linux

```bash
source env/bin/activate
```

## 4. Install dependencies

```bash
pip install -r requirements.txt
```

## 5. Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

## 6. Create a superuser (Optional)

```bash
python manage.py createsuperuser
```

## 7. Start the development server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000
```

---

# 🚀 Future Enhancements

- 📱 Mobile application
- ⏱️ Pomodoro study timer
- 📅 Google Calendar integration
- 📄 PDF study plan export
- 🎥 Video-enabled study rooms
- 📈 Advanced learning analytics
- 🧠 AI-powered exam recommendations
- 📝 AI-generated quizzes and mock exams
- 🎯 Personalized learning insights
- 🔔 Push notifications

---

# ⭐ Project Highlights

- AI-powered study planning
- Personalized weekly schedules
- Interactive task management
- Progress dashboard and analytics
- Gamification with XP and badges
- Collaborative study rooms
- Responsive Bootstrap interface
- AWS deployment support

---

# 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📄 License

This project was developed for educational and learning purposes.

---

**Developed using Django, MySQL, Bootstrap, JavaScript, and GROQ AI to provide an intelligent study planning experience.**
