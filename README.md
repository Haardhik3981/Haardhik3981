# 👋 Hi, I'm Haardhik Mudagere Anil  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/haardhik-m-a-2075661a5/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/Haardhik3981)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:haardhiknbd@gmail.com)

### Cloud • Distributed Systems • HPC • CUDA • AI/ML Systems • LLM • Real-Time Streaming • Full-Stack Engineering 

<!-- ![Visitors](https://visitor-badge.laobi.icu/badge?page_id=Haardhik3981) -->

---

## 👉 About Me

I'm a Master's student in Computer Science at **UC Santa Cruz** and a former **Systems/Software Engineer at Hewlett Packard Enterprise (HPE)**.  

I enjoy understanding how complex systems work end-to-end and building software that is fast, scalable, and reliable.

My background spans **HPC, distributed systems, cloud-native architectures, and real-time applications**. I’ve worked across the stack - from **C++ and CUDA** for performance-critical workloads to **AWS, Node.js, React, and modern CI/CD pipelines** for production deployments.

I’m also deeply interested in AI systems engineering. I’ve built **custom tokenizers**, trained **compact generative models in PyTorch**, and deployed **LLM inference pipelines** that integrate with cloud services and modern serverless architectures.

I build real-world applications that blend performance, design, and engineering depth.


---

## 👉 Projects

---
### 🔹 CounselGPT — GPU-Optimized LLM Inference Platform
**Fine-tuning + Hybrid RAG + CUDA Optimization**
[➡️ GitHub Repository](https://github.com/Mati02K/CounselGPT)

**Tech Stack:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-4285F4?logo=google-cloud&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)

* **Model Engineering:** Fine-tuned **Qwen-7B (8-bit)** using **LoRA** on specialized legal datasets.
* **Inference Optimization:** Served models via GPU-optimized **llama.cpp** in custom **CUDA Docker images** on L4/L40 GPUs, supporting 4-bit and 8-bit quantization.
* **Retrieval & Caching:** Built a **Hybrid RAG** system (BM25 + semantic embeddings) and achieved a **20x reduction** in repeated-query latency using **Redis semantic caching**.
* **Observability:** Monitored RPS, GPU utilization, and memory metrics with an integrated **Prometheus/Grafana** pipeline.

---

### 🔹 Social Network Kubernetes Platform
**Microservices + Infrastructure as Code + Observability**
[➡️ GitHub Repository](https://github.com/Haardhik3981/deathstarbench-socialnetwork)

**Tech Stack:** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1628?logo=helm&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)

* **Orchestration:** Engineered a modular platform of **11+ microservices** using **Helm** with service-specific overrides.
* **Autoscaling:** Implemented **HPA**, maintaining a consistent **100ms latency** under a load of 2,000+ concurrent users.
* **Data Persistence:** Automated the scaling and deployment of sharded **MongoDB**, **Redis clusters**, and **Memcached** via Python/Bash Helm hooks.
* **Benchmarking:** Verified system reliability with **k6 tests**, achieving a **99.9% success rate** across 1.5M+ requests.

---

### 🔹 Cloud-Native ChatBot + Generative LLM  
**LLM inference + Serverless AWS + Full-stack deployment**  
[➡️ GitHub Repository](https://github.com/Haardhik3981/Cloud-Chatbot-SaaS)

**Tech Stack:**  
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F00?logo=amazonapiGateway&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?logo=amazon-dynamodb&logoColor=white)
![Cognito](https://img.shields.io/badge/Cognito-DD344C?logo=amazoncognito&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?logo=amazons3&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-FF4F00?logo=amazonaws&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![SentencePiece](https://img.shields.io/badge/SentencePiece-008000?logo=google&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

**Highlights:**  
- Built multi-tenant chat APIs using **Lambda + API Gateway**, secured with **Cognito**  
- Designed complete serverless backend with **DynamoDB session memory**  
- Trained a **custom PyTorch generative model** with an **8K SentencePiece tokenizer**  
- Deployed hybrid inference (**custom LLM + GPT-4o fallback**) on Dockerized FastAPI  
- CI/CD pipeline using GitHub Actions and deployed frontend via **CloudFront**  

---

### 🔹 Scalable Live Streaming Platform  
**Nginx-RTMP + Kafka + Redis + Node.js distributed backend**  
[➡️ GitHub Repository](https://github.com/Haardhik3981/Scalable-Live-Streaming-System)

**Tech Stack:**  
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx_RTMP-009639?logo=nginx&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![ZooKeeper](https://img.shields.io/badge/ZooKeeper-000000?logo=apache&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-000000?logo=socket.io&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_CDN-F38020?logo=cloudflare&logoColor=white)

**Highlights:**  
- Implemented low-latency HLS streaming using **Nginx-RTMP**  
- Built distributed services using **Node.js**, backed by **Redis** for real-time metrics  
- Used **Kafka** for event streaming and analytics  
- Horizontally scaled backend using **Nginx Load Balancer**  
- CDN optimization using **Cloudflare Pages + Cloudflare CDN**  

---

### 🔹 High-Performance Image Processing Library  
**C++ + CUDA + OpenMP + pybind11 accelerated image filters**  
[➡️ GitHub Repository](https://github.com/Haardhik3981/OpenMP-CUDA-Accelerated-High-Performance-Image-Processing-Library)

**Tech Stack:**  
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white)
![OpenMP](https://img.shields.io/badge/OpenMP-659AD2?logo=openmp&logoColor=white)
![SIMD](https://img.shields.io/badge/SIMD-000000?logo=amd&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![pybind11](https://img.shields.io/badge/pybind11-000000?logo=python&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

**Highlights:**  
- Built modular **C++ image processing library** with CUDA acceleration  
- Added GPU-accelerated filters for real-time performance  
- Used **OpenMP + SIMD** for CPU parallelism; achieved ~50% faster runtime  
- Exposed functions to Python using **pybind11** for ML/CV pipelines

## 👉 Skills

- **Distributed Systems:** Concurrency, load balancing, event-driven architectures, real-time streaming  
- **System Design:** Microservices, messaging systems, API design, scalable backend patterns  
- **Databases:** MySQL, DynamoDB modeling, MongoDB schema design, Redis caching  
- **DevOps & Infra:** CI/CD pipelines, containerization, cloud networking, IaC principles  
- **GPU & HPC:** Parallel programming concepts, memory hierarchies, GPU kernels, performance tuning  
- **AI Systems:** Tokenizers, model training, inference optimization, embeddings, cloud-scale LLM integration

## 👉 Resume

[![Resume](https://img.shields.io/badge/Resume-Download-blue?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://drive.google.com/file/d/1zNxKjWOiYCHkx9LEdvFN_j4jhmAUtg77/view?usp=sharing)

---

## 👉 Contact Me
If you'd like to collaborate, discuss systems/AI work, or explore opportunities, feel free to reach out.

📧 Email: haardhiknbd@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/haardhik-m-a-2075661a5/  
🐙 GitHub: https://github.com/Haardhik3981




