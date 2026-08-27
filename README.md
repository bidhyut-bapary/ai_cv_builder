# AI CV Builder

An AI-powered CV builder web application built with Flask and MySQL.
Supports General CVs and Job-Targeted CVs with AI writing assistance.

## Status
🚧 Under active development — see phases below.

## Tech Stack
- **Backend:** Python 3, Flask, Flask-SQLAlchemy, Flask-Login, Flask-WTF
- **Database:** MySQL (SQLAlchemy ORM)
- **Frontend:** HTML5, CSS3, Vanilla JavaScript, Bootstrap 5
- **PDF:** WeasyPrint
- **AI:** Configurable provider via environment variables

## Features (planned)
- Secure authentication (register/login/logout)
- User profile with photo upload
- General CV & Targeted CV builder
- AI writing assistant (summary, experience, projects — never fabricates facts)
- Job description analysis & ATS optimization
- Multiple CV templates
- Live preview
- PDF export
- Dashboard with duplication support

## Setup
_(Instructions will be added in Phase 2 — Environment Setup)_

## Project Structure
See `docs/architecture.md` (to be added) or the folder layout below:

\`\`\`
ai_cv_builder/
├── app/
│   ├── models/       # SQLAlchemy models
│   ├── routes/       # Flask blueprints
│   ├── services/      # AI, PDF, ATS, file-handling logic
│   ├── forms/          # WTForms
│   ├── templates/       # Jinja templates (UI + cv_templates/)
│   └── static/            # CSS, JS, images
├── migrations/
├── tests/
├── run.py
├── requirements.txt
└── .env.example
\`\`\`

## License
TBD
