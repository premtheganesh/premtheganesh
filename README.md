# Prem Ganesh Maddirala

**Software Engineer** · Building production systems with AI at scale

MS Data Science & Analytics @ Arizona State University · BE Computer Science @ BITS Dubai

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/premtheganesh)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/premtheganesh)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:premganeshmaddirala@gmail.com)

---

## What I Build

I design and ship **production-grade software systems**, from real-time streaming pipelines processing millions of records to LLM-powered automation platforms serving enterprise clients daily. My work sits at the intersection of **backend engineering**, **distributed systems**, and **applied AI**.

**Currently:** Software Engineer – AI @ Leaniar LLC, building an AI agent-based test-automation platform for enterprise SAP, JD Edwards and Salesforce systems, which cut manual QA effort ~80% and took 2-week QA cycles under 3 days.

- **Self-healing test automation** that turns analysts' plain-English Word test scripts into executable Playwright automation against a GxP-regulated Salesforce pharmacovigilance application, proving each step actually worked
- **A verb store** of parameterized code templates that assembles known steps deterministically, with no browser and no AI in the loop, removing per-document code duplication and the configuration drift it caused
- **An autonomous auto-fix loop** where a database poller detects unresolvable steps and launches a headless multi-subagent session that attaches to a persistent signed-in browser over the Chrome DevTools Protocol, probes the live DOM, and synthesizes stable selectors
- **Evidence-first validation**: every synthesized selector is checked statically, then live against a real record, before it is spliced back in. Zero false passes across ~15 step and document types, with evidence produced for human GxP sign-off
- **The supporting stack**: an LLM-powered SAP OData engine that auto-discovers the right API from 1,500+ services (1-2 days down to 15-20 minutes), an LLM plus pandas hybrid running model-written code in a sandbox at ~$0.001/query, Django REST APIs with RabbitMQ orchestration (~40% more throughput, ~65% less latency), and a locally hosted LLM council that cut inference cost ~40%

---

## Tech Stack

