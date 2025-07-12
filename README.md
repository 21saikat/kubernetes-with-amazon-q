# 🚀 Kubernetes App Deployment using Amazon Q (Natural Language Only)

## 🤖 Description
Built and deployed a full Kubernetes application using **natural language** via **Amazon Q**, without writing a single `kubectl` or YAML command.

---

## 🔧 Stack Used
- 🐧 Ubuntu
- 🤖 Amazon Q
- 📁 mcp.json
- ☸️ Kubernetes (Minikube, Docker)
- 📦 Astral UV MCP Server

---

## ⚙️ Installation & Setup

### Step 1: Install Amazon Q
```bash
sudo apt update
sudo apt install libfuse2

curl --proto '=https' --tlsv1.2 -sSf https://desktop-release.q.us-east-1.amazonaws.com/latest/amazon-q.deb -o amazon-q.deb
sudo apt install -y ./amazon-q.deb

q login



Step 2: Create mcp.json
(See this repo)

Step 3: Start MCP Server

sudo snap install astral-uv --classic
uvx kubernetes-mcp-server@latest



🧠 What I Asked Amazon Q
"Install Docker, kubectl, and Minikube"

"Check if kubectl is working"

"Create an NGINX pod in a new namespace"

"Deploy trainwithshubham/tws-online-shop-app-demo:latest with 3 replicas in a new namespace"

"Expose port 80 so I can access in browser"

✅ Output
http://localhost:8080 → NGINX

http://localhost:8081 → Online Shop App



📌 Author
Ibne Sabid Saikat
Microsoft Learn Student Ambassador | DevOps & AI | Azure Certified

Save and exit the file.

---

### 🌐 5. **Create a GitHub repository**

Go to: [https://github.com/new](https://github.com/new)

- **Repository name:** `kubernetes-with-amazon-q`
- Description: `Deploy Kubernetes app using natural language with Amazon Q`
- Keep it Public
- Don’t initialize with README

Click **"Create repository"**

---

### 🔗 6. **Initialize local Git and push to GitHub**
Back in your terminal:
```bash
git init
git add .
git commit -m "Initial commit: Added mcp.json and README"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/kubernetes-with-amazon-q.git
git push -u origin main

✅ DONE!
You can now visit:

bash
Copy
Edit
https://github.com/YOUR_USERNAME/kubernetes-with-amazon-q
To see your full project live on GitHub.
