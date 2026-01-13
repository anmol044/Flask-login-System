# Flask Login System

A simple Flask-based authentication system that provides **user registration, login, logout, and a protected dashboard** using server-side sessions and template inheritance.

---
PROJECT LINK:
https://captivating-nature-production.up.railway.app/

ScreenShots:
<img width="1914" height="986" alt="homeeee" src="https://github.com/user-attachments/assets/fc37347f-8d9b-4522-a518-e5395323f589" />
<img width="1905" height="979" alt="register" src="https://github.com/user-attachments/assets/79a69be0-fa66-456f-865a-163f3911fe2c" />
<img width="1913" height="989" alt="login" src="https://github.com/user-attachments/assets/2b658d53-4279-45ce-90bd-6d91f22289ff" />


## 📁 Project Structure

```
Flask-login-System/
│
├── app.py               # Main Flask application
├── app.db               # SQLite database
├── requirements.txt     # Python dependencies
├── .gitignore
│
├── templates/
│   ├── base.html        # Base layout (template inheritance)
│   ├── home.html        # Home page
│   ├── login.html       # Login page
│   ├── register.html    # Registration page
│   └── dashboard.html   # Protected dashboard
│
└── static/              # CSS, JS, images (if any)
```

---

## 🚀 Features

* User Registration
* User Login & Logout
* Password handling
* Protected Dashboard (login required)
* Template inheritance using `base.html`
* SQLite database for persistence

---

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Frontend:** HTML, Jinja2 Templates
* **Database:** SQLite

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone <your-github-repo-url>
cd Flask-login-System
```

### 2️⃣ Create & Activate Virtual Environment

```bash
python -m venv venv

# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application

```bash
python app.py
```

The app will run at:

```
http://127.0.0.1:5000/
```

---

## 🔐 Routes Overview

| Route        | Description         |
| ------------ | ------------------- |
| `/`          | Home page           |
| `/register`  | User registration   |
| `/login`     | User login          |
| `/dashboard` | Protected dashboard |
| `/logout`    | Logout user         |

---

## 📌 Notes

* Make sure `app.db` exists or is initialized before running.
* `base.html` is used as the parent template for all pages.
* This project is suitable for **learning Flask authentication basics** and can be extended with Flask-Login, password hashing, or role-based access.

---

## 📄 License

This project is for **educational purposes**. Feel free to modify and extend it.

---

## ✨ Future Improvements

* Password hashing with `werkzeug.security`
* Flask-Login integration
* Form validation
* Flash messages & error handling
* Deployment (Render / Railway / PythonAnywhere)

---

### 👨‍💻 Author

**Stavan Katrojwar**
