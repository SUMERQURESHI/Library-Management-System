# 📚 Library Management System (LMS)

# 🔍 Description
The "Library Management System" is a full-stack web application developed using "Python and Django". It is designed to manage and automate various library operations such as managing books, users, and transactions.

The system provides functionalities for both admin and users:
- Admin can add, update, or remove books, manage users, and monitor book issue/return status.
- Users can search for books, request to borrow them, and check their borrowing history.

This project includes a clean UI, authentication system, and a backend database using "SQLite".

---

## 🛠️ Tech Stack

| Layer         | Technology     |
|---------------|----------------|
| Language  | Python 3       |
| Framework | Django         |
| Database  | SQLite         |
| Frontend  | HTML, CSS, Bootstrap (via Django templates) |
| Version Control | Git & GitHub |

---

## 🚀 How to Run the Project

```bash
# 1. Clone the repository
git clone https://github.com/your-username/Library-Management-System.git

# 2. Navigate to the project folder
cd Library-Management-System/LMS

# 3. Install required packages (recommended: use virtualenv)
pip install -r requirements.txt  # If available

# 4. Run migrations
python manage.py makemigrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver


Then visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## ✅ Features

- 👤 User and admin login system
- 📚 Add, update, delete books
- 📖 Book issue and return tracking
- 📊 Dashboard for monitoring activity
- 🔐 Role-based access (admin/user)

---

## 📂 Project Structure (Important Files)

 `main.py` – Entry point (if used separately)
 `LMS/manage.py` – Django management script
 `LMS/LMS/settings.py` – Project settings
 `LMS/db.sqlite3` – Database file
`.idea/` – IDE config (for PyCharm)

---

## 👨‍💻 Author

Name – Mohammad Sumer Qureshi 
Name - Kabinand Rathod
