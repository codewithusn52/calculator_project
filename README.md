# calculator_project
We are SYCS students, building beginner level project : django based calculator, 
# Calculator Project

A beginner-friendly Django web application that provides a fully functional calculator interface. Built as part of our Second Year Computer Science (SYCS) coursework to demonstrate web development basics, server-side request handling, and dynamic template rendering.

---

## 🚀 Features

* **Basic Arithmetic Operations**: Perform addition, subtraction, multiplication, and division.
* **Responsive UI**: Clean and user-friendly web interface.
* **Error Handling**: Graceful feedback for edge cases like division by zero or invalid inputs.

---

## 🛠️ Tech Stack

* **Backend**: Python 3.x, Django
* **Frontend**: HTML5, CSS3, JavaScript
* **Environment**: GitHub Codespaces / Local Environment

---

## ⚙️ Local Setup Instructions

Follow these steps to run the project locally on your machine or inside a GitHub Codespace.

### 1. Clone the Repository

```bash
git clone https://github.com/codewithusn52/calculator_project.git
cd calculator_project

```

### 2. Create and Activate Virtual Environment

* **On Windows:**
```bash
python -m venv venv
venv\Scripts\activate

```


* **On macOS/Linux/Codespaces:**
```bash
python3 -m venv venv
source venv/bin/activate

```



### 3. Install Dependencies

```bash
pip install django

```

*(If you have a `requirements.txt` file, run `pip install -r requirements.txt` instead)*

### 4. Apply Database Migrations

```bash
python manage.py migrate

```

### 5. Run the Development Server

```bash
python manage.py runserver

```

Open your browser and navigate to `[http://127.0.0.1:8000/](http://127.0.0.1:8000/)` to use the app.

---

## 👥 Contributors

* **SYCS Team** — *Initial development and logic integration* ([@codewithusn52](https://www.google.com/search?q=https://github.com/codewithusn52))

---

## 📜 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE).