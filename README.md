# FastAPI School Management System

A RESTful API built with **FastAPI** and **SQLAlchemy** for managing Students and Teachers in a school system.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| FastAPI | Web framework |
| SQLAlchemy | ORM / Database |
| Pydantic | Data validation |
| SQLite | Database |
| Uvicorn | ASGI server |

---

## Project Structure
fast api/
├── student/
│   ├── init.py
│   ├── models.py
│   ├── router.py
│   ├── schemas.py
│   └── service.py
├── teacher/
│   ├── init.py
│   ├── models.py
│   ├── router.py
│   ├── schemas.py
│   └── service.py
├── databases.py
├── main.py
└── README.md
