# Installation & Setup Guide for Essential Tools

## Essential Tools
```bash
1. Git – Version control.
2. VS Code – Code editor.
3. Docker Desktop – Containerization (integrates with WSL2).
4. Node.js LTS – For frontend and some backend tools.
5. Go – Backend language.
6. Azure CLI (optional: also install AWS CLI or gcloud CLI).
7. kubectl – Kubernetes CLI.
8. Postman – API testing.
```
This guide covers the installation, setup, and verification of key development tools.

---

## 1. Git (Version Control)

- **Install:**  
  Download from [https://git-scm.com/downloads](https://git-scm.com/downloads) and follow platform instructions.

- **Verify:**  
```bash
  git --version
```

## 2. Visual Studio Code (Code Editor)
**Install:**
Download from **https://code.visualstudio.com/** and **install.**

**Verify:**
Open VS Code and check the version under **Help > About.**

## 3. Docker Desktop (Containerization + WSL2 Integration)
**Install:**
Download from **https://www.docker.com/products/docker-desktop.** Ensure WSL2 is enabled on Windows.

**Verify:**
```bash
docker --version
docker info
```

## 4. Node.js LTS (Frontend & Backend Runtime)
**Install:**
Download LTS version from **https://nodejs.org/en/**.

**Verify:**
```bash
node --version
npm --version
```

## 5. Go (Backend Language)
**Install:**
Download from **https://golang.org/dl/** and install.

**Verify:**
```bash
go version
```

## 6. Azure CLI (Cloud Command-Line Interface)
**Install:**
Follow instructions at **https://learn.microsoft.com/en-us/cli/azure/install-azure-cli.**

**Verify:**
```bash
az version
```

**Optional:**
```bash
Install AWS CLI (https://aws.amazon.com/cli/) or Google Cloud SDK (https://cloud.google.com/sdk/docs/install).
```

## 7. kubectl (Kubernetes CLI)
**Install:**
Follow **https://kubernetes.io/docs/tasks/tools/**.

**Verify:**
```bash
kubectl version --client
```

## 8. Postman (API Testing)
**Install:**
Download from **https://www.postman.com/downloads/**.

**Verify:**
Launch Postman and confirm it opens successfully.

**Notes**
Restart your terminal or system after installations for environment variables to update.

For WSL2 integration with Docker and other tools, ensure WSL2 is properly installed and set as default backend on Windows.

## Happy coding! 🚀

If you want, I can also make a version with quick install commands for Linux/macOS or Windows PowerShell. Let me know!
