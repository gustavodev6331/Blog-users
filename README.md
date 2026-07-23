# Blog Users

A blog platform built with Flask where users can register, log in, create blog posts, and leave comments.

The project showcases user authentication, CRUD operations, relational database modeling, and SQLite integration. 

<img width="1467" height="871" alt="Screenshot 2026-07-23 at 6 03 31 PM" src="https://github.com/user-attachments/assets/0e8ad616-c49e-4523-9596-4b662c1b71b7" />

<img width="1460" height="865" alt="Screenshot 2026-07-23 at 6 05 07 PM" src="https://github.com/user-attachments/assets/e744ca1c-b278-4fdf-a538-41af57f2bf8b" />

<img width="1464" height="866" alt="Screenshot 2026-07-23 at 6 05 32 PM" src="https://github.com/user-attachments/assets/b485264f-d48b-473d-9009-1c215a5489c7" />

<img width="1463" height="870" alt="Screenshot 2026-07-23 at 6 06 28 PM" src="https://github.com/user-attachments/assets/fc11b86a-f522-41fd-8b10-bfc1c8d39a62" />

<img width="1466" height="866" alt="Screenshot 2026-07-23 at 6 07 25 PM" src="https://github.com/user-attachments/assets/1af66652-c95c-4130-8d41-db4d8e9c010b" />


## Features

- User registration
- User login
- Create blog posts
- Edit blog posts
- Delete blog posts
- Leave comments
- Responsive interface

## Technologies

- Python
- Flask
- SQLAlchemy
- SQLite
- Flask-Login
- Bootstrap
  
## Installation

1. Clone the repository

```bash
git clone https://github.com/gustavodev6331/blog-users.git
```

2. Navigate to the project folder

```bash
cd blog-users
```

3. Create a virtual environment

```bash
python -m venv .venv
```

4. Activate the virtual environment

**macOS / Linux**

```bash
source .venv/bin/activate
```

**Windows**

```bash
.venv\Scripts\activate
```

5. Install the dependencies

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the project root and add the following variables:

```env
FLASK_KEY=your_secret_key
DB_URI=sqlite:///posts.db
```

6. Run the application

```bash
python main.py
```