**Languages**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)](https://typescriptlang.org)
[![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)](https://java.com)
[![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=postgresql&logoColor=white)](https://en.wikipedia.org/wiki/SQL)

**Backend & APIs**

[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)](https://djangoproject.com)
[![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat&logo=socketdotio&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API)
[![Celery](https://img.shields.io/badge/Celery-37814A?style=flat&logo=celery&logoColor=white)](https://docs.celeryq.dev)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)](https://rabbitmq.com)
[![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat&logo=postman&logoColor=white)](https://restfulapi.net)

**Databases & Storage**

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)](https://postgresql.org)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)](https://mysql.com)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat&logo=neo4j&logoColor=white)](https://neo4j.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)](https://redis.io)
[![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)](https://github.com/facebookresearch/faiss)

**Cloud & DevOps**

[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)](https://aws.amazon.com)
[![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)](https://aws.amazon.com/lambda/)
[![Amazon SQS](https://img.shields.io/badge/Amazon_SQS-FF4F8B?style=flat&logo=amazonsqs&logoColor=white)](https://aws.amazon.com/sqs/)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://docker.com)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)](https://kafka.apache.org)

**ML & AI**

[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)](https://langchain.com)
[![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)](https://langchain-ai.github.io/langgraph/)
[![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)](https://anthropic.com)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)](https://playwright.dev)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)](https://opencv.org)

**Frontend & Visualization**

[![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)](https://react.dev)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://tableau.com)

---

## Featured Projects

### [TrendScout AI](https://github.com/premtheganesh/TrendScout-AI)
**Market Intelligence Platform** · Python, FastAPI, Next.js, MongoDB, Neo4j, FAISS

Conversational market-intelligence engine over **3,898 documents across 6 types**, ingested from **11 scheduled sources** and growing ~450 a week, scraped into MongoDB with spaCy NER entity extraction. Every document is indexed three ways: Okapi BM25 for exact terms, E5-base-v2 embeddings in a FAISS index for meaning, and a **10,851-entity Neo4j graph** (20,617 document-entity edges) for connections. The rankings are fused with Reciprocal Rank Fusion and measured at **0.882 nDCG@10** on a frozen snapshot with 22 labelled queries, reproducible from a fresh clone. A structured extraction layer pulls **136 funding rounds worth $24.4B at precision 1.00 and recall 0.93** on 41 hand-labelled articles. A Groq-hosted LLM only plans the query and writes the prose, citing every claim; ranking questions bypass similarity search entirely and rank the extracted rounds in the database. **~11,200 lines of Python behind ~20 FastAPI endpoints, a 2,600-line Next.js 16 site, and 327 tests across 27 files.**

`FastAPI` `Next.js` `MongoDB` `Neo4j` `FAISS` `BM25` `Reciprocal Rank Fusion` `spaCy` `Groq API` `RAG`

---

### Elastic Cloud Face Recognition Pipeline
**Cloud Architecture: IaaS → Serverless → Edge** · AWS, Python, PyTorch, Docker

A face-recognition service built four times over on AWS, taken from raw infrastructure to serverless to the edge. *(CSE 546 Cloud Computing, ASU)*

**IaaS.** A concurrent Python web tier on a single **EC2** instance behind an Elastic IP, accepting multipart uploads, persisting inputs to **S3**, and resolving predictions from a **SimpleDB** domain. Extended into a multi-tier application with **SQS** request and response queues decoupling the web tier from a **PyTorch** app tier launched from a custom **AMI** — plus a **hand-written autoscaling controller** (AWS Auto Scaling was explicitly disallowed) that scaled app-tier instances **from 0 up to 15 on queue depth** and back to 0 when the workload drained.

**PaaS.** The same pipeline rebuilt serverless as two containerised **AWS Lambda** functions published to **Elastic Container Registry** — MTCNN face detection behind a Lambda Function URL, InceptionResnetV1 recognition triggered by SQS.

**Edge.** Face detection moved off Lambda onto an **AWS IoT Greengrass** component running on a core device, receiving video frames over **MQTT** from an emulated IoT client, with IoT Thing certificates, policies and cloud discovery. Recognition stayed on Lambda in the cloud.

`AWS` `EC2` `S3` `SQS` `Lambda` `ECR` `IoT Greengrass` `MQTT` `Autoscaling` `boto3` `Docker` `PyTorch`

---

### Real-Time Chat Service
**Backend Engineering** · Python, FastAPI, Redis, PostgreSQL

Real-time messaging platform supporting 1-on-1 and group conversations using FastAPI WebSocket and Redis pub/sub for cross-instance message broadcasting. JWT authentication, PostgreSQL-backed message persistence with cursor-based pagination, online presence tracking, and read receipt delivery guarantees.

`FastAPI` `WebSockets` `Redis Pub/Sub` `PostgreSQL` `JWT` `Distributed Systems`

---

### Bulk Notification Service
**Async Systems** · Python, FastAPI, Celery, Redis, Docker

Asynchronous notification delivery platform using FastAPI and Celery with Redis as message broker. Jinja2-based email templating, per-recipient delivery tracking, exponential backoff retry logic, and configurable rate limiting. Deployed with Docker Compose and GitHub Actions CI/CD.

`FastAPI` `Celery` `Redis` `Docker Compose` `CI/CD` `Rate Limiting`

---

### [Graph Data Processing Pipeline](https://github.com/premtheganesh/Graph_Processing_Pipeline)
**Distributed Systems** · Python, Kafka, Kubernetes, Neo4j, Docker

Real-time streaming pipeline processing **millions of NYC taxi trip records**. Two-phase architecture: batch loading into Neo4j graph + Kafka-powered real-time streaming with Kubernetes orchestration. Implements PageRank and BFS graph algorithms via Cypher queries.

`Kafka` `Kubernetes` `Neo4j` `Docker` `Helm` `Distributed Systems` `Graph Algorithms`

---

### [EtherFi Portfolio Manager](https://github.com/premtheganesh/etherfi-portfolio-manager) · *ASU Claude Hackathon Winner 🏆*
**AI-Powered DeFi Platform** · JavaScript (React), Python (FastAPI), SQLite

AI-powered DeFi portfolio advisor rapid-prototyped in 48 hours. Integrates Claude API with ether.fi protocols and a multi-broker voting system where global freelance brokers validate AI-generated portfolio recommendations. Privacy-first architecture with self-improving AI feedback loops.

`React` `FastAPI` `Claude API` `SQLite` `DeFi` `System Design`

---

### [Aircraft Predictive Maintenance System](https://github.com/premtheganesh/IFRPM) *(In Progress)*
**ML Engineering** · Python, Flask, React, LSTM, Transformers

Predictive maintenance system forecasting Remaining Useful Life (RUL) of aircraft components using NASA C-MAPSS and NGAFID datasets. LSTM and Transformer models with multi-source data fusion. Deployed via Flask API + React dashboard for real-time monitoring.

`Flask` `React` `LSTM` `Transformers` `Time-Series` `Feature Engineering`

---

### [Sentiment Analyzer](https://github.com/premtheganesh/Sentiment_Analysis_of_Twitter_Data)
**NLP Pipeline** · Python, BERT, Scikit-learn, Gradio

End-to-end NLP pipeline processing **1.6M tweets**. Systematic comparison of 6 embedding methods (BoW, TF-IDF, Word2Vec, FastText, GloVe, BERT) across 5 ML models. Fine-tuned BERT achieved **92.7% accuracy**, a 13-15% improvement over classical baselines. Live Gradio demo.

`BERT` `Scikit-learn` `HuggingFace` `Gradio` `NLP` `Large-Scale Data`

---

### [Image Captioning System](https://github.com/premtheganesh/Image_Captioning)
**Computer Vision + NLP** · Python, PyTorch, TensorFlow, Groq API

Dual-approach image captioning: fine-tuned Llama-4 vision models via Groq API + custom MobileNetV3 encoder with Bidirectional LSTM + Attention-over-Attention decoder. Evaluated with BLEU, METEOR, ROUGE-L, and SPICE metrics. Includes text-to-speech output via gTTS.

`PyTorch` `TensorFlow` `Groq API` `Llama-4` `Attention Mechanisms` `Transfer Learning`

---

### [Driver Drowsiness Detection](https://github.com/premtheganesh/drowsinessdetection)
**Real-Time Computer Vision** · Python, OpenCV, Keras, dlib

Real-time drowsiness detection via webcam using multi-model pipeline: Haar Cascades for face detection, CNN for eye-state classification, and dlib 68-landmark model for yawn detection. Triggers audio alarm when drowsiness score exceeds threshold.

`OpenCV` `CNN` `dlib` `Real-Time Systems` `Safety-Critical`

---

### [Customer Segmentation Engine](https://github.com/premtheganesh/Online_Retail_Customer_Segmentation)
**Data Science** · Python, Scikit-learn

Customer segmentation on 54,000+ e-commerce transactions using RFM analysis. Compared K-Means, Hierarchical Clustering, and DBSCAN. K-Means achieved best Silhouette Score (~0.69) identifying 4 actionable segments: high-value, at-risk, occasional, and new customers.

`Clustering` `RFM Analysis` `Scikit-learn` `Business Analytics`

---

### [Hustle](https://github.com/premtheganesh/Hustle---Daily-Productivity-App) ⚡
**Personal Productivity App** · TypeScript, Python, CSS

A personal productivity app to track your daily routine, manage tasks, and stay consistent every single day. Daily routine tasks per day type (weekday / Saturday / Sunday) with tap-to-complete and drag-to-reorder, one-off tasks with priority levels and due dates, a homepage dashboard with progress ring / streak / XP level, Focus page combining goals + milestones with a Vision Board, 7/14/30-day XP and completion analytics, daily journaling, and weekly summaries.

`TypeScript` `React` `Python` `Full-Stack` `Gamification` `Product Design`

---

### [DeadlineIQ](https://github.com/premtheganesh/DeadlineIQ) · [Live Demo](https://deadline-iq.vercel.app)
**Web Application** · Vanilla JavaScript, HTML5, CSS3

AI-powered assignment management dashboard with custom priority scoring algorithm (urgency + grade weight + workload + grade impact). 5 dashboard views, Pomodoro timer, analytics, and confetti celebrations. Zero dependencies, dark mode, WCAG-compliant. Built in 48 hours for ASU App Challenge.

`JavaScript` `Responsive Design` `Algorithm Design` `Accessibility`

---

## Experience

| Role | Company | Duration |
|------|---------|----------|
| **Software Engineer – AI** | Leaniar LLC, California | Sep 2025 – Current |
| **Automation Engineer** | Konica Minolta, Dubai | Feb 2023 – Jul 2024 |
| **Digital Transformation Intern** | Konica Minolta, Dubai | Aug 2022 – Jan 2023 |
| **Data Analyst & Automation Intern** | Flydubai, Dubai | Aug 2021 – Jan 2022 |

---

## Let's Connect

I graduated in **May 2026** and I'm looking for **Software Engineer, AI Engineer, Forward Deployed Engineer, and Data Scientist** roles. Open to opportunities anywhere in the US.

If you're building something interesting, especially at the intersection of backend systems and AI, let's talk.

📫 **premganeshmaddirala@gmail.com** · [LinkedIn](https://linkedin.com/in/premtheganesh)
