# Python Flask TODO App

![Flask-based Python TODO app](https://daehnhardt.com/images/screenshots/flask/todo_app_v2.png)

**Build a simple task manager with Python, Flask, and SQLite.** This repository accompanies a detailed [tutorial post](https://daehnhardt.com/blog/2025/02/11/todo-flask-app/) that shows you how to create a functional TODO web application. You’ll learn key steps for setting up Flask routes, rendering templates, and managing data with an SQLite database.  

## Features
- **Create tasks** and set their priority (High, Medium, Low).
- **Mark tasks as complete** with a single click.
- **Edit and delete** existing tasks.
- **Store data** in a lightweight SQLite database for persistence.
- **Minimal CSS styling** for an easy-to-improve UI.

## Getting Started
1. **Clone the repository:**
   ```bash
   git clone https://github.com/edaehn/todo_app.git
   cd todo_app
   ```
2. **Create and activate a virtual environment (recommended):**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate   # Linux/macOS
   .venv\Scripts\activate      # Windows
   ```
3. **Install dependencies:**
   ```bash
   pip install Flask
   ```
4. **Run the app:**
   ```bash
   python app.py
   ```
5. **Open your browser** at [http://127.0.0.1:5000](http://127.0.0.1:5000) to view your TODO list.

## Contributing
Feel free to fork this project and make pull requests with new features, fixes, or styling improvements. Check the [tutorial post](https://daehnhardt.com/blog/2025/02/11/python-flask-todo-app) for extended explanations and references.

**If you find this project helpful, please give it a star—it means a lot!**  

Enjoy coding, and happy task managing!
