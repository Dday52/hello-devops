# hello-devops
interview
# Hello DevOps App

Simple Python Flask app demonstrating:
- Docker
- GitHub Actions CI
- Docker Compose

## Run Locally
```bash
pip install -r requirements.txt
python app.py
## Docker
docker build -t hello-devops .
docker run -p 8080:8080 hello-devops
## Docker Compose
docker-compose up --build
