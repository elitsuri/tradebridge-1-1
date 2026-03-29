# TradeBridge 1

> Desktop trading dashboard with real-time feeds and order execution

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C++, Qt, SQLite, CMake

## 🏗️ Architecture
Backend service with C++, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/tradebridge-1
cd tradebridge-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
