.
├── .gitignore
├── README.md
├── LICENSE
├── docs/                  # Dokumentasi proyek
├── assets/                # Aset mentah (gambar, audio, font, shader)
│   ├── images/
│   ├── audio/
│   └── fonts/
├── client/                # Kode proyek Godot
│   ├── project.godot
│   ├── default_env.tres
│   ├── export_presets.cfg
│   ├── addons/            # Plugin pihak ketiga
│   ├── autoload/          # Singleton global (misalnya Globals.gd)
│   ├── scenes/            # File scene (.tscn)
│   │   ├── main/
│   │   ├── levels/
│   │   └── ui/
│   ├── scripts/           # Skrip GDScript, C#, atau Python
│   │   ├── controllers/
│   │   ├── gameplay/
│   │   └── ui/
│   ├── shaders/           # File shader (.gdshader)
│   └── theme/             # Resource UI (.tres)
├── server/                # Backend FastAPI
│   ├── app/
│   │   ├── main.py
│   │   ├── api/           # Routing dan endpoint
│   │   ├── models/        # SQLAlchemy models
│   │   ├── schemas/       # Pydantic schemas
│   │   ├── crud/          # Operasi database
│   │   ├── core/          # Config, security (JWT, passlib)
│   │   └── db/            # Database (engine, session, migrations)
│   ├── alembic/           # Migrasi skema database
│   ├── requirements.txt
│   └── Dockerfile
├── tests/                 # Unit dan integration tests
├── .github/               # Workflow CI/CD (GitHub Actions)
│   └── workflows/
└── deployment/            # Skrip dan configs untuk deployment (Docker Compose, Helm)
