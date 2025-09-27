# Learning Log (Django Project)

A simple web application built with **Django** for tracking learning topics and entries.  
This project is based on the *Learning Log* example from the book *Python Crash Course*.

---

## ✨ Features
- User authentication (sign up / log in / log out)
- Create personal **topics**
- Add multiple **entries** under each topic
- Edit existing entries
- Data isolation → each user only sees their own topics and entries

---

## 🛠 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/learning-log.git
   cd learning-log
   
2. Create a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate   # Windows
    source venv/bin/activate   # Mac/Linux
   
3. Install dependencies:
    ```bash
   pip install -r requirements.txt

4. migrations:
    ```bash:
   python manage.py migrate

5. Create a superuser (optional):
    ```bash:
   python manage.py createsuperuser

6. Run the server:
    ```bash:
   python manage.py runserver

7. Open the app in your browser:
    http://127.0.0.1:8000/


