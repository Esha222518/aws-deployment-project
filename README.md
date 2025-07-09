AWS Flask Deployment Project ☁

A lightweight Flask app containerized using Docker and deployed on AWS EC2.

##  Features
- Simple Flask backend
- Dockerized setup with Dockerfile
- Deployed to AWS EC2 (Ubuntu server)
- Can be tested locally or on cloud

##  Tech Stack
- **Language:** Python (Flask)
- **DevOps:** Docker, AWS EC2
- **Tools:** Git, GitHub, Ubuntu CLI

## Folder Structure
aws-deployment-project/
├── app.py
├── Dockerfile
└── README.md



##  How to Run Locally

```bash
# 1. Install Flask (if not using Docker)
pip install flask

# 2. Run App
python app.py

# App runs on http://127.0.0.1:80 or localhost
 Run with Docker
# 1. Build Docker Image
docker build -t flask-app .
# 2. Run the Container
docker run -p 80:80 flask-app


