<div align="center">
  ![Profile Banner](./assets/Profile-Banner.gif) 
</div>


<p align="center">
<a href="https://github.com/Aswin-Shine"><img src="https://img.shields.io/badge/GitHub-Aswin--Shine-181717?style=flat&logo=github"></a>
<a href="https://linkedin.com/in/aswinshine"><img src="https://img.shields.io/badge/LinkedIn-aswinshine-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
</p>

---

### 🧭 About Me

DevOps/MLOps engineer focused on **AWS EKS, Terraform, and GitOps delivery**, with a design-and-frontend background that shapes how I build developer- and user-facing tooling. I've taken infrastructure from bare cloud to production: Kubernetes clusters via IaC, CI/CD pipelines with security gates, and observability stacks — alongside a production RAG chatbot built on LangChain and Pinecone. Comfortable owning the stack end to end: Linux servers, Nginx/SSL, Docker, and automated pipelines.

Currently deepening my System Design and scalable-architecture skills.

---

### 📊 GitHub Stats:

<p align="center">
<img src="https://github-readme-stats.shion.dev/api?username=Aswin-Shine&theme=merko&hide_border=false&include_all_commits=true&count_private=false" height="165"/>
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Aswin-Shine&theme=merko&hide_border=false&include_all_commits=true&count_private=false&layout=compact" height="165"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com/?user=Aswin-Shine&theme=merko&hide_border=false" width="65%"/>
</p>

---

### 💼 Experience

**Frontend Developer Intern — RAD Techno Services** | *Jul 2024 – Jul 2025 | Jaipur, Rajasthan*
- Wireframed and prototyped user flows in Figma/Adobe XD, then implemented them as reusable React components with a shared design-token system.
- Refactored the front-end into a component-based, modular architecture — cutting duplicated code by 15% and speeding up subsequent feature development by 20%.
- Tuned Webpack/Vite build configs (code-splitting, lazy-loaded routes, tree-shaking), cutting bundled application size by 25% and improving load times.

**UI/UX Designer Intern — MQDC**
- Summer internship focused on user research, wireframing, and interface design.

---

### 🚀 Featured Projects

**🔹 Penwave — Cloud-Native Blogging Platform on AWS EKS**
Full-stack blogging platform (Next.js, Node.js/Express, PostgreSQL, Redis) deployed as a modular monolith on AWS EKS, with cluster and networking provisioned via Terraform.
- Multi-stage, multi-arch (amd64/arm64) Docker builds deployed via Helm across frontend, backend, and ingress — managed through a GitOps workflow with ArgoCD.
- Horizontal Pod Autoscaling (2–6 replicas, CPU/memory-based) with Prometheus, Grafana, Loki, and Promtail for metrics, dashboards, and centralized logging.
- Hardened with Argon2id password hashing, JWT refresh-token rotation, Redis-backed rate limiting, Zod-validated inputs, and Trivy image scanning in CI/CD.
- Nginx reverse proxy in front of all services with HTTP→HTTPS redirect, Let's Encrypt SSL/TLS, and endpoint-level rate limiting.

**🔹 Formula 1 RAG Chatbot — Production AI Q&A System**
Python (Flask, LangChain) RAG chatbot: Pinecone vector search (k=3, cosine) + OpenAI GPT-4.1-mini, with SerpAPI web-search fallback and HuggingFace sentence-transformer embeddings (384-dim) over mixed PDF/CSV sources.
- Shipped via a 3-stage GitHub Actions pipeline (integration → delivery → deployment) to Docker Hub, deployed on a self-hosted AWS EC2 runner over SSH with security-group-managed ports.

**🔹 YouTube Sentiment Analyser — Chrome Extension**
Browser extension that scrapes YouTube video comments and runs sentiment analysis pipelines for real-time audience insights.

---

### 🛠️ Tech Stack

**Cloud & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![OCI](https://img.shields.io/badge/OCI-F80000?style=flat&logo=oracle&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)

**Containers & GitOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)

**CI/CD & Security**
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat)

**Observability**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-black?style=flat)

**Backend & Databases**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Frontend & Design**
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-black?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

**GenAI / MLOps**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

---

### 📚 Continuous Learning

- **100 Days of DevOps** (KodeKloud)
- Linux, Kubernetes, Terraform — Level 1–3/4 completed (KodeKloud)
- **Ethical Hacking from Scratch** — Udemy
- Currently studying **System Design**: high-level & low-level architecture, scalability, microservices, distributed systems

---

### 📜 Certifications

- Oracle Cloud Infrastructure 2025 Certified Foundations Associate — Oracle
- Introduction to Containers, Kubernetes, and OpenShift (CC0201EN) — IBM / Cognitive Class
- Docker Essentials: A Developer Introduction (CO0101EN) — IBM / Cognitive Class
- Cybersecurity Analyst Job Simulation — TCS (Forage)
- Ethical Hacking from Scratch — Udemy
- Introduction to Industry 4.0 and Industrial Internet of Things — NPTEL / Swayam
- Introduction to Professional Scientific Communication — NPTEL / Swayam

---

### 📫 Let's Connect

<p align="left">
<a href="https://linkedin.com/in/aswinshine"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white"></a>
<a href="mailto:ashwinsh.91@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat&logo=gmail&logoColor=white"></a>
</p>