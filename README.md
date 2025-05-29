# To use **Ansible** on **WSL2** to automate the deployment of a **Dockerized Ubuntu image** (with Docker Compose) and execute **bash scripts**

---

## ✅ Prerequisites

1. **WSL2 installed with Ubuntu (e.g., Ubuntu 22.04)**

2. **Docker Desktop installed (with WSL2 integration)**

3. **Ansible installed in WSL2**

   ```bash
   sudo apt update
   sudo apt install ansible -y
   ```

4. **Docker & Docker Compose available inside WSL2**
   Docker Desktop handles the Docker engine, and WSL2 can communicate with it via the Docker CLI.

   Test with:

   ```bash
   docker version
   docker compose version
   ```
