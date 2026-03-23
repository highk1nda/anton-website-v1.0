# 🌐 Personal Website v1.0

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-2.x-black?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![SCSS](https://img.shields.io/badge/SCSS-supported-CC6699?logo=sass&logoColor=white)](https://sass-lang.com/)
[![Deployment](https://img.shields.io/badge/Deployment-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![Status](https://img.shields.io/badge/Status-Archived-lightgrey)](https://github.com/highk1nda/anton-website-v2.0)

> ⚠️ **Archived** — This is an older version of my personal website and is no longer maintained.
>
> 👉 **Live site (v2.0):** [antonsatsuk.com](https://antonsatsuk.com)
>
> 📂 **New repository:** [anton-website-v2.0](https://github.com/highk1nda/anton-website-v2.0)

---

## 📖 About

This is the first version of my personal website, built with **Flask** as the backend framework. It served as my initial attempt at building and deploying a complete personal website from scratch.

The site includes multiple pages (Home, About Me, Experience, Contacts) and a working contact form that saves submitted messages to a local file.

---

## 📁 Project Structure

```
anton-website-v1.0/
│
├── app.py                    # Flask application — routing and form handling
│
├── templates/                # Jinja2 HTML templates
│   ├── index.html            # Home page
│   ├── about_me.html         # About Me page
│   ├── expirience.html       # Experience page
│   └── contacts.html         # Contacts page with form
│
├── static/
│   ├── css/                  # Compiled CSS stylesheets (per-page)
│   ├── scss/                 # SCSS source files
│   ├── scripts/
│   │   └── script.js         # Frontend JavaScript
│   └── images/               # Images, icons, and SVGs
│
├── data/
│   └── form_data.txt         # Stores contact form submissions
│
└── .github/
    └── workflows/
        └── static.yml        # GitHub Actions deployment workflow
```

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS/SCSS, JavaScript
- **Deployment:** GitHub Actions

---

## ⚙️ Requirements & Running Locally

Make sure you have **Python 3.x** installed, then install the dependencies:

```bash
pip install flask
```

Run the development server:

```bash
python app.py
```

The site will be available at `http://127.0.0.1:5000`.

> **Note:** If you want to edit styles, you'll also need [Sass](https://sass-lang.com/install) to compile the `.scss` files. A helper script `static/watch_sass.sh` is included for that.

---

## 📌 Status

Archived — not in active development. See [antonsatsuk.com](https://antonsatsuk.com) for the current version.

---

## 📬 Contacts

- **LinkedIn:** [linkedin.com/in/antonsatsuk](https://www.linkedin.com/in/antonsatsuk/)
- **Email:** satsuk.anton@gmail.com

---

<p align="center">
  <strong>Have fun, do pobachennya 👋</strong>
</p>

<p align="center">
  <a href="https://github.com/highk1nda">More projects by highk1nda 🚧</a>
</p>
