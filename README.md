# 👋 Hi, I'm Mohsin Ali

### Full-Stack AI Engineer

<p align="left">
  <a href="https://ai-powered-workspace.vercel.app">
    <img src="https://img.shields.io/badge/🚀_Live_Project-AI_Knowledge_Platform-111827?style=for-the-badge" alt="Live Project" />
  </a>
  <a href="https://github.com/MohsinAli-2000">
    <img src="https://img.shields.io/badge/GitHub-MohsinAli--2000-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/mohsinali77">
    <img src="https://img.shields.io/badge/LinkedIn-Mohsin_Ali-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

I'm a **Full-Stack AI Engineer** focused on building **production-ready AI applications and scalable backend systems**.

My engineering focus sits at the intersection of:

**Full-Stack Development → Backend Engineering → System Design → Cloud & DevOps → AI/LLM Engineering → Production AI Systems**

I enjoy building systems end-to-end — from product requirements and database architecture to APIs, AI pipelines, access control, containerization, CI/CD, cloud deployment, and production operations.

> **My goal:** Build reliable software systems that combine strong engineering fundamentals with practical, secure, and useful AI capabilities.

---

## 🚀 Featured Project

### 🧠 AI Knowledge Platform

**A production-deployed multi-tenant AI knowledge platform that turns organizational documents into searchable, grounded knowledge.**

<a href="https://ai-powered-workspace.vercel.app">
  <img src="https://img.shields.io/badge/🌐_Open_Live_Application-Visit_Project-2563EB?style=for-the-badge" alt="Open Live Application" />
</a>

The platform allows organizations to:

- 🏢 Create isolated multi-tenant workspaces
- 👥 Manage members, roles, projects, and groups
- 📄 Upload and process organizational documents
- 🖼️ Process images and visual documents with multimodal AI
- ⚙️ Process large document workloads asynchronously
- 🔎 Perform semantic/vector retrieval with `pgvector`
- 🤖 Ask grounded questions using Retrieval-Augmented Generation
- 🔐 Enforce organization, project, group, role, user, and document-level access control
- 📚 Return source citations with AI answers
- 💬 Stream AI responses using Server-Sent Events
- 📝 Maintain conversations and audit logs
- ☁️ Run the application in a production cloud environment

### Production Architecture

```text
                         👤 User
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Next.js + React      │
                 │ TypeScript + Tailwind│
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Node.js + Express   │
                 │ REST API + Security │
                 └──────┬────────┬─────┘
                        │        │
              ┌─────────┘        └──────────┐
              ▼                             ▼
      ┌───────────────┐             ┌──────────────┐
      │ PostgreSQL    │             │ Object       │
      │ + pgvector    │             │ Storage / S3 │
      └───────┬───────┘             └──────────────┘
              │
              │
      ┌───────▼───────┐
      │   RabbitMQ    │
      │ Background    │
      │ Jobs          │
      └───────┬───────┘
              │
              ▼
      ┌─────────────────────┐
      │ Python + FastAPI    │
      │ AI Service / Worker │
      └──────────┬──────────┘
                 │
        ┌────────┴─────────┐
        ▼                  ▼
 ┌──────────────┐   ┌───────────────┐
 │ Embeddings   │   │ Gemini / LLM   │
 │ + Retrieval  │   │ + Vision      │
 └──────────────┘   └───────────────┘
```

### What this project demonstrates

`Multi-Tenancy` · `RBAC` · `Document Processing` · `Async Workers` · `RAG` · `Vector Search` · `Multimodal AI` · `SSE Streaming` · `PostgreSQL` · `pgvector` · `RabbitMQ` · `Object Storage` · `Security` · `Audit Logging` · `Docker` · `CI/CD` · `Cloud Deployment`

---

# 💻 Technical Skills

## 🌐 Frontend Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,tailwind&perline=7" alt="Frontend technologies" />
</p>

**Technologies:** HTML5 · CSS3 · JavaScript · TypeScript · React · Next.js · Tailwind CSS

**Also used:** Shadcn/ui · Zustand · React Query · App Router · SSE-based streaming · Responsive UI

---

## ⚙️ Backend Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,ts,python,fastapi&perline=5" alt="Backend technologies" />
</p>

**Technologies:** Node.js · Express.js · TypeScript · Python · FastAPI

**Engineering:** REST APIs · Modular architecture · Authentication · Authorization · RBAC · JWT · API validation · Rate limiting · Background jobs · SSE · Service boundaries

---

## 🤖 AI & LLM Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=python&perline=1" alt="Python" />
</p>

