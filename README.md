# simple-python-http
Simple python web server dengan Flask dan Docker

## Cara Menggunakan

### Menjalankan dengan Docker

1. Build Docker image:
```bash
docker build -t simple-python-http .
```

2. Run container:
```bash
docker run -p 5000:5000 simple-python-http
```

3. Buka browser dan akses: `http://localhost:5000`

### Menjalankan tanpa Docker

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run server:
```bash
python app.py
```

3. Buka browser dan akses: `http://localhost:5000`

## Struktur Project

```
simple-python-http/
├── app.py              # Flask application
├── requirements.txt    # Python dependencies
├── Dockerfile         # Docker configuration
├── templates/         # HTML templates
│   └── index.html     # Halaman utama
└── README.md          # Dokumentasi
```
