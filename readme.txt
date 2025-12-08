facial_scanner_2025/
│
├── 📁 app/
│   ├── 📄 main.py              # Punto de entrada principal
│   ├── 📄 scanner.py           # Lógica principal del escáner
│   ├── 📄 detector.py          # Detección de rostros y accesorios
│   ├── 📄 recognizer.py        # Reconocimiento facial
│   ├── 📄 database.py          # Gestión de base de datos
│   ├── 📄 trainer.py           # Entrenamiento del modelo
│   ├── 📄 utils.py             # Utilidades generales
│   └── 📁 gui/                 # Interfaz gráfica
│       ├── 📄 main_window.py
│       ├── 📄 register_window.py
│       └── 📄 scanner_window.py
│
├── 📁 models/
│   ├── 📄 face_detector.onnx   # Modelo detección (optimizado)
│   ├── 📄 face_recognizer.onnx # Modelo reconocimiento
│   └── 📄 accessories_detector.pt  # Detector de accesorios
│
├── 📁 database/
│   ├── 📄 facial_database.db   # Base de datos SQLite
│   └── 📁 embeddings/          # Vectores faciales serializados
│
├── 📁 dataset/
│   ├── 📁 registered/
│   │   ├── 📁 jeremy_valdivieso/
│   │   │   ├── 📸 photo_1.jpg
│   │   │   ├── 📸 photo_2.jpg
│   │   │   └── 📄 metadata.json
│   │   └── ...
│   ├── 📁 unknown/             # Rostros no identificados
│   └── 📁 accessories/         # Dataset de accesorios
│
├── 📁 config/
│   ├── 📄 settings.yaml        # Configuración del sistema
│   ├── 📄 thresholds.yaml      # Umbrales y parámetros
│   └── 📄 paths.yaml           # Rutas del sistema
│
├── 📁 logs/
│   └── 📄 system.log           # Logs de actividad
│
├── 📁 requirements/
│   └── 📄 requirements.txt     # Dependencias
│
├── 📄 train_model.py           # Script de entrenamiento
├── 📄 register_person.py       # Registro de nuevas personas
├── 📄 run_scanner.py           # Ejecutar escáner
├── 📄 backup_database.py       # Backup de datos
├── 📄 test_system.py           # Pruebas del sistema
└── 📄 README.md                # Documentación