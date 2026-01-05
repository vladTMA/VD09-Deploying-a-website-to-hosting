#🇬🇧 **READMEen.md **

# 🎮 Clicker — Flask Web Application

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue" />
  <img src="https://img.shields.io/badge/Flask-3.0-black" />
  <img src="https://img.shields.io/badge/Bootstrap-5.3-purple" />
  <img src="https://img.shields.io/badge/SQLite-Database-green" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
</p>

A small educational project demonstrating the basics of Flask: routing, templates, forms, authentication, and database work.  
The application is deployed on PythonAnywhere.

---

## 🚀 Features
- 🔐 User registration and login  
- 🔑 Password hashing (Flask‑Bcrypt)  
- 🗄 SQLite + SQLAlchemy  
- 🎯 Individual click counter  
- 🎨 Custom game‑style button  
- 🧩 Bootstrap + custom CSS  
- 🔒 Protected routes (`@login_required`)  

---

## 🛠 Technologies
- Python 3  
- Flask  
- Flask‑Login  
- Flask‑WTF  
- Flask‑Bcrypt  
- Flask‑SQLAlchemy  
- WTForms  
- Bootstrap 5  
- Jinja2  

---

## 📁 Project Structure

```text
project/
│   main.py
│   requirements.txt
│   README.md
│   READMEru.md
│   READMEen.md
│
└───app/
    │   __init__.py
    │   models.py
    │   routes.py
    │   forms.py
    │
    ├───templates/
    │       base.html
    │       index.html
    │       login.html
    │       register.html
    │
    └───static/
            style.css
            
```
---

## ⚙️ Local Installation

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd project
```

### 2. Create a virtual environment

```bash
python -m venv venv
.\venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Initialize the database

Ensure `main.py` contains:

```python
with app.app_context():
    db.create_all()
```
Run once:

```bash
python main.py
```

### 5. Start the application

```bash
python main.py
```
---

## 🌐 Deployment on PythonAnywhere

- upload project files
- configure virtual environment
- install dependencies
- configure WSGI
- press Reload

---

## 📜 License

Free for educational use.
