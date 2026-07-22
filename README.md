# Blog Users

A blog platform built with Flask where users can register, log in, create blog posts, and leave comments.

The project showcases user authentication, CRUD operations, relational database modeling, and SQLite integration. 

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

