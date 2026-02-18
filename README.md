# Flask Authentication App

A simple Flask web application with user registration, login, and dashboard functionality.  

It uses **Flask**, **Flask-SQLAlchemy**, and **bcrypt** for secure password hashing.

---

## 🚀 Features

- User registration with hashed passwords
  
- User login with session management
  
- Dashboard accessible only to logged-in users
  
- Logout functionality
  
- SQLite database for persistence

---

## 📂 Project Structure

flask_auth_app/

│

├── app.py  

├── database.db  

├── templates/

   ├── index.html 
   
   ├── register.html 
   
   ├── login.html 
   
   └── dashboard.html 
   
   ├── requirements.txt   
   
└── Procfile           

---


---

## ⚙️ Installation & Setup

1. Clone the repository:
   
   ```bash
   
   git clone https://github.com/your-username/flask_auth_app.git
   
   cd flask_auth_app
   
2. Create a Virtual Enviornment

   python -m venv venv

   source venv/bin/activate   # macOS/Linux

    venv\Scripts\activate      # Windows

3. Install Dependensies
   
   pip install -r requirements.txt

5. Run the app
   
   python app.py   


