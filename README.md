# 🔗 URL Shortener — Frontend

A simple Django web interface for the URL Shortener API. Enter a long URL and get a shortened one instantly.

## ✨ Features

- **Clean UI** — minimal Bootstrap 5 form
- **One click shortening** — paste URL, click shorten, done
- **Error handling** — displays errors if something goes wrong
- **Clickable result** — shortened URL is shown as a working link

## 🛠️ Tech Stack

- **Python**
- **Django** — web framework
- **Bootstrap 5** — styling
- **Requests** — communicates with the FastAPI backend

## ⚙️ Setup

1. Clone the repo
2. Create a virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install django requests
   ```
4. Make sure the backend is running at `http://localhost:8000`
5. Run the frontend:
   ```bash
   py manage.py runserver 8080
   ```
6. Visit `http://localhost:8080`

> ⚠️ This frontend requires the URL Shortener Backend to be running first.

## 👤 Author

Made by [@lol_wave](https://t.me/lol_wave)
