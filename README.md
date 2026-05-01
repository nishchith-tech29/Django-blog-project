## 📌 Django Project (Corey Schafer Tutorial)

A fully functional Django web application built while following Corey Schafer’s Django tutorial series. This project demonstrates core backend development concepts including models, views, templates, authentication, and CRUD operations.

---

## 🚀 Features

- User Authentication (Login / Logout / Register)
- Create, Read, Update, Delete (CRUD) posts
- User profiles with profile pictures
- Password reset via email
- Responsive UI using HTML & CSS
- Django Admin Panel

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS
- **Database:** SQLite (default)
- **Other:** Django ORM, Authentication System

---

## 📂 Project Structure

```
dproject/
│
├── users/          # User authentication & profiles
├── blog/           # Main app (posts, views, models)
├── dproject/       # Project settings
├── db.sqlite3
├── manage.py
```

---

## ⚙️ Installation & Setup

1. Clone the repository  
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Create virtual environment  
```
python -m venv venv
venv\Scripts\activate   # Windows
```

3. Install dependencies  
```
pip install -r requirements.txt
```

4. Run migrations  
```
python manage.py migrate
```

5. Start server  
```
python manage.py runserver
```

6. Open in browser  
```
http://127.0.0.1:8000/
```

---

## 🔑 Admin Access

Create a superuser:
```
python manage.py createsuperuser
```

Access admin panel:
```
http://127.0.0.1:8000/admin/
```



## 🎯 Learning Outcome

- Understanding Django MVT architecture  
- Building real-world web apps  
- Handling authentication and user sessions  
- Working with databases using ORM  

---

## 📌 Future Improvements

- Add REST API (Django REST Framework)  
- Deploy on cloud (Render / AWS)  
- Improve UI with Bootstrap / Tailwind  
- Add comments & likes feature  

---

## 🙌 Acknowledgment

Based on Corey Schafer’s Django tutorial series.
