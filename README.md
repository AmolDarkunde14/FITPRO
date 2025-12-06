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
```
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
```
-- Inspired by real-world gym operations

Screenshots

Homepage-
<img width="1919" height="1065" alt="image" src="https://github.com/user-attachments/assets/82388bae-777f-4d0b-9490-4e28972fc15c" />
The homepage shows featured exercises and clean navigation for gym users.

<img width="1919" height="985" alt="image" src="https://github.com/user-attachments/assets/f2ba54b9-3b91-4217-8d5f-3f0c1ae0b9ed" />

 User Panel-
<img width="1919" height="994" alt="image" src="https://github.com/user-attachments/assets/875b9171-d7a3-47f2-a21e-900f446dafd9" />
Users can view their assigned workout for the day, check their diet plan, and manage their profile settings.

<img width="1919" height="984" alt="image" src="https://github.com/user-attachments/assets/2d872a2c-60ca-4142-98fd-bcc90dce6716" />

<img width="905" height="959" alt="image" src="https://github.com/user-attachments/assets/5759ec90-1dbc-4baf-8492-2edebb1fb95d" />

Admin Panel-
<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/75d5abe2-1f75-435e-b36d-d76efd251828" />
Gym admins can add users, take attendance, and manage member data securely from the dashboard.





