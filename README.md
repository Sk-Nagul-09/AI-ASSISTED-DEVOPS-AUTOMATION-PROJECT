# 🤖🐳 AI-Assisted DevOps Automation
## ⚡ GenAI Powered Dockerfile Generator

🚀 Automate Dockerfile creation using Generative AI.

This project generates **production-ready Dockerfiles** based on the programming language provided by the user.

Instead of writing Dockerfiles manually, this tool creates optimized and standardized configurations in seconds.

---

## 📌 Project Overview

In real DevOps workflows, writing Dockerfiles is repetitive and error-prone.

This tool uses a locally running Large Language Model via **Ollama** and the **Llama 3** model to automatically generate Dockerfiles following best practices.

✅ Faster containerization  
✅ Standardized configurations  
✅ Reduced manual effort  
✅ Improved productivity  

---

## 🎯 Features

✨ Generate Dockerfiles instantly  
✨ Supports multiple programming languages  
✨ Uses container best practices  
✨ Runs locally (no cloud API required)  
✨ Keeps source code private & secure  

---

## 🛠 Tech Stack

| 🔧 Technology | 🚀 Purpose |
|--------------|-----------|
| 🐍 Python | Application logic |
| 🤖 Generative AI | Dockerfile generation |
| 🧠 Ollama | Local LLM runtime |
| 🐳 Docker | Containerization |
| ⚙ Prompt Engineering | Controlled output |

---

## ⚙️ Prerequisites

### 1️⃣ Install Ollama

#### Linux
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### Start Ollama:
```bash
ollama serve
```

### Pull model:
```bash
ollama pull llama3.2:1b
```

### 2️⃣ Start Ollama Service
```
ollama serve
```

### 3️⃣ Pull Llama Model
```
ollama pull llama3.1:8b
```

### 🚀 Project Setup

1️⃣ Clone Repository
```
git clone https://github.com/Sk-Nagul-09/AI-ASSISTED-DEVOPS-AUTOMATION-PROJECT.git
cd ai-dockerfile-generator
```

### 2️⃣ Create Virtual Environment
```
python3 -m venv venv
source venv/bin/activate
```

### 3️⃣ Install Dependencies
```
pip install -r requirements.txt
```

### ▶️ Run the Application
```
python3 generate_dockerfile.py
```

### 💬 Example Input
```
Enter the programming language: python
```

| Step | Description                                 |
| ---- | ------------------------------------------- |
| 1️⃣  | User enters programming language            |
| 2️⃣  | Script sends structured prompt to local LLM |
| 3️⃣  | LLM generates optimized Dockerfile          |
| 4️⃣  | Dockerfile is displayed instantly           |


### 🐳 Example Output
```
FROM amazonlinux:latest
RUN yum update -y
RUN yum install -y python3 python3-pip
RUN pip3 install flask
WORKDIR /opt/python_webapp
COPY app.py .
CMD FLASK_APP=app.py flask run --host=0.0.0.0 --port=8082
EXPOSE 8082
```

🔐 Why Run AI Locally?
---

✔ Keeps source code private

✔ Eliminates API costs

✔ Works without external AI services

✔ Suitable for enterprise security policies


### 🔮 Future Enhancements
---

🚀 Generate Kubernetes manifests

🚀 Create CI/CD pipeline templates

🚀 Auto-generate shell scripts

🚀 Framework detection & dependency handling

🚀 Multi-stage & optimized production builds


### 🎯 Learning Outcomes
---

✅ DevOps automation using AI

✅ Prompt engineering fundamentals

✅ Docker containerization best practices

✅ Local LLM integration

✅ Secure AI usage in DevOps workflows