![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented_Generation-7C3AED?style=for-the-badge)
![pgvector](https://img.shields.io/badge/pgvector-Vector_Search-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Focus:**

`LLMs` · `RAG` · `Embeddings` · `Vector Search` · `Semantic Retrieval` · `Prompt Engineering` · `Multimodal AI` · `Vision/OCR` · `AI Provider Abstraction` · `Grounded Generation` · `Citation/Provenance`

### RAG Pipeline

```text
Document
   ↓
Extraction / Vision
   ↓
Normalization
   ↓
Chunking
   ↓
Embeddings
   ↓
PostgreSQL + pgvector
   ↓
User Query
   ↓
Similarity Search
   ↓
Access-Controlled Retrieval
   ↓
Context Building
   ↓
LLM
   ↓
Grounded Answer + Sources
```

---

## 🗄️ Databases & Data Engineering

<p align="left">
  <img src="https://skillicons.dev/icons?i=postgresql,mongodb&perline=2" alt="Database technologies" />
</p>

![pgvector](https://img.shields.io/badge/pgvector-Vector_Extension-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Technologies & Concepts:**

`PostgreSQL` · `pgvector` · `MongoDB` · `Relational Modeling` · `ERDs` · `Constraints` · `Indexes` · `Foreign Keys` · `Transactions` · `Connection Pooling` · `Vector Embeddings` · `HNSW` · `Data Isolation`

---

## 📨 Distributed Processing & Async Systems

<p align="left">
  <img src="https://skillicons.dev/icons?i=rabbitmq&perline=1" alt="RabbitMQ" />
</p>

**Technologies & Concepts:**

`RabbitMQ` · `Background Workers` · `Dead Letter Queues` · `Retries` · `Async Processing` · `Producer/Consumer Architecture` · `Job Acknowledgement`

---

## ☁️ Cloud, DevOps & Infrastructure

<p align="left">
  <img src="https://skillicons.dev/icons?i=aws,docker,linux,nginx,githubactions,terraform,ansible,vercel&perline=8" alt="Cloud and DevOps technologies" />
</p>

**Technologies:** AWS · Docker · Docker Compose · Linux · Nginx/Caddy · GitHub Actions · Vercel · Terraform · Ansible

**Engineering:** Cloud deployment · Containerization · Environment configuration · CI/CD · Infrastructure as Code · Reverse proxies · HTTPS · Production deployment

---

## 🛠️ Engineering Tools & Practices

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,postman&perline=4" alt="Development tools" />
</p>

![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/Shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

**Practices:**

`Git` · `GitHub` · `API Testing` · `Code Reviews` · `Modular Architecture` · `Environment Management` · `Error Handling` · `Logging` · `Monitoring` · `Observability`

---

# 🏗️ Engineering Capabilities

### 🔐 Security & Access Control

- Multi-tenant data isolation
- Authentication and JWT token rotation
- Role-Based Access Control
- Project-level permissions
- Group-based permissions
- User-level document access
- `ALLOW / DENY` rules with deny precedence
- Backend-enforced authorization
- Rate limiting
- Audit logging
- Secure secret management practices

### 🧩 System Design

- Modular monolithic backend architecture
- Service-oriented AI layer
- Asynchronous processing
- Producer/consumer systems
- Object storage architecture
- Vector retrieval architecture
- Database-driven authorization
- API/service boundaries
- Production deployment architecture
- Separation of application, data, AI, and infrastructure concerns

### 🤖 Production AI

I focus on AI systems that are more than simple API integrations:

- Grounded RAG
- Secure retrieval
- Embedding pipelines
- Vector databases/search
- Multimodal document processing
- AI provider abstraction
- Streaming AI responses
- Source attribution
- Hallucination-aware system design
- Local-to-cloud model switching

---

# 📊 My Engineering Approach

I think about software as a complete lifecycle:

```text
                Product Requirements
                        ↓
                   Architecture
                        ↓
                 Database Design
                        ↓
                 Backend Systems
                        ↓
                  AI Integration
                        ↓
                Security & Access
                        ↓
              Containers & Cloud
                        ↓
                 CI/CD Deployment
                        ↓
              Monitoring & Reliability
                        ↓
                    Scaling
```

I don't aim to learn technologies simply for the sake of collecting them.

> **I aim to understand the problem, choose the right technology, understand its trade-offs, and build a reliable system around it.**

---

# 🎯 Current Direction

I'm building toward becoming a **production-focused Full-Stack AI Engineer** capable of independently designing and shipping AI-powered systems.

```text
Full-Stack Development
        ↓
Backend Engineering
        ↓
Database & System Design
        ↓
Cloud & DevOps
        ↓
LLM / RAG Engineering
        ↓
Production AI Systems
```

My strongest area of interest is the intersection of **backend engineering + AI + cloud infrastructure**.

---

# 📚 Currently Deepening

### AI Engineering
`LLMs` · `RAG` · `Agents` · `Embeddings` · `Vector Search` · `Multimodal AI` · `AI Architecture`

### Backend Engineering
`Node.js` · `TypeScript` · `Python` · `FastAPI` · `REST APIs` · `Async Systems` · `Distributed Systems`

### Data & Systems
`PostgreSQL` · `pgvector` · `Data Modeling` · `System Design` · `Caching` · `Scalability`

### Cloud & Infrastructure
`AWS` · `Docker` · `CI/CD` · `Infrastructure as Code` · `Linux` · `Reverse Proxies`

### Production Engineering
`Security` · `Observability` · `Monitoring` · `Reliability` · `Performance` · `Deployment Automation`

---

# 🌐 Connect With Me

<p align="left">
  <a href="https://linkedin.com/in/mohsinali77">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mohsinalideveloper474@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/MohsinAli-2000">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

# 📊 GitHub Statistics

<p align="center">
  <img
    src="https://github-readme-stats.shion.dev/api?username=MohsinAli-2000&theme=dark&hide_border=false&include_all_commits=false&count_private=false"
    alt="Mohsin Ali's GitHub statistics"
  />
</p>

<p align="center">
  <img
    src="https://streak-stats.demolab.com/?user=MohsinAli-2000&theme=dark&hide_border=false"
    alt="GitHub contribution streak"
  />
</p>

<p align="center">
  <img
    src="https://github-readme-stats.shion.dev/api/top-langs/?username=MohsinAli-2000&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact"
    alt="Top programming languages"
  />
</p>

---

# 🐍 Contribution Activity

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/MohsinAli-2000/MohsinAli-2000/output/github-contribution-grid-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/MohsinAli-2000/MohsinAli-2000/output/github-contribution-grid-snake.svg"
    />
    <img
      src="https://raw.githubusercontent.com/MohsinAli-2000/MohsinAli-2000/output/github-contribution-grid-snake.svg"
      alt="GitHub contribution activity"
    />
  </picture>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=MohsinAli-2000&icon=0&color=0" alt="Profile views" />
</p>

<p align="center">
  <i>Building software that works in production — not just in tutorials.</i>
</p>
