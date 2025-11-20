Backend del proyecto [FullStack] Administrador de Notas: API REST para registro/login (JWT) y CRUD de notas con soporte de contenido en Markdown.
Este README explica cómo levantar, probar y desplegar el backend.

🧭 Stack principal

Python 3.10+

FastAPI (API web)

SQLModel (modelos ORM + Pydantic — sobre SQLAlchemy)

PostgreSQL (base de datos)

python-jose (jose) — JWT

passlib[bcrypt] — hashing de contraseñas

Uvicorn — servidor ASGI

📁 Estructura principal 
backend/
├─ main.py
├─ database.py
├─ utils.py            
├─ services/
│  ├─ user_service.py
│  └─ note_service.py
├─ controllers/
│  ├─ user_controller.py
│  └─ note_controller.py
├─ models/
│  ├─ user.py
│  └─ note.py
├─ schemas/
│  ├─ user_schema.py
│  └─ note_schema.py
├─ requirements.txt
└─ ...
