# ProManage — Architecture (design phase)

```
Browser
   │
   ▼
Flask app (app.py)
   │
   ├── Flask-Login (auth)
   ├── SQLAlchemy models
   └── Jinja templates
           │
           ▼
      MySQL (promanage_db)
```

## Roles (planned)

- **Admin** — system configuration
- **Supervisor** — review student projects
- **Student** — submit and track project work

## Note

Database migrations via Alembic; environment variables in `.env` (not published here).
