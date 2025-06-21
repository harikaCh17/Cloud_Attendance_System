
# Cloud Attendance System

A cloud-based Django application for managing student attendance. This system supports admin login, session tracking, attendance visualization, and role-based access.

---

## 🧠 Project Overview

This Django-based project is designed to streamline the process of tracking student attendance. It includes both admin and user functionalities and uses REST APIs for backend operations.

---

## 🔧 Architecture

![Cloud Attendance Architecture](https://github.com/kujalk/Cloud_Attendance_System/blob/main/cloud2.PNG)

---

## 🚀 Features

- Admin authentication system
- Attendance session handling
- Role-based user views
- API integration with Django REST Framework
- CORS configuration for cross-origin requests
- Simple UI with visual attendance display

---

## 🛠️ Tech Stack

- **Backend:** Django 2.2, Django REST Framework  
- **Frontend:** HTML, CSS (Django templates)  
- **Database:** SQLite (default)  
- **Other Tools:** Python 3.10, CORS headers

---

## 🖥️ Setup Instructions

### Prerequisites:
- Python 3.10 installed
- GitHub account
- VS Code (recommended)

### Steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/cloud-attendance-system.git
   cd cloud-attendance-system
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate   # On Windows
   ```

3. **Install the requirements**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations and start the server**
   ```bash
   python manage.py migrate
   python manage.py createsuperuser
   python manage.py runserver
   ```

5. **Access the server**
   Open your browser and go to:  
   [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## 📑 Useful Resources

- [Different Views Based on User Privileges](https://scripting4ever.wordpress.com/2021/03/23/different-views-based-on-users-privileges-in-django-application/)

---

## 👩‍💻 Developer

**Harika Chennupati**  
Intern @ SlashMark

*Original Developer Reference: K. Janarthanan*
