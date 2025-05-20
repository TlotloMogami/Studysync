# StudySync

**StudySync** is a Django-based personal assistant web app designed to help students manage their time more effectively. It allows students to input their class schedules, study plans, and personal activities — then interact with their timetable through natural language commands powered by AI.

---

## Features

- User authentication with personalized schedules.
- Add, edit, and delete classes, study sessions, and personal activities.
- Natural language command interface for dynamic schedule management.
- Conflict detection and automatic rescheduling.
- Server-rendered UI with simple, clean Django templates.
- Notifications and reminders (planned feature).

---

## How It Works

1. Students enter their weekly class timetable and planned study sessions.
2. Add personal activities such as meetings or social events.
3. Use natural language commands like:
   - "Cancel all plans from 2pm to 4pm today."
   - "Move my study session tomorrow from 10am to 12pm."
   - "Add a break at 3pm."
4. The AI parses commands and updates the schedule in real-time.
5. Students can view their updated timetable on a clean dashboard.

---

## Tech Stack

- Backend: Django, Django REST Framework (optional)
- Frontend: Vanilla Django templates
- AI Integration: OpenAI GPT API (or other NLP API)
- Database: PostgreSQL or SQLite for development

---

## Getting Started

### Prerequisites

- Python 3.8+
- Django 4.x
- An OpenAI API key (if using GPT for command processing)

