# 🐍 Python Online Compiler

A full-screen, browser-based Python compiler built using **React + Vite** on the frontend and **Django** on the backend. It supports Python code execution with `input()`, displays output in real-time, and mimics terminal behavior.

## 🚀 Features

- 🔤 Write and run Python code in the browser
- 📥 Supports multiple `input()` values
- 💻 Output displayed just like a real terminal
- ⌨️ Run with `Shift+Enter`
- 🌓 Dark mode editor with syntax highlighting
- ⚙️ Django backend executes code securely
- 📡 Full CORS support for local development

---

## 🧩 Tech Stack

### Frontend:
- [React](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [CodeMirror 6](https://codemirror.net/6/) with:
  - `@codemirror/view`
  - `@codemirror/state`
  - `@codemirror/lang-python`
  - `@codemirror/theme-one-dark`
- Tailwind CSS (optional, or custom CSS)
- React Router (for routing support, optional)

### Backend:
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)
- Python 3.x
- `subprocess` module (for executing Python code safely)

---

## 📁 Folder Structure

my-python-compiler/
│
├── backend/ # Django project
│ ├── compiler/ # Django app
│ └── api/execute-code/ # API to run Python code
│
├── frontend/ # React + Vite project
│ ├── src/
│ │ ├── PythonCompiler.jsx
│ │ └── PythonCompiler.css
│ └── index.html
