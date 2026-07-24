<p align="center">
  <img src="./assets/Profile-Banner.gif" alt="Profile Banner" width="100%"/>
</p>


<p align="center">
<a href="https://github.com/Aswin-Shine"><img src="https://img.shields.io/badge/GitHub-2b2b2b?style=flat-square&logo=github&logoColor=white"></a>
<a href="https://linkedin.com/in/aswinshine"><img src="https://img.shields.io/badge/LinkedIn-2b2b2b?style=flat-square&logo=linkedin&logoColor=white"></a>
</p>

---

## About Me

DevOps/MLOps engineer focused on **AWS EKS, Terraform, and GitOps delivery**, with a design-and-frontend background that shapes how I build developer- and user-facing tooling. I've taken infrastructure from bare cloud to production: Kubernetes clusters via IaC, CI/CD pipelines with security gates, and observability stacks - alongside a production RAG chatbot built on LangChain and Pinecone. Comfortable owning the stack end to end: Linux servers, Nginx/SSL, Docker, and automated pipelines.

Currently deepening my System Design and scalable-architecture skills.

---

## GitHub Stats

<p align="center">
<img src="https://github-readme-stats.shion.dev/api?username=Aswin-Shine&theme=merko&hide_border=false&include_all_commits=true&count_private=false" height="165"/>
<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=Aswin-Shine&theme=merko&hide_border=false&include_all_commits=true&count_private=false&layout=compact" height="165"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com/?user=Aswin-Shine&theme=merko&hide_border=false" width="65%"/>
</p>

---

## Featured Projects

**Penwave - Cloud-Native Blogging Platform on AWS EKS** ([repo](https://github.com/Aswin-Shine/Penwave))
Full-stack blogging platform (Next.js, Node.js/Express, PostgreSQL, Redis) deployed as a modular monolith on AWS EKS, with cluster and networking provisioned via Terraform.
- Packaged as multi-stage, multi-arch (amd64/arm64) Docker builds deployed via Helm across frontend, backend, and ingress in a GitOps workflow with ArgoCD, with HPA (2-6 replicas) and Prometheus/Grafana/Loki for monitoring and centralized logging.
- Hardened with Argon2id password hashing, JWT refresh-token rotation, Redis-backed rate limiting, Zod-validated inputs, and Trivy image scanning in CI/CD, fronted by Nginx with Let's Encrypt TLS termination.

**Formula 1 RAG Chatbot - Production AI Q&A System** ([repo](https://github.com/Aswin-Shine/Formula-1-Chatbot))
Conversational RAG system over historical F1 data (races, drivers, results, standings) and technical PDFs, with real-time web-search fallback.
- Hybrid retrieval: Pinecone vector search (k=3, cosine, 384-dim HuggingFace embeddings) with a context-sufficiency threshold that falls back to SerpAPI web search when local context is thin, orchestrated via LangChain's `RunnableWithMessageHistory` for multi-turn conversational memory.
- Shipped via a 3-stage GitHub Actions pipeline (integration → delivery → deployment) to Docker Hub, deployed on a self-hosted AWS EC2 runner serving GPT-4.1-mini responses through a Flask API.

**YouTube Sentiment Insight - MLOps Pipeline & Chrome Extension** ([repo](https://github.com/Aswin-Shine/Youtube-Sentiment-Insight))
End-to-end MLOps system for YouTube comment sentiment classification, from DVC-orchestrated training to a production Chrome extension.
- Built a 5-stage DVC pipeline (ingestion → preprocessing → model building → evaluation → registration) training a LightGBM classifier on TF-IDF features, tracked via MLflow with S3 as the remote/artifact store, reaching 85.3% accuracy / 84.9% F1 on the test set.
- Automated a 3-stage GitHub Actions pipeline (CI → Docker build/push to Docker Hub → CD to AWS EC2 via self-hosted runner) serving predictions through a Flask REST API, consumed by a Chrome extension for real-time comment scraping, sentiment visualization, and trend analysis.

---

## Tech Stack

**Cloud, Infrastructure & Containers**

<p align="left">
<img src="https://skillicons.dev/icons?i=aws,terraform,ansible,docker,kubernetes,githubactions,jenkins,nginx,linux,bash" />
</p>

**Backend, Databases & Frontend**

<p align="left">
<img src="https://skillicons.dev/icons?i=nodejs,express,python,postgres,mysql,redis,react,nextjs,ts,figma" />
</p>

**Not yet on skillicons.dev** - ArgoCD, Helm, Prometheus, Grafana, Loki, SonarQube, Trivy, LangChain, Pinecone, HuggingFace, MLflow, OCI:

<p align="left">
<img src="https://img.shields.io/badge/ArgoCD-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/Helm-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/Prometheus-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/Grafana-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/Loki-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/SonarQube-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/Trivy-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/LangChain-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/Pinecone-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/HuggingFace-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/MLflow-2b2b2b?style=flat-square" />
<img src="https://img.shields.io/badge/OCI-2b2b2b?style=flat-square" />
</p>

---

## Certifications

- Oracle Cloud Infrastructure 2025 Certified Foundations Associate - Oracle
- Introduction to Containers, Kubernetes, and OpenShift (CC0201EN) - IBM / Cognitive Class
- MlOps Zero to Hero - Udemy
- Ethical Hacking from Scratch - Udemy
- Introduction to Industry 4.0 and Industrial Internet of Things - NPTEL / Swayam
- Introduction to Professional Scientific Communication - NPTEL / Swayam

---

## Let's Connect

<p align="left">
<a href="https://linkedin.com/in/aswinshine"><img src="https://img.shields.io/badge/LinkedIn-2b2b2b?style=flat-square&logo=linkedin&logoColor=white"></a>
<a href="mailto:ashwinsh.91@gmail.com"><img src="https://img.shields.io/badge/Email-2b2b2b?style=flat-square&logo=gmail&logoColor=white"></a>
</p>