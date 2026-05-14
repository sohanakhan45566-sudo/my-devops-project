# DevOps Project - CI/CD Pipeline with Docker & Kubernetes

## 🛠️ Technologies
- Python Flask
- Docker
- GitHub Actions  
- Kubernetes (Minikube)

## 📋 Features
- Automated CI/CD pipeline
- Docker containerization
- Kubernetes deployment with 2 replicas
- Health check endpoint

## 🔧 How to Run

### Local Setup
\`\`\`bash
python app.py
\`\`\`

### Docker
\`\`\`bash
docker build -t my-project .
docker run -d -p 5000:5000 my-project
\`\`\`

### Kubernetes
\`\`\`bash
kubectl apply -f deployment.yaml
minikube service my-app-service
\`\`\`

## 📊 CI/CD Pipeline
GitHub Actions automatically builds and tests on every push.

## 👨‍💻 Author
Sohana Akbar - DevOps Engineer

## 📧 Contact
[https://www.linkedin.com/in/sohana-akbar-5b6b1337b/] | [https://github.com/sohanakhan45566-sudo] | [sohanajhan45566@gmail.com]
