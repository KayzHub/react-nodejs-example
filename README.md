# React + Node.js Example (Full Stack)

A simple full-stack example project with:
- **Frontend:** React app (in `my-app/`)
- **Backend:** Node.js API (in `api/`)
- **Containerization:** Docker support via the root `Dockerfile`

> Repo structure includes `api/`, `my-app/`, and a root `Dockerfile`.  
---

## Project Structure
- **api/** – Node.js backend API  
- **my-app/** – React frontend  
- **Dockerfile** – Container build instructions  
- **.dockerignore** – Docker ignore rules  
- **.gitignore** – Git ignore rules
---

## Prerequisites

- Node.js (LTS recommended)
- npm (or yarn)
- Docker (optional, for container builds/runs)

---

## Quick Start (Local Dev)

### 1) Clone

```bash
git clone https://github.com/KayzHub/react-nodejs-example.git
cd react-nodejs-example
```

---
## Run with Docker
```bash
docker build -t devjumpstart/demo-app:2.0 .
docker push devjumpstart/demo-app:2.0
docker run -d -p 3080:3080 devjumpstart/demo-app:2.0
```
