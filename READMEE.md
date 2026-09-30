# FitBuddy - AI Fitness Plan Generator

FitBuddy is an AI-powered fitness planning web application.

It uses:

- FastAPI
- Google Gemini
- SQLite
- SQLAlchemy
- Jinja2
- HTML
- CSS
- Pydantic

## Features

1. User registration
2. Personalized 7-day workout plan
3. Nutrition/recovery tip
4. Feedback-based plan updates
5. SQLite database
6. Admin dashboard
7. REST API
8. Swagger API documentation
9. Demo mode
10. Automated tests

---

# Project structure

```text
FitBuddy/
│
├── app/
│   ├── __init__.py
│   ├── main.py
│   ├── config.py
│   ├── database.py
│   ├── schemas.py
│   ├── prompts.py
│   ├── gemini_client.py
│   ├── gemini_generator.py
│   ├── gemini_flash_generator.py
│   ├── updated_plan.py
│   └── routes.py
│
├── templates/
│   ├── index.html
│   ├── result.html
│   └── all_users.html
│
├── static/
│   └── css/
│       └── style.css
│
├── tests/
│   └── test_app.py
│
├── .env
├── .env.example
├── .gitignore
├── requirements.txt
└── README.md