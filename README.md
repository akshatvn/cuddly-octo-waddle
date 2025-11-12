# FastAPI Ping Application

A simple FastAPI application with a `/ping` endpoint.

## Installation

```bash
pip install -r requirements.txt
```

## Usage

Run the application:

```bash
python main.py
```

Or using uvicorn directly:

```bash
uvicorn main:app --reload
```

The server will start on `http://localhost:8000`

## Testing the Endpoint

Visit the `/ping` endpoint:

```bash
curl http://localhost:8000/ping
```

Response:
```json
{"data": "pong"}
```

## Interactive API Documentation

FastAPI automatically generates interactive API documentation:

- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc
