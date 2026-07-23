# Blog Users

A blog platform built with Flask where users can register, log in, create blog posts, and leave comments.

The project showcases user authentication, CRUD operations, relational database modeling, and SQLite integration. 

<img width="1465" height="837" alt="Screenshot 2026-07-23 at 7 33 43 PM" src="https://github.com/user-attachments/assets/cc18c112-a776-4443-8544-5f39d8d94e7f" />



<img width="1467" height="835" alt="Screenshot 2026-07-23 at 7 34 34 PM" src="https://github.com/user-attachments/assets/e93dcd67-809d-469b-9d01-0fbaddf2b2eb" />


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

