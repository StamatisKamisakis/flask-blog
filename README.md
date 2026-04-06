# Stamatis's Blog

A full-featured Flask blog application with user authentication, database management, and a modern responsive design.

## 🌐 Live Demo

**Visit the live website:** [https://web-production-28151.up.railway.app](https://web-production-28151.up.railway.app)

## 🚀 Features

- **User Authentication** - Secure registration and login with password hashing
- **Blog Posts** - Create, edit, and delete blog posts (admin only)
- **Comments** - Users can comment on blog posts
- **Responsive Design** - Works on mobile, tablet, and desktop
- **PostgreSQL Database** - Reliable cloud database for production
- **CKEditor** - Rich text editing for blog content

## 🛠️ Technologies Used

- **Backend:** Python, Flask, Flask-SQLAlchemy
- **Database:** PostgreSQL (Railway)
- **Frontend:** HTML, CSS, Bootstrap 5
- **Authentication:** Flask-Login, Werkzeug
- **Forms:** WTForms, Flask-WTF

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/StamatisKamisakis/flask-blog.git
cd flask-blog
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run locally:
```bash
python main.py
```

Visit `http://127.0.0.1:5000` in your browser.

## 🔧 Environment Variables

Create a `.env` file with:
```
FLASK_KEY=your_secret_key
DATABASE_URL=postgresql://user:password@localhost/dbname
```

## 📝 Usage

1. Register a new account
2. Login with your credentials
3. Create new blog posts (first user becomes admin)
4. Comment on posts
5. Manage posts via the dashboard

## 👤 Author

- **Stamatis Kamisakis** - [GitHub](https://github.com/StamatisKamisakis)

## 📄 License

This project is for educational purposes.
