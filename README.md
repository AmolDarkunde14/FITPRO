FitnessPro – Django Gym Management App

FitnessPro is a role-based gym management system built with Django, enabling members to view personalized workout and diet plans while allowing admins to securely manage users, attendance, and other operations through a dedicated dashboard.

Features

User Panel -
User login and signup
View daily exercise plan
View recommended diet plan
Delete profile
Change password
Update profile picture

Admin Panel (Gym Manager) -
Add new users
Record attendance
View all members
Change password
Search members by name, username, or ID

Tech Stack

Backend: Django (Python)
Database: SQLite3
Frontend: Django Templates (HTML, CSS, JavaScript)

Folder Structure -

FITPRO/
│
├── FITNESSPRO/              # Django project folder
├── gym/                     # Main app containing models, views, templates
├── media/                   # saved media
│     └── users_profile_images/    # Users profile images
├── screenshots/             # Project live demo screenshots
├── db.sqlite3               # Database file
├── manage.py
└── requirements.txt

-- Inspired by real-world gym operations
