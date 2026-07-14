# 👋 Hi, I'm Harsh Sharma

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&width=650&lines=MSCS-AI+%40+University+of+Southern+California;NeuroSymbolic+AI+%7C+Reinforcement+Learning;Knowledge+Graphs+%7C+Agentic+AI+%7C+LLMs;Building+scalable%2C+production-ready+AI+systems)](https://git.io/typing-svg)

![Profile Views](https://komarev.com/ghpvc/?username=Harsh-31&color=6C63FF&style=for-the-badge)

---

## About Me

I'm a Master's student in Computer Science (AI track) at the **University of Southern California**, focused on building scalable, production-grade AI systems across language, reasoning, and multi-agent environments. I work end-to-end from designing neurosymbolic architectures and training small language models to deploying agentic AI workflows and backend services on the cloud.

I'm especially interested in **NeuroSymbolic AI, Reinforcement Learning, Knowledge Graphs, and Agentic AI systems** architectures that combine the flexibility of neural models with the guarantees of symbolic reasoning. I care about clean system design, explainability, and translating research ideas into practical, high-impact solutions.

Before USC, I spent 3+ years at Shell as a Software Engineer building enterprise API integration solutions that shipped to production and delivered measurable business value.

**🎯 Actively seeking full-time job opportunities for 2027 in ML/AI Engineering and ML/AI Research**

---

## Professional Experience

**Backend & Cloud Engineer Intern @ USC Grand Challenges Scholars Program** • Los Angeles, CA • *Jul 2026 – Present*
- Designing and Developing backend engineering solution for USC GCSP Network Portal for 100+ institutions.

**ML Research Engineer Intern @ IRT Lab, University of South Carolina** • *May 2026 – Present*
- Developing a **GNN-based knowledge graph encoder** to replace an ID-pooling baseline in a Neurosymbolic RL system, targeting improved typed-relation reasoning across constraints, preferences, and entities in editable specifications.
- Contributing to the **PALMS (Personal Adaptive Learning Management System)** project. Designed the **Course Knowledge Graph** schema and deployed it on Neo4J and built the **OCR + transcript ingestion pipeline** that extracts video frames, runs Tesseract OCR on slide content, aligns them with timestamped transcripts, and integrates the output with the User KG to drive personalized adaptive learning.
- Contributing to the development of a **Small Language Model for food & nutrition**

**AI Research Engineer Intern @ USC Marshall School of Business** • Los Angeles, CA • *Feb 2026 – Present*
- Built **"Mulholland"**, a Neurosymbolic multi-agent system simulating high-stakes governance negotiations across **13 autonomous agents** that negotiate within deterministic legal constraints. Used a **self-hosted Qwen 2.5-7B-Instruct model served via vLLM** inside SLURM-scoped jobs on USC CARC HPC and scaled to **100 parallel simulations** via SLURM job arrays with per-job temporary lifecycle for reproducibility and cost control.
- Engineered end-to-end Python ETL pipeline analysing **30M+ job postings** across 10 organizational culture dimensions; processed 50+ Parquet files with schema normalization and cross-file deduplication.
- Executed large-scale web scraping of **6,200+ European data center facilities**; built structured datasets with capacity, operational status, location, and infrastructure details.

**AI Engineer Volunteer @ USC GRIDS (Graduates Rising in Data Science)** • *Feb 2026 – Apr 2026*
- Engineered a responsible-AI auditing framework enforcing LLM prompt policy compliance at scale: embedding-based policy violation detection, token-budget guardrails, and RAG context relevance scoring with **100% detection accuracy** on Natural Questions and LongBench benchmarks.
- Deployed a FastAPI service for context-engineering safety validation and conducted adversarial red-teaming against policy guardrails.

**AI Engineer Intern @ Varlyq Technologies** • *May 2025 – Jul 2025*
- Architected an end-to-end AI-powered interview simulator (Python, GPT-4) with audio recording, speech-to-text, TTS generation, and automated answer scoring; hardened reliability via edge-case handling for exit recognition and role reversal.

**Associate Software Engineer @ Shell India Markets Private Limited** • Bengaluru • *Aug 2022 – Jul 2025*
- Delivered **7 API Integration Solutions** for Shell Market Hub, generating **$130K in operational savings** and **$195K in annual savings** through ≥50% reduction in airport processing time.
- Built AIS-based Salesforce MDM integration ($80K/year savings); implemented Salesforce–Shell Recharge via Azure; migrated MuleSoft to AIS; built Pub/Sub + gRPC Platform Events listener eliminating ~2 months of manual migration effort.
- Automated GitHub attestation across **22,000+ enterprise repositories** using Node.js; led an Azure OpenAI & Cognitive Search Virtual Assistant POC for Software Engineering workflows.
- **Winner** — Shell Business Platform Functional Excellence Award (CoE Ideathon 2024); 3× Star of the Month recognitions; Project Process Hackathon (2025)

---

## Featured Projects

### [BrandSync — Multi-Agent Video Ad Generation System](https://github.com/YOUR_GITHUB_USERNAME/brandsync)
> Agentic AI pipeline that turns a business website URL into a cinematic video ad — fully automated

- **Tech**: Python, LangGraph, Ollama (Qwen 2.5), Google ADK, Gemini, Nano Banana Pro, Lyria 3, Veo
- **Architecture**: Strategist ↔ Critic negotiation loop (actor–critic pattern) producing a validated `BrandBrief`; downstream tool-using agents handle image generation, ranking, music, TTS, and video composition
- **Highlights**: Structured-output enforcement via Pydantic schemas, hybrid local/cloud stack (open-source reasoning + managed generation), Supervisor agent for feedback routing

### [Neurosymbolic Clinical Fraud Detection Pipeline](https://github.com/YOUR_GITHUB_USERNAME/neurosymbolic-clinical-nlp)
> Explainable, hallucination-resistant medical coding + Fraud, Waste & Abuse (FWA) detection

- **Tech**: Python, GPT-4o, NetworkX, ICD-10 / HCC / CMS rulebooks, FastAPI
- **Architecture**: Neural extraction (LLM pulls clinical entities → ICD-10 / RxNorm / CPT codes) + symbolic reasoning engine that validates every extraction against a healthcare knowledge graph encoding real medical relationships and CMS billing rules
- **Highlights**: Produces a **CMS-defensible audit trail** rather than an opaque confidence score; catches upcoding, unsupported billing complexity, and clinical contradictions; designed for payer workflows where explainability is a compliance requirement

---

## Research & Publications

- **Comparative Performance of Deep Learning Architectures in Lower Grade Glioma Segmentation** — *Indian Patent and Design Journal*
- **Breast Cancer Detection: Comparative Analysis of Machine Learning Classification Techniques** — *IEEE*
- **Network Security in Software Defined Networks (SDN)** — *IEEE*

**Speaker / Invitee** — Applied Machine Learning Conference 2026 (USA), API Days NYC 2024, SciML Workshop @ ICERM Lab, API World 2024, AIDevcon 2025 Bangalore.

---

## Technical Expertise

### AI & Machine Learning

| &nbsp; | &nbsp; |
| :--- | :--- |
| **Large Language Models & Agents**<br>LangChain, LangGraph, MCP, Agentic AI<br>RAG, LoRA / QLoRA, Prompt engineering<br>vLLM | **NeuroSymbolic AI & Knowledge Graphs**<br>NetworkX, GNNs, Symbolic reasoning engines<br>Knowledge graph construction & querying<br>Multi-agent systems with constraint validation |
| **Classical ML & Deep Learning**<br>PyTorch, TensorFlow, scikit-learn<br>BiLSTM, CNNs, Transformers, GNNs<br>Applied NLP, Computer Vision | **MLOps & Deployment**<br>FastAPI, Docker, SLURM / HPC<br>Azure (Logic Apps, Function Apps, APIM, Key Vault, Service Bus)<br>AWS, CI/CD, GitHub Actions |

### Tech Stack

```yaml
Languages:
  Primary:   [Python, Core Java]
  Secondary: [C++, C#, JavaScript, Go, SQL]

ML / AI:
  Deep Learning:     [PyTorch, TensorFlow]
  LLM Orchestration: [LangChain, LangGraph, MCP, Google ADK]
  Serving:           [Ollama, vLLM, FastAPI]
  Data:              [NumPy, Pandas]

Databases & Vector Stores:
  Relational:  [PostgreSQL, MongoDB]
  Vector:      [Qdrant, ChromaDB]
  Messaging:   [RabbitMQ, Azure Service Bus]

Cloud & Infrastructure:
  Cloud:       [Microsoft Azure, AWS]
  Containers:  [Docker]
  HPC:         [SLURM, USC CARC]
  Version:     [Git, GitHub Actions]

Backend & Integration:
  Frameworks:  [FastAPI, .NET Core, Node.js, Express.js]
  Azure AIS:   [Logic Apps, Function Apps, API Management, Key Vault]
```

### Certifications

- Microsoft Certified: **Azure Fundamentals (AZ-900)**
- Microsoft Certified: **Azure AI Fundamentals (AI-900)**
- **ISC2** Certified in Cybersecurity (CC)
- Cisco CCNA Routing & Switching — Introduction to Networks
- Green Software Practitioner (Linux Foundation)

---

## Achievements & Recognition

| Award | Achievement | Year |
| :--- | :--- | :--- |
| **Winner** | Shell Business Platform Functional Excellence Award — CoE Ideathon | 2024 | Project Process Hackathon | 2025
| **Star of the Month** | Shell IDE API/Integration Capability Centre (×3 — Sep 2023, Jul 2024, Aug 2024) | 2023–24 |
| **Appreciation** | Shell GitHub Workstream — enterprise-wide repository automation | 2024 |
| **Co-Founder** | A-Coders Community — mentored 300+ students on placements, resumes, LinkedIn | 2020–24 |
| **Recognition** | Featured on NewYork Times Square Billboard USA - for helping college students in crafting their resume | 2025

---

## Currently Exploring

- **NeuroSymbolic AI** — combining neural models with symbolic reasoning grounded in **Knowledge Graph ontologies** for explainable, hallucination-resistant systems to make systems Trustworthy.
- **Reinforcement Learning** — classical RL, constraint-grounded RL, typed-relation reasoning, and knowledge-graph-conditioned policies.
- **ML / AI Infrastructure** — self-hosted model serving (vLLM), SLURM-based HPC workflows, distributed inference, and cost-efficient production ML systems.
- **Small Language Models** — domain-specific pre-training, custom tokenization, and neurosymbolic grounding for specialized vocabularies.

---

## GitHub Analytics

![Harsh's GitHub stats](https://github-readme-stats.vercel.app/api?username=Harsh-31&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=6C63FF&icon_color=6C63FF&text_color=FFFFFF)
![GitHub Streak](https://streak-stats.demolab.com/?user=Harsh-31&theme=radical&hide_border=true&background=0D1117&stroke=6C63FF&ring=6C63FF&fire=FF6B6B&currStreakLabel=6C63FF)
 
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Harsh-31&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=6C63FF&text_color=FFFFFF&langs_count=8)

---

## Open to Collaborate On

- **Research** — NeuroSymbolic AI, Reinforcement Learning, Knowledge Graphs, Multi-Agent Systems, Small Language Models, ML Model Optimization and Infrastructure
- **Open Source** — Agentic AI frameworks, LLM evaluation & monitoring pipelines, knowledge-graph tooling
- **Industry Projects** — Production ML systems, LLM-based backend services, cloud-native AI applications
- **Mentorship** — Career guidance for CS students transitioning into ML/AI

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harshsharma-3107)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_GITHUB_USERNAME)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharma.harsh3107@gmail.com)
[![Location](https://img.shields.io/badge/Los_Angeles,_CA-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com/?q=Los+Angeles,+CA)

---

### 💭 Philosophy

> **"Neural models generalize, symbols reason, and infrastructure decides whether either ever reaches the real world. I build where all three meet grounded, efficient, and small enough to actually run."**

---

*Last updated: July 2026*
