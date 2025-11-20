# TinyToDo Project

TinyToDo is a simple and clean to-do list web application built with **Flask**, **HTML**, and **CSS**. It allows users to create tasks, set due dates, assign categories and priority levels, mark tasks as completed, and delete them. All task data is stored locally in a JSON file so the app stays lightweight and easy to run.

---

## 👥 Members

* **Nico Gibson**
* **Bao Phuc Nguyen**

---

## ✨ Features

Users can:

* Add tasks with:

  * Title
  * Due date
  * Category (School, Work, Home, Personal)
  * Priority (High, Medium, Low)
* Mark tasks as completed
* Delete tasks
* Store tasks persistently using `tasks.json`

---

## 📁 Project Structure

```
project/
│── app.py
│── tasks.json
│── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── styles.css
```

---

## 🛠 Installation

### 1. Clone the repository

```bash
git clone https://github.com/baophucnguyen761/TinyTodo.git
cd TinyTodo
```

---

### 2. (Optional but recommended) Create a virtual environment

A **virtual environment (venv)** keeps your project’s Python packages separate from your system packages.
If you're new to Python, this helps avoid version conflicts.

#### **macOS / Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

#### **Windows**

```bash
python3 -m venv venv
venv\Scripts\activate
```

If the venv is activated, your terminal will look like this:

```
(venv) your-computer:~/TinyTodo$
```

To deactivate later:

```bash
deactivate
```

---

### 3. Install required packages

```bash
pip install flask
```

---

## ▶️ Running the Application

Inside the project folder, start the Flask server:

```bash
python3 app.py
```

Then open your browser and go to:

```
http://127.0.0.1:5000/
```
---

## 📦 Data Storage

All tasks are saved in **tasks.json**, which is generated automatically when the application runs.
Each task includes:

```json
{
  "title": "",
  "done": false,
  "due": "",
  "category": "",
  "priority": ""
}
```

---

## 🚀 Future Improvements

* Edit task button
* Search & filtering
* Drag-and-drop sorting
* User login system
* Time / Clock widget
* Built-in Timer feature

---

## 🖼 Demo UI

<img width="1460" height="839" alt="Screenshot" src="https://github.com/user-attachments/assets/33f90ebd-e409-466c-a2d3-190ba37681fe" />

---

## 📄 License

This project is for educational and personal use.
Feel free to modify and extend it.

