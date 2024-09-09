# Movie reviews

This project is a simple movie rating portal built using Python and Flask. The portal allows users to view movie reviews, add new reviews.

## Features

- View all movies on the main page.
- Add reviews.
- View user reviews.

## Technologies Used

- **Programming Language:** Python
- **Web Framework:** Flask
- **Database:** SQLite with SQLAlchemy ORM
- **HTML Templating:** Jinja2
- **Form Handling:** Flask-WTF

## Installation & Setup

### 1. Clone the repository:

```bash
git clone https://github.com/iwannafly69/movie_reviews.git
cd movie_reviews
```
### 2. Set up a virtual environment:

```bash
python3 -m venv venv

source venv/bin/activate  # For Linux/Mac

venv\Scripts\activate  # For Windows
```
### 3. Install the dependencies:

```bash
pip install -r requirements.txt
```

### 4. Initialize the database:

```bash
flask shell
>>> from main import db
>>> db.create_all()
>>> exit()
```

### 5. Run the application:

```bash
flask run
```

Access the portal at http://127.0.0.1:5000 in your web browser.


## Usage



## Author
Developed by [iwannafly69](https://github.com/1sten)

- Email: iwannafly666@yandex.ru
- GitHub: [iwannafly69](https://github.com/iwannafly69)
