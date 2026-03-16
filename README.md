# Demo DevOps Project

A simple demo project to test the complete DevOps workflow.

## Features

- Simple Python Flask API
- GitHub Actions CI/CD
- Docker support

## Quick Start

```bash
# Local run
pip install flask
python app.py

# Docker
docker build -t demo-devops .
docker run -p 5000:5000 demo-devops
```

## API Endpoints

- `GET /` - Health check
- `GET /health` - Health check (JSON)