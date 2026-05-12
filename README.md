# Flask Todo App

A simple Flask web application for managing todos with SQLite database.

## Setup Instructions

### 1. Create Virtual Environment
```bash
python -m venv venv
```

### 2. Activate Virtual Environment
**Windows:**
```bash
venv\Scripts\activate
```

**Mac/Linux:**
```bash
source venv/bin/activate
```
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python app.py
```

The app will run at `http://localhost:5000`

## Project Structure
```
flask project/
├── app.py              # Main Flask application
├── requirements.txt    # Project dependencies
├── templates/          # HTML templates
│   └── index.html     # Main page
├── static/            # CSS, JavaScript, images
└── README.md          # This file
```

## Features
- ✅ Add new todos
- ✅ Mark todos as completed
- ✅ Delete todos
- ✅ SQLite database persistence
- ✅ Beautiful UI

## Next Steps
- Customize the styling in `templates/index.html`
- Add more routes and features in `app.py`
- Create additional database models in `app.py`
- Add static files (CSS, JS, images) to the `static/` folder
