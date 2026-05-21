---
title: Projects
icon: fas fa-project-diagram
order: 2
---

## Dira – Agentic Civic Intelligence Platform

- **Overview**: A multi-agent system automating civic feedback management at scale.
- **Key Technologies**: Jaseci (Jac), OSP graphs, Google Gemini Vision, PostgreSQL with pgvector, Python NLP microservices
- **Technical Achievements**:
  - Deployed multi-agent system for automated intake, classification, and spatial routing of civic feedback
  - Integrated Google Gemini Vision for multimodal incident severity assessment from user-uploaded images
  - Implemented semantic deduplication using PostgreSQL vector embeddings and clustering to reduce redundant manual reviews

## MedRAG - Clinical Report Intelligence System

- **Overview**: RAG-powered assistant for radiology and imaging workflows, designed to simplify medical report drafting for clinicians.
- **Key Technologies**: Python, RAG architecture, pgvector, Streamlit, n8n, Gemini, Groq Cloud, Pinecone
- **Technical Achievements**:
  - Built a symptom-driven retrieval workflow that identifies similar MRI/scanning reports from historical records
  - Returned editable report templates to reduce clinician documentation time while preserving human review
  - Developed and tested the system through Streamlit prototypes and n8n-powered automation flows
  - Optimized retrieval reliability and latency for production-scale usage (5,000+ documents/month)

## Qwen3 LLM Rebuild (From Scratch)

- **Overview**: Functional replica of the Qwen3 Large Language Model built from first principles.
- **Key Technologies**: Python, PyTorch, Transformer architecture, attention mechanisms
- **Technical Achievements**:
  - Implemented complete transformer architecture including attention mechanisms and training dynamics
  - Demonstrated efficiency-aware model design under constrained compute and dataset size
  - Achieved strong NLP performance benchmarks despite resource limitations

## Model Chaining & Experiment Tracking Pipeline

- **Overview**: Multi-model ML orchestration system for production inference and reproducibility.
- **Key Technologies**: Docker Compose, LangChain, MLflow, Python
- **Technical Achievements**:
  - Deployed multi-model ML pipelines for orchestrated model chaining and inference
  - Integrated MLflow for comprehensive experiment tracking, model versioning, and reproducibility
  - Built containerized workflows ensuring consistency across applied ML projects

## Agentic Codebase Genius

- **Overview**: Autonomous agent system for intelligent code analysis and architectural reasoning.
- **Key Technologies**: AI agents, tool-use workflows, codebase reasoning, Python
- **Technical Achievements**:
  - Built autonomous agent system capable of reasoning over large software codebases
  - Designed multi-step, tool-using agent workflows to simulate human-level code understanding
  - Enabled architectural question answering and dependency analysis at scale

## Intelligent Trader – Multi-Agent Data Pipeline & Orchestration System

- **Overview**: Sophisticated data pipeline for financial forecasting and decision orchestration with multi-agent architecture.
- **Key Technologies**: Python, FastAPI, Docker, Celery, Redis, PostgreSQL with Alembic migrations
- **Technical Achievements**:
  - Designed layered multi-agent pipeline for real-time data ingestion, feature extraction, forecasting, and decision orchestration
  - Built containerized end-to-end workflows using Docker and Celery with Redis message broker for distributed task orchestration
  - Implemented reproducible backtesting pipelines and comprehensive monitoring infrastructure
  - Managed database migrations and schema versioning for governed, auditable execution at scale

## Mizigo DTD - Door-to-Door Delivery Platform

- **Overview**: Mobile logistics platform inspired by ride-hailing patterns, built to coordinate door-to-door goods delivery.
- **Key Technologies**: Flutter, Firebase, Google Maps, PostgreSQL
- **Technical Achievements**:
  - Built user flows for delivery requests, assignment, live location context, and order status tracking
  - Integrated Google Maps APIs for route context, pickup/drop-off mapping, and location-aware dispatch support
  - Combined Firebase services with PostgreSQL-backed data workflows for reliable app operations and persistence

## Additional Public GitHub Projects

### FoodChatBot

- **Repository**: [jumanewton/foodchatbot](https://github.com/jumanewton/foodchatbot)
- **Overview**: NLP-enabled assistant for food ordering and support workflows.
- **Tech Stack**: Python, NLP, API integrations

### YOLOVision Experiments

- **Repository**: [jumanewton/yolovision](https://github.com/jumanewton/yolovision)
- **Overview**: Computer vision experimentation and model prototyping with object detection workflows.
- **Tech Stack**: Python, Jupyter Notebook, computer vision tooling

### SocialApp

- **Repository**: [jumanewton/socialapp](https://github.com/jumanewton/socialapp)
- **Overview**: Flutter-based social/mobile product prototype with practical mobile engineering patterns.
- **Tech Stack**: Flutter, Dart