📝 Django Personal Diary App

A clean, user-friendly personal diary application built with Django. Keep track of your thoughts, ideas, and daily reflections in one secure place. With full CRUD functionality, search, and pagination, this app makes managing your notes simple and private with proper user authentication.

✨ Features

* User Authentication – Register, log in, and manage your account securely using Django’s built-in authentication.
* Create Notes – Add personal notes with a title and content effortlessly.
* View Notes – Browse all your notes in a clean, organized list.
* Edit & Delete Notes – Modify or remove notes safely; only the owner has access.
* Search – Quickly filter notes by title.
* Pagination – Navigate through your notes easily with customizable pagination.
* Privacy & Security – Notes are private and accessible only to their owner.

🛠️ Tech Stack

* Backend: Django
* Database: SQLite (default)
* Frontend: Django Templates (HTML, CSS)
* Python Version: 3.13

🚀 Installation

- Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git

- Install dependencies
pip install -r requirements.txt


- Apply migrations
python manage.py makemigrations
python manage.py migrate

- Admin access
python manage.py createsuperuser


- Run the development server
python manage.py runserver

Access the app at http://127.0.0.1:8000 and http://127.0.0.1:8000/admin for admin dashboard