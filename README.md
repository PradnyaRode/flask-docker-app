🚀 Flask Docker App 🐳
Welcome to Flask Docker App, a minimal yet production-ready Python web application built using the lightweight Flask framework and containerized with Docker for consistent, reproducible deployments across environments. 🔥🐍

This project was developed as part of a technical assignment to demonstrate familiarity with building containerized microservices using Python and Docker. The app serves a basic "Hello, World!" response — making it a clean and functional starting point for verifying Docker setups, testing APIs, or learning container orchestration.

🧰 Features
📦 Simple Flask-based web server (app.py)

🐳 Dockerized for clean, isolated execution

⚙️ Docker Compose support for simplified service management

✅ Health check via curl http://localhost:5001

🔧 Technologies 
Used
🐍 Python 3.6.9
🌐 Flask
🐳 Docker
🧱 Docker Compose

🛠️ Setup Instructions
🔁 Clone the repository
bash
Copy code
git clone https://github.com/PradnyaRode/flask-docker-app.git
cd flask-docker-app
🐋 Build & Run using Docker
bash
Copy code
docker build -t flask-docker-app .
docker run -d -p 5001:5000 flask-docker-app
Now open your browser at 👉 http://localhost:5001

⚙️ Using Docker Compose
bash
Copy code
docker-compose up --build -d
To stop the services:

bash
Copy code
docker-compose down
