
# Python Real-Time Chatroom

A simple real-time chatroom built with Python, Flask, and Socket.IO.

## 🧩 Features

- Real-time two-way chat communication between clients
- Built on Flask for fast web development
- Powered by Flask-SocketIO (WebSockets under the hood)
- Clean, minimal interface with Bootstrap for styling
- Easy to extend — add user login, rooms, message history, and more!

## ⚙️ Requirements

- Python 3.7+
- `pip` package manager

## 📦 Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/naasamajh1/Python-RealTime-Chatroom.git
   cd Python-RealTime-Chatroom
   ```

2. **Create and activate a virtual environment** (optional, but recommended)  
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # Linux/macOS
   venv\Scripts\activate      # Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**  
   ```bash
   python app.py
   ```
   By default, the server runs on: http://127.0.0.1:5000

## 🚀 Usage

- Open your browser and navigate to `http://127.0.0.1:5000`
- Enter a username to join the chatroom
- Chat in real time with other users on the same network or host

## 🛠️ Code Overview

- `app.py` — Main Flask application setup with Socket.IO handlers
- `templates/index.html` — Chatroom front-end built with HTML5 and Bootstrap
- `static/` — Contains CSS, JS, and any media assets

## 🔧 Customization Ideas

- Add room creation and joining (multi-room support)
- Persist chat history with a database (SQLite, Redis, MongoDB)
- Enable private messaging between users
- Add authentication (Flask-Login, OAuth)
- Deploy to production (Gunicorn + Nginx, or Heroku)

## 📜 License

This project is open source, feel free to use it and improve upon it!

---

*Created and maintained by [naasamajh1](https://github.com/naasamajh1). Contributions are welcome!*
