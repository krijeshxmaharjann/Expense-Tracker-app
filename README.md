# Expense Tracker (Flask + Python)

A simple web-based **Expense Tracker** built with **Flask and SQLite** that allows users to add and track daily expenses.

This project demonstrates backend development using **Python, Flask, SQLAlchemy, and HTML templates**.

---

## Features

* Add new expenses
* View all expenses
* Categorize expenses
* Track total spending
* Store data using SQLite database
* Flash messages for user feedback

---

## Technologies Used

* Python
* Flask
* Flask-SQLAlchemy
* SQLite
* HTML (Jinja Templates)

---

## Project Structure

```
expense-tracker/
│
├── app.py
├── README.md
├── .gitignore
│
├── instance/
│   └── expenses.db
│
├── templates/
│   └── index.html
│
└── venv/
```

---

## Installation

Clone the repository:

```
git clone https://github.com/krijeshxmaharjann/expense-tracker.git
```

Go into the project folder:

```
cd expense-tracker
```

Create virtual environment:

```
python -m venv venv
```

Activate virtual environment:

Windows:

```
venv\Scripts\activate
```

Mac/Linux:

```
source venv/bin/activate
```

Install dependencies:

```
pip install flask flask-sqlalchemy
```

---

## Run the Application

Start the Flask server:

```
python app.py
```

Open in browser:

```
http://127.0.0.1:4848
```

---

## Example Categories

* Food & Dining
* Transportation
* Housing
* Entertainment
* Health & Fitness
* Shopping
* Education
* Miscellaneous

---

## Future Improvements

* Edit expenses
* Delete expenses
* Monthly analytics
* Expense charts
* User authentication
* Export to CSV

---

## Author

**Krijesh Maharjan**

Computer Science Student | Aspiring Software Engineer

GitHub: https://github.com/krijeshxmaharjann

