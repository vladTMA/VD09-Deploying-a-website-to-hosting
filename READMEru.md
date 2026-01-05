#**READMEru.md **

# 🎮 Кликер — веб‑приложение на Flask

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue" />
  <img src="https://img.shields.io/badge/Flask-3.0-black" />
  <img src="https://img.shields.io/badge/Bootstrap-5.3-purple" />
  <img src="https://img.shields.io/badge/SQLite-Database-green" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
</p>

Мини‑проект, демонстрирующий основы веб‑разработки на Flask: маршруты, шаблоны, формы, авторизацию и работу с базой данных.  
Приложение развёрнуто на PythonAnywhere.

---
## 🚀 Функциональность
- 🔐 Регистрация и авторизация  
- 🔑 Хеширование паролей (Flask‑Bcrypt)  
- 🗄 SQLite + SQLAlchemy  
- 🎯 Индивидуальный счётчик кликов  
- 🎨 Игровая кнопка с кастомным стилем  
- 🧩 Bootstrap + собственный CSS  
- 🔒 Защищённые маршруты (`@login_required`)  

---
## 🛠 Технологии
- **Python 3**
- **Flask**
- **Flask‑Login**
- **Flask‑WTF**
- **Flask‑Bcrypt**
- **Flask‑SQLAlchemy**
- **WTForms**
- **Bootstrap 5**
- **Jinja2**

---
## 📁 Структура проекта

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
## ⚙️ Установка и запуск

### 1. Клонировать репозиторий

```bash
git clone <your-repo-url>
cd project
```
### 2. Создать виртуальное окружение

```bash
python -m venv venv
.\venv\Scripts\activate
```

### 3. Установить зависимости

```bash
pip install -r requirements.txt
```

### 4. Создать базу данных

В `main.py` должны быть строки:

```python
with app.app_context():
    db.create_all()
```

### 5. Запустить один раз:

```bash
python main.py
```
---
## 🌐 Деплой на PythonAnywhere

- загрузить файлы проекта
- настроить виртуальное окружение
- установить зависимости
- указать путь в WSGI
- нажать Reload в панели управления

---
## 📜 Лицензия

Проект доступен для свободного использования в учебных целях.


