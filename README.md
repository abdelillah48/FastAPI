# API Factures FastAPI

API simple pour gérer clients et factures.

## Installation

### Docker
```bash
docker build -t invoice-api .
docker run -p 8000:80 invoice-api
```

### Local
```bash
pip install fastapi uvicorn
uvicorn app.main:app --reload
```

## Documentation
- Swagger: http://localhost:8000/docs
