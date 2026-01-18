# My Library 📚

A simple and elegant web application to manage your personal book collection. This application allows users to store book details, rate them, and manage their reading list efficiently.

**Created by:** Param Sangani

## 📖 About
My Library is a CRUD (Create, Read, Update, Delete) application built with **Flask** and **SQLAlchemy**. It serves as a digital bookshelf where you can keep track of the books you own or have read, along with your personal ratings for each.

## 📸 Screenshots

| <img width="503" height="268" alt="Home page" src="https://github.com/user-attachments/assets/2404d2a0-c1f4-46b5-a811-0f5496bbe1ab" />
| <img width="787" height="206" alt="add book" src="https://github.com/user-attachments/assets/742cfcd4-cdfc-4571-bb7a-de63b8897455" />
 

## ✨ Features
* **View Library:** Display a list of all books in your collection.
* **Add New Books:** Input book details including Title, Author, and a Rating out of 10.
* **Edit Ratings:** Update your rating for a book if your opinion changes.
* **Delete Books:** Remove books from your collection permanently.
* **Data Persistence:** Automatically saves your data to a local SQLite database (`new-books-collection.db`).

## 🛠️ Tech Stack
* **Backend:** Python, Flask
* **Database:** SQLite, Flask-SQLAlchemy
* **Frontend:** HTML, CSS (Jinja2 Templates)

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed on your system. You will also need `pip` (Python package manager).

### Installation

1.  **Clone the repository** (or download the project files).

2.  **Install Dependencies**
    Open your terminal or command prompt in the project folder and run:
    ```bash
    pip install Flask Flask-SQLAlchemy
    ```

3.  **Run the Application**
    Execute the Python script:
    ```bash
    python main.py
    ```
    *(Note: Ensure your main python file is named `main.py` or replace it with your actual filename)*

4.  **Open in Browser**
    Go to the following URL in your web browser:
    `http://127.0.0.1:5000`

## 📂 Project Structure

```text
/
├── main.py                 # Main application code (Flask routes & DB model)
├── instance/               # Contains the SQLite database (auto-generated)
└── templates/              # HTML files for the UI
    ├── index.html          # Homepage (List of books)
    ├── add.html            # Page to add a new book
    └── edit.html           # Page to edit book rating
