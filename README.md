# Backend API (FastAPI)

A clean and minimal backend service designed to demonstrate good engineering practices,
including clear project structure, maintainable endpoints, and production-friendly patterns.

This repository shows how I approach:
- **API architecture** and modular design  
- **Separation of concerns** through clear folder layout  
- **Scalability awareness**, enabling easy extension into a larger service  
- **Fast iteration and reliability**, using lightweight modern frameworks such as FastAPI  
- **Developer onboarding**, with simple commands and minimal setup friction  

## Highlights
- Implements foundational endpoints (`/health`, `/greet/{name}`) to show structure without unnecessary complexity.
- Organized to support additional layers like services, repositories, and dependency injection.
- Simple enough for demonstration, but structured according to real-world engineering expectations.
- Easy to containerize and integrate into CI/CD pipelines.

## Endpoints
- `GET /health` -- Service health check
- `GET /greet/{name}` -- Example parameterized route

## Run locally
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
