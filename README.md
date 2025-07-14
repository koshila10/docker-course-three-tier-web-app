# 🐳 3-Tier Docker Web App

A simple 3-tier application using **Flask (backend)**, **Nginx static frontend**, and **MySQL** — containerized with Docker and orchestrated with Docker Compose. DevOps practices like CI/CD and GitHub Actions are applied.

---

## 📊 Architecture Diagram

```plaintext
+-------------+        +--------------+        +-------------+
|  Frontend   | <----> |   Backend    | <----> |   MySQL     |
|  (Nginx)    |        |  (Flask API) |        |  Database   |
+-------------+        +--------------+        +-------------+
      |                       |                       |
  Port 3000              Port 5000               Port 3306


## 🚀 How to Run the App

```bash
git clone https://github.com/YOUR-USERNAME/docker-course-three-tier-web-app.git
cd docker-course-three-tier-web-app
docker-compose up --build
## 📸 Screenshots

| Feature        | Screenshot |
|----------------|------------|
| Frontend UI    | `frontend.png` |
| Backend API    | `backend.png` |
| Docker Running | `docker.png` |
| Final README   | `readme.png` |

