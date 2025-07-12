#  Kubernetes App Deployment using Amazon Q (Natural Language Only)

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

### 🔹 Step 1: Install Amazon Q
```bash
sudo apt update
sudo apt install libfuse2

curl --proto '=https' --tlsv1.2 -sSf https://desktop-release.q.us-east-1.amazonaws.com/latest/amazon-q.deb -o amazon-q.deb
sudo apt install -y ./amazon-q.deb

q login




🔹 Step 2: Create mcp.json
See mcp.json file in this repository.

🔹 Step 3: Start MCP Server

sudo snap install astral-uv --classic
uvx kubernetes-mcp-server@latest



🧠 What I Asked Amazon Q
"Install Docker, kubectl, and Minikube"

"Check if kubectl is working"

"Create an NGINX pod in a new namespace"

"Deploy trainwithshubham/tws-online-shop-app-demo:latest with 3 replicas in a new namespace"

"Expose port 80 so I can access in browser"


✅ Output
🌐 http://localhost:8080 → NGINX

🌐 http://localhost:8081 → Online Shop App


<img width="1400" height="741" alt="image" src="https://github.com/user-attachments/assets/1221851c-0270-4ef9-8b43-c3a26005abbb" />





👨‍💻 Author
Ibne Sabid Saikat
Microsoft Learn Student Ambassador | DevOps & AI | Azure Certified
