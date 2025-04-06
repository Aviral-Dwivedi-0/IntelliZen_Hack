# AI Model Benchmarking Tool

A web-based tool for benchmarking AI models, providing insights on accuracy, inference time, and memory usage.

## Features

- Support for multiple model formats (.pt, .h5, .onnx)
- Real-time benchmarking metrics
- Visual performance comparisons
- Downloadable PDF reports
- Docker-based deployment

## Project Structure

```
ai-model-benchmark/
├── backend/               # FastAPI backend
├── frontend/             # React frontend
├── docker/               # Docker configuration
└── scripts/              # Utility scripts
```

## Getting Started

1. Clone the repository
2. Install Docker and Docker Compose
3. Run `docker-compose up --build`
4. Access the application at http://localhost:3000

## Development

- Backend runs on port 8000
- Frontend runs on port 3000
- API documentation available at http://localhost:8000/docs
